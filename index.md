---
layout: default
title: Home
---

<!-- HERO -->
<section class="hero" id="hero-slideshow">
  <div class="hero__slideshow">
    <div class="hero__slide is-active">
      <img src="{{ '/images/lab_group.jpg' | relative_url }}" alt="ACUTE Lab">
    </div>
    <div class="hero__slide">
      <img src="{{ '/images/sensory_substitution.jpg' | relative_url }}" alt="Sensory substitution research">
    </div>
    <div class="hero__slide">
      <img src="{{ '/images/kemar.jpg' | relative_url }}" alt="KEMAR mannequin in anechoic chamber">
    </div>
    <div class="hero__slide">
      <img src="{{ '/images/room_acoustics.jpg' | relative_url }}" alt="Room acoustics simulation">
    </div>
    <div class="hero__slide hero__slide--logo">
      <img src="{{ '/images/logo.svg' | relative_url }}" alt="ACUTE" class="hero__slide-logo">
    </div>
    <div class="hero__slide">
      <img src="{{ '/images/mannequin.jpg' | relative_url }}" alt="Prosthetic feedback mannequin">
    </div>
    <div class="hero__slide">
      <img src="{{ '/images/scan_pattern.png' | relative_url }}" alt="Attention and foraging research">
    </div>
    <div class="hero__slide">
      <img src="{{ '/images/KRI_sound_of_vision_170908_027.jpg' | relative_url }}" alt="Sound of Vision sensory substitution device">
    </div>
    <div class="hero__slide hero__slide--award">
      <img src="{{ '/images/carousel_ICT-2018-Sound-of-Vision-Award-652x1024.png' | relative_url }}" alt="ICT 2018 Sound of Vision Award">
    </div>
  </div>
  <div class="hero__inner">
    <div class="hero__label">ACoUstic and Tactile Engineering · University of Iceland</div>
    <h1 class="hero__title">
      We decode<br>
      <em>the senses —</em><br>
      and put them<br>
      to work.
    </h1>
    <p class="hero__sub">Vibrotactile interfaces. Spatial audio. Room acoustics.<br>
      Research that bridges perception science and engineering.</p>
    <div class="hero__actions">
      <a href="{{ '/research/' | relative_url }}" class="btn btn--primary">Explore our research</a>
      <a href="{{ '/contact/' | relative_url }}" class="btn btn--ghost">Get in touch</a>
    </div>
  </div>
</section>

<!-- ABOUT -->
<section class="about">
  <div class="container">
    <div class="about__grid">
      <div class="about__intro">
        <span class="section-label">About the lab</span>
        <h2>Engineering at the boundary of human perception</h2>
      </div>
      <div class="about__body">
        <p>ACUTE is an interdisciplinary research group at the University of Iceland. We sit at the intersection of human perception science, engineering design, and applied acoustics.</p>
        <p>We collaborate with prosthetics manufacturer <strong>Össur ehf.</strong>, spatial audio company <strong>Treble Technologies</strong>, and clinicians at <strong>Landspítali — National University Hospital</strong>. Funded by RANNÍS, NordForsk, and the European Union.</p>
      </div>
    </div>
  </div>
</section>

<!-- RESEARCH HIGHLIGHTS -->
<section class="highlights" id="research">
  <div class="container">
    <div class="highlights__header">
      <span class="section-label">Research areas</span>
      <h2>Six interconnected themes</h2>
    </div>
    <div class="highlights__grid">

      <article class="highlight-card">
        <div class="highlight-card__img-wrap">
          <img class="highlight-card__img" src="{{ '/images/sensory_substitution.jpg' | relative_url }}" alt="Vibrotactile Perception">
        </div>
        <div class="highlight-card__body">
          <div class="highlight-card__number">01</div>
          <h3>Vibrotactile Perception</h3>
          <p>Mapping the frequency, amplitude, and spatial limits of touch on the forearm and wrist.</p>
          <a href="{{ '/research/' | relative_url }}" class="highlight-card__link">Read more →</a>
        </div>
      </article>

      <article class="highlight-card">
        <div class="highlight-card__img-wrap">
          <img class="highlight-card__img" src="{{ '/images/mannequin.jpg' | relative_url }}" alt="Prosthetic Feedback">
        </div>
        <div class="highlight-card__body">
          <div class="highlight-card__number">02</div>
          <h3>Prosthetic Feedback</h3>
          <p>Vibrotactile sleeves that restore proprioception for transfemoral amputees.</p>
          <a href="{{ '/research/' | relative_url }}" class="highlight-card__link">Read more →</a>
        </div>
      </article>

      <article class="highlight-card">
        <div class="highlight-card__img-wrap">
          <img class="highlight-card__img" src="{{ '/images/lab_equipment.jpg' | relative_url }}" alt="Sensory Substitution">
        </div>
        <div class="highlight-card__body">
          <div class="highlight-card__number">03</div>
          <h3>Sensory Substitution</h3>
          <p>Devices that translate sound and vision into touch for visually and hearing-impaired users.</p>
          <a href="{{ '/research/' | relative_url }}" class="highlight-card__link">Read more →</a>
        </div>
      </article>

      <article class="highlight-card">
        <div class="highlight-card__img-wrap">
          <img class="highlight-card__img" src="{{ '/images/kemar.jpg' | relative_url }}" alt="Spatial Audio & HRTFs">
        </div>
        <div class="highlight-card__body">
          <div class="highlight-card__number">04</div>
          <h3>Spatial Audio &amp; HRTFs</h3>
          <p>Synthetic pinna models and machine learning to personalise 3D sound.</p>
          <a href="{{ '/research/' | relative_url }}" class="highlight-card__link">Read more →</a>
        </div>
      </article>

      <article class="highlight-card">
        <div class="highlight-card__img-wrap">
          <img class="highlight-card__img" src="{{ '/images/room_acoustics.jpg' | relative_url }}" alt="Room Acoustics">
        </div>
        <div class="highlight-card__body">
          <div class="highlight-card__number">05</div>
          <h3>Room Acoustics</h3>
          <p>Structure-preserving model reduction achieving 100× speedup in wave simulation.</p>
          <a href="{{ '/research/' | relative_url }}" class="highlight-card__link">Read more →</a>
        </div>
      </article>

      <article class="highlight-card">
        <div class="highlight-card__img-wrap">
          <img class="highlight-card__img" src="{{ '/images/scan_pattern.png' | relative_url }}" alt="Attention & Perception">
        </div>
        <div class="highlight-card__body">
          <div class="highlight-card__number">06</div>
          <h3>Attention &amp; Perception</h3>
          <p>Cross-modal foraging, visual synchrony effects, and haptic illusions.</p>
          <a href="{{ '/research/' | relative_url }}" class="highlight-card__link">Read more →</a>
        </div>
      </article>

    </div>
  </div>
</section>

<!-- STATS -->
<section class="stats">
  <div class="container">
    <div class="stats__grid">
      <div class="stats__item"><span class="stats__number">93%</span><span class="stats__label">Pattern recognition accuracy with sequential vibrotactile stimulation</span></div>
      <div class="stats__item"><span class="stats__number">100×</span><span class="stats__label">Speedup in wave-based room acoustics simulation</span></div>
      <div class="stats__item"><span class="stats__number">20</span><span class="stats__label">Pinna replicas in the open Viking HRTF Dataset v2</span></div>
      <div class="stats__item"><span class="stats__number">500k+</span><span class="stats__label">Cochlear implant users who could benefit from vibrotactile music augmentation</span></div>
    </div>
  </div>
</section>

<!-- GALLERY -->
<section class="gallery">
  <div class="container">
    <div class="gallery__header">
      <span class="section-label">Inside the lab</span>
      <h2>Equipment &amp; environment</h2>
    </div>
    <div class="gallery__strip">
      <figure class="gallery__item">
        <img src="{{ '/images/lab_group.jpg' | relative_url }}" alt="Lab group">
        <figcaption class="gallery__caption">Lab Group</figcaption>
      </figure>
      <figure class="gallery__item">
        <img src="{{ '/images/kemar.jpg' | relative_url }}" alt="KEMAR + pinna replicas">
        <figcaption class="gallery__caption">KEMAR + Pinna Replicas</figcaption>
      </figure>
      <figure class="gallery__item">
        <img src="{{ '/images/lab_equipment.jpg' | relative_url }}" alt="Lab equipment">
        <figcaption class="gallery__caption">Vibrotactile Actuators</figcaption>
      </figure>
      <figure class="gallery__item">
        <img src="{{ '/images/lobes_mold.jpg' | relative_url }}" alt="Ear lobe molds">
        <figcaption class="gallery__caption">Ear Molds</figcaption>
      </figure>
      <figure class="gallery__item">
        <img src="{{ '/images/spatial_audio.png' | relative_url }}" alt="Spatial Audio HRTFs">
        <figcaption class="gallery__caption">HRTF Measurement Setup</figcaption>
      </figure>
      <figure class="gallery__item">
        <img src="{{ '/images/Sound-of-Vision-Team-Award-1024x784.png' | relative_url }}" alt="Sound of Vision team receiving award">
        <figcaption class="gallery__caption">Sound of Vision Award</figcaption>
      </figure>
    </div>
  </div>
</section>

<!-- FEATURED RESEARCH -->
<section class="feature">

  <div class="feature__row">
    <div class="feature__img-col">
      <img src="{{ '/images/sensory_substitution.jpg' | relative_url }}" alt="Haptic interfaces">
    </div>
    <div class="feature__text-col">
      <span class="section-label">Haptic interfaces</span>
      <h3>Designing touch that speaks</h3>
      <p>Sequential vibrotactile patterns achieve 93% recognition accuracy on the forearm — nearly four times the 26% seen with simultaneous stimulation. This finding shapes the core programming logic of every wearable device we build.</p>
      <span class="feature__meta">Yeganeh et al. · Applied Sciences 2024</span>
      <a href="https://doi.org/10.3390/app14010043" class="feature__link" target="_blank">Read the paper →</a>
    </div>
  </div>

  <div class="feature__row feature__row--reverse">
    <div class="feature__img-col">
      <img src="{{ '/images/spatial_audio.png' | relative_url }}" alt="Spatial audio">
    </div>
    <div class="feature__text-col">
      <span class="section-label">Spatial audio</span>
      <h3>Your ear, rebuilt in silicone</h3>
      <p>We 3D-scan real pinnae, alter one geometric feature at a time, cast them in silicone, and measure their acoustic fingerprint. This controlled methodology lets us isolate exactly which part of your ear shape determines where you hear sound coming from.</p>
      <span class="feature__meta">Sumner, Riedel &amp; Unnthorsson · Cogent Engineering 2025</span>
      <a href="https://doi.org/10.1080/23311916.2025.2536150" class="feature__link" target="_blank">Read the paper →</a>
    </div>
  </div>

  <div class="feature__row">
    <div class="feature__img-col">
      <img src="{{ '/images/room_acoustics.jpg' | relative_url }}" alt="Room acoustics">
    </div>
    <div class="feature__text-col">
      <span class="section-label">Room acoustics</span>
      <h3>100× faster, equally accurate</h3>
      <p>Our structure-preserving model order reduction compresses the wave equation into a low-dimensional form that runs 100 times faster than a full simulation — without sacrificing stability at complex material boundaries. Built with Treble Technologies.</p>
      <span class="feature__meta">Bonthu et al. · Int. J. Numerical Methods in Engineering 2026</span>
      <a href="https://doi.org/10.1002/nme.70295" class="feature__link" target="_blank">Read the paper →</a>
    </div>
  </div>

</section>

<!-- TEAM -->
<section class="team" id="team">
  <div class="container">
    <div class="team__header">
      <span class="section-label">The people</span>
      <h2>Our team</h2>
    </div>
    <div class="team__grid">

      <div class="person-card" data-bio="Professor of Mechanical Engineering at the University of Iceland. Research interests include vibrotactile interfaces, prosthetic feedback, and sensory substitution systems." data-url="{{ '/team/runar-unnthorsson/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/runar.jpg' | relative_url }}" alt="Rúnar Unnþórsson">
        </div>
        <div class="person-card__name">Rúnar Unnþórsson</div>
        <div class="person-card__role">Principal Investigator</div>
        <div class="person-card__links">
          <a href="mailto:runson@hi.is">Email</a>
          <a href="https://english.hi.is/staff/runson" target="_blank">Profile</a>
        </div>
      </div>

      <div class="person-card" data-bio="Professor of Cognitive Psychology at the University of Iceland. Research focuses on visual attention, cross-modal foraging, haptic illusions, and the perceptual science underlying sensory interfaces." data-url="{{ '/team/arni-kristjansson/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/arni.jpg' | relative_url }}" alt="Árni Kristjánsson">
        </div>
        <div class="person-card__name">Árni Kristjánsson</div>
        <div class="person-card__role">Principal Investigator</div>
        <div class="person-card__links">
          <a href="mailto:ak@hi.is">Email</a>
          <a href="https://english.hi.is/staff/ak" target="_blank">Profile</a>
        </div>
      </div>

      <div class="person-card" data-bio="Dr. Makarov earned his PhD in Psychology from the University of Iceland (2024), with dissertation research on using multimodal attention to design sensory substitution devices. He holds an MSc in Applied Cognitive Psychology from Utrecht University. His work focuses on multisensory perception, tactile music, haptic illusions, and human–computer interaction. He currently leads the Haptic Harmony project, exploring the translation of music into tactile experiences via wearable devices." data-url="{{ '/team/ivan-makarov/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/ivan.jpg' | relative_url }}" alt="Ivan Makarov">
        </div>
        <div class="person-card__name">Ivan Makarov</div>
        <div class="person-card__role">Postdoctoral Researcher</div>
      </div>

      <div class="person-card" data-bio="Nashmin is a PhD student specializing in wearable technology, haptics, and human–computer interaction. She holds BSc and MSc degrees in Mechanical Engineering, with expertise in signal processing, system optimization, and haptic systems evaluation. Her doctoral research focuses on the VibroSleeve, a wearable vibrotactile device for forearm stimulation, advancing understanding of vibrotactile perception for assistive technologies." data-url="{{ '/team/nashmin-yeganeh/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/nashmin.jpg' | relative_url }}" alt="Nashmin Yeganeh">
        </div>
        <div class="person-card__name">Nashmin Yeganeh</div>
        <div class="person-card__role">PhD Candidate</div>
      </div>

      <div class="person-card" data-bio="Mohammadmahdi holds BSc and MSc degrees in Biomedical Engineering from Islamic Azad University in Tehran. His doctoral research focuses on the design and development of tactile sensory feedback systems to enhance control and perception in bionic prosthetic limbs, conducted in collaboration with Össur and funded by the Rannís Technical Development Fund." data-url="{{ '/team/mohammadmahdi-karimi/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/mahdi.jpg' | relative_url }}" alt="Mohammadmahdi Karimi">
        </div>
        <div class="person-card__name">Mohammadmahdi Karimi</div>
        <div class="person-card__role">PhD Candidate</div>
      </div>

      <div class="person-card" data-bio="Jonas is pursuing doctoral research in Virtual Acoustics, with expertise in room acoustic design, spatial audio, and sound design. He earned his BSc in Electrical Engineering and MSc in Sound and Vibration from Chalmers University of Technology. His current project, PAAAC, investigates perceptual aspects of virtual acoustics within the scope of human echolocation training." data-url="{{ '/team/jonas-karlberg/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/jonas.jpg' | relative_url }}" alt="Jonas Karlberg">
        </div>
        <div class="person-card__name">Jonas Karlberg</div>
        <div class="person-card__role">PhD Candidate</div>
      </div>

      <div class="person-card" data-bio="Eric is a PhD candidate at ACUTE Lab working on spatial audio and HRTF research." data-url="{{ '/team/eric-sumner/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/placeholder.svg' | relative_url }}" alt="Eric Michael Sumner">
        </div>
        <div class="person-card__name">Eric Michael Sumner</div>
        <div class="person-card__role">PhD Candidate</div>
      </div>

      <div class="person-card" data-bio="Satish is a PhD candidate at ACUTE Lab working on computational room acoustics and model order reduction." data-url="{{ '/team/satish-bonthu/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/satish.jpg' | relative_url }}" alt="Satish Kumar Bonthu">
        </div>
        <div class="person-card__name">Satish Kumar Bonthu</div>
        <div class="person-card__role">PhD Candidate</div>
      </div>

      <div class="person-card" data-bio="Hafliði is the Lab Manager at ACUTE Lab, overseeing day-to-day laboratory operations and equipment." data-url="{{ '/team/haflidi-asgeirsson/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/placeholder.svg' | relative_url }}" alt="Hafliði Ásgeirsson">
        </div>
        <div class="person-card__name">Hafliði Ásgeirsson</div>
        <div class="person-card__role">Lab Manager</div>
      </div>

      <div class="person-card" data-bio="Stefanos is an R&amp;D Engineer at ACUTE Lab, contributing to the development of hardware and software for research projects." data-url="{{ '/team/stefanos-vasilakis/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/stefanos.jpg' | relative_url }}" alt="Stefanos Vasilakis">
        </div>
        <div class="person-card__name">Stefanos Vasilakis</div>
        <div class="person-card__role">R&amp;D Engineer</div>
      </div>

      <div class="person-card" data-bio="Emma works on e-textiles and wearables design at ACUTE Lab, integrating textile-based sensing and actuation into wearable devices." data-url="{{ '/team/emma-shannon/' | relative_url }}">
        <div class="person-card__photo-wrap">
          <img src="{{ '/images/team/placeholder.svg' | relative_url }}" alt="Emma Shannon">
        </div>
        <div class="person-card__name">Emma Shannon</div>
        <div class="person-card__role">E-textiles &amp; Wearables Design</div>
      </div>

    </div>

    <!-- Bio drawer — inserted by JS below the grid row of the clicked card -->
    <div class="bio-drawer" id="bio-drawer" hidden>
      <button class="bio-drawer__close" aria-label="Close bio">&times;</button>
      <div class="bio-drawer__inner">
        <img class="bio-drawer__photo" src="" alt="">
        <div>
          <div class="bio-drawer__name"></div>
          <div class="bio-drawer__role"></div>
          <p class="bio-drawer__text"></p>
          <a class="bio-drawer__more" href="">Read more &rarr;</a>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- PARTNERS -->
<section class="partners">
  <div class="container">
    <div class="partners__header">
      <div>
        <span class="section-label">Collaboration &amp; funding</span>
        <h2>Partners &amp; funders</h2>
      </div>
    </div>
    <div class="partners__groups">

      <div>
        <div class="partners__group-label">Industry partners</div>
        <div class="partners__row">
          <a href="https://www.ossur.com" class="partner-logo" target="_blank" title="Össur ehf.">
            <img src="{{ '/images/partners/ossur.png' | relative_url }}" alt="Össur">
          </a>
          <a href="https://www.treble.tech" class="partner-logo" target="_blank" title="Treble Technologies">
            <img src="{{ '/images/partners/treble.png' | relative_url }}" alt="Treble Technologies">
          </a>
          <a href="https://www.landspitali.is" class="partner-logo" target="_blank" title="Landspítali — National University Hospital">
            <img src="{{ '/images/partners/landspitali.png' | relative_url }}" alt="Landspítali">
          </a>
        </div>
      </div>

      <div>
        <div class="partners__group-label">Funders</div>
        <div class="partners__row">
          <a href="https://www.rannis.is" class="partner-logo" target="_blank" title="RANNÍS — Icelandic Research Fund">
            <img src="{{ '/images/partners/rannis.png' | relative_url }}" alt="RANNÍS">
          </a>
          <a href="https://www.hi.is" class="partner-logo" target="_blank" title="University of Iceland">
            <img src="{{ '/images/partners/hi.png' | relative_url }}" alt="University of Iceland">
          </a>
          <a href="https://www.nordforsk.org" class="partner-logo" target="_blank" title="NordForsk">
            <img src="{{ '/images/partners/nordforsk.jpeg' | relative_url }}" alt="NordForsk">
          </a>
          <a href="https://ec.europa.eu/programmes/horizon2020" class="partner-logo" target="_blank" title="EU Horizon 2020">
            <img src="{{ '/images/partners/horizon.png' | relative_url }}" alt="EU Horizon 2020">
          </a>
          <a href="https://www.eurocc-access.eu" class="partner-logo" target="_blank" title="EUROCC2">
            <img src="{{ '/images/partners/eurocc2.png' | relative_url }}" alt="EUROCC2">
          </a>
          <a href="https://www.edihiceland.is" class="partner-logo" target="_blank" title="EDIH Iceland">
            <img src="{{ '/images/partners/edih_iceland.png' | relative_url }}" alt="EDIH Iceland">
          </a>
        </div>
      </div>

    </div>
  </div>
</section>
