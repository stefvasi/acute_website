# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

Jekyll static site for the **ACUTE Lab** (ACoUstic and Tactile Engineering) at the University of Iceland. Uses a custom design system with a single CSS file. The site is part of a contract project (Mar–Nov 2026, ~70 hrs/month). Website development has a 24h budget with a due date of 2026-04-02.

## Commands

```bash
bundle exec jekyll serve        # dev server at http://localhost:4000 with live reload
bundle exec jekyll build        # build to _site/
```

## Structure

```
_layouts/default.html     — base layout (head, nav, main, footer)
_layouts/member.html      — individual team member profile page (extends default)
_includes/header.html     — sticky nav with hamburger menu at ≤768px
_includes/footer.html     — dark footer
assets/css/main.css       — entire design system (single file, plain CSS — not Sass)
index.md                  — home page (hero slideshow, about, highlights, stats, gallery, team, partners)
research/index.md         — alternating 50/50 image/text splits for 6 research areas
team/index.md             — team member grid (cards link to individual profiles)
team/<slug>/index.md      — 11 individual member profile pages
publications/index.md     — chronological publication list with DOI links
contact/index.md          — contact info, map link, partners & funders with logos
images/                   — lab photos, SVGs, partners/, team/
```

Prototype files (`preview.html`, `ACUTE_preview_images.html`, `ACUTE_inner_pages.html`) remain at root but are excluded from the build via `_config.yml`.

## Design System (`assets/css/main.css`)

CSS custom properties on `:root` — use these everywhere, never hardcode values:

- **Fonts:** `--font-display` (Space Grotesk), `--font-body` (Inter), `--font-mono` (DM Mono)
- **Colours:** `--bg-dark` (#0D1B2F navy), `--bg-surface` (#f5f2ed), `--bg-alt` (#eceae4), `--accent` (#ff8000 orange), `--text` (#1B1B27), `--text-muted`, `--text-dim`, `--border` (#D6D1C7)
- **Layout:** `--max-w: 1200px`

Key layout patterns:
- `.page-hero` — dark hero banner used on interior pages (research, team, contact, member)
- `.ra` / `.ra--flip` — alternating 50/50 image/text research area splits
- `.contact-block` — `180px 1fr` grid for contact page rows
- `.team__grid` — 6-col grid on homepage; team page uses inline grid overrides (2/3/4 col)
- `.person-card` — team member card with photo, name, role; clickable on team page (wrapped in `<a>`)
- `.bio-drawer` — expandable drawer on homepage showing member bio + "Read more" link
- `.member-profile` — two-column layout (240px photo + 1fr body) for individual member pages
- `.highlights__grid` — 3-column card grid → responsive collapse
- `.feature__row` / `.feature__row--reverse` — 50/50 feature splits on homepage
- `.pub-item` — publication entry with optional thumbnail

## Hero Slideshows

- **Homepage:** JS-driven crossfade (5s interval, 9 slides including logo slide). Code in `_layouts/default.html`.
- **Research page:** CSS-only crossfade (15s keyframe loop, 3 slides). Uses `.page-hero--slides`.

## Mobile Navigation

Hamburger menu at ≤768px. Toggle button in `_includes/header.html`, JS handler in `_layouts/default.html`. Slide-in panel from right.

## Team Member Pages

Each member has a page at `team/<slug>/index.md` using `layout: member`. Frontmatter fields:
- `title` (required) — Full name
- `role` (required) — Role title
- `photo` (required) — Path to image, e.g. `/images/team/filename.jpg`
- `email` (optional) — Email address
- `profile` (optional) — External profile URL

To add a new member:
1. Create `team/<slug>/index.md` with the above frontmatter
2. Add photo to `images/team/`
3. Add a `.person-card` entry in both `index.md` (homepage, with `data-bio` and `data-url`) and `team/index.md` (team page, wrapped in `<a>` tag)

## Deployment (GitHub Actions → GitHub Pages)

Workflow at `.github/workflows/deploy.yml` builds with Jekyll 4.3 on push to `main` and deploys via `actions/deploy-pages`.

**Required repo setting:** Settings → Pages → Source must be set to **GitHub Actions** (not "Deploy from branch").

**baseurl:** Currently `""` in `_config.yml` (assumes custom domain or org-root Pages). If publishing at a subpath (e.g. `username.github.io/acute_website_v2`), change to `baseurl: "/acute_website_v2"` — but the GHA workflow already passes `--baseurl` automatically from the Pages config, so this is only needed for local builds.

Every link in templates uses `| relative_url` — this is correct and must be preserved.

## Known Issues & Pending Work

- **Images are oversized** (21 MB total). 8 files over 1 MB each. Must compress before launch.
- **5 team members need real bios and photos:** Eric Sumner, Satish Bonthu, Haflidi Asgeirsson, Stefanos Vasilakis, Emma Shannon.
- **No favicon, robots.txt, sitemap, or 404 page yet.**
- **No Open Graph meta tags** — social sharing has no preview.
- **Publications page loads thumbnails from external URLs** (pub.mdpi-res.com) — fragile.
- **No `rel="noopener"` on `target="_blank"` links.**
- **Not yet deployed** — all changes are local, no commits/pushes made.
- Full go-live checklist tracked in Notion: "Website Go-Live Checklist" under the "Lab Website Development" task.
