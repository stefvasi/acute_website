---
layout: default
title: Research
description: "Six interconnected themes spanning vibrotactile perception, prosthetic feedback, sensory substitution, spatial audio, room acoustics, and human attention."
---

<section class="page-hero page-hero--slides">
  <div class="page-hero__slideshow">
    <img class="page-hero__slide" src="{{ '/images/lab_equipment.jpg' | relative_url }}" alt="">
    <img class="page-hero__slide" src="{{ '/images/kemar.jpg' | relative_url }}" alt="">
    <img class="page-hero__slide" src="{{ '/images/lobes_mold.jpg' | relative_url }}" alt="">
  </div>
  <div class="page-hero__inner">
    <p class="page-hero__eyebrow">What we study</p>
    <h1 class="page-hero__title">Research</h1>
    <p class="page-hero__sub">Six interconnected themes spanning vibrotactile perception, prosthetic feedback, sensory substitution, spatial audio, room acoustics, and human attention — each grounded in formal experiments and informing device design.</p>
  </div>
</section>

{% for area in site.data.research %}
{% assign num = forloop.index | prepend: "0" | slice: -2, 2 %}
<div class="ra{% if forloop.index == 2 or forloop.index == 4 or forloop.index == 6 %} ra--flip{% endif %}">
  <div class="ra__img">
    <img src="{{ area.image | relative_url }}" alt="{{ area.image_alt }}">
  </div>
  <div class="ra__txt">
    <div class="ra__num">{{ num }}</div>
    <h2>{{ area.title }}</h2>
    {% for p in area.description %}
    <p>{{ p }}</p>
    {% endfor %}
    <div class="ra__pubs">
      <p class="ra__pubs-label">Key publications</p>
      <ul>
        {% for pub in area.pubs %}
        <li>{{ pub.text }} <a href="https://doi.org/{{ pub.doi }}" target="_blank" rel="noopener">doi:{{ pub.doi }}</a></li>
        {% endfor %}
      </ul>
    </div>
  </div>
</div>
{% endfor %}
