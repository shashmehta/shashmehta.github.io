---
layout: about
title: About
permalink: /
custom_about: true
social: false
---

<section class="portfolio-hero" aria-labelledby="hero-heading">
  <div class="portfolio-hero__copy">
    <p class="eyebrow">Shashvat Mehta · Student at San Mateo High School · 12th Grade</p>
    <h1 id="hero-heading">High school student passionate about biological research and robotics.</h1>
    <p class="portfolio-hero__lede">
      My recent work includes SCRIBE, an open-source single-cell RNA-sequencing pipeline presented at AACR, and software
      and technical leadership for an FTC regional championship robotics team. I enjoy working through complex
      technical problems and turning them into tools other people can use.
    </p>
  </div>
  <figure class="profile-portrait profile-portrait--hero">
    <img src="{{ '/assets/img/prof_pic.PNG' | relative_url }}" alt="Portrait of Shashvat Mehta" loading="eager">
  </figure>
</section>

<section class="portfolio-section about-summary" aria-labelledby="about-heading">
  <div class="about-summary__copy">
    <div class="section-heading"><h2 id="about-heading">About</h2></div>
    <p>
      I’m Shashvat Mehta, a senior at San Mateo High School interested in the intersection of computer science, engineering, and biology. I enjoy working through technical problems, especially when the result is something useful or easier for other people to understand.
    </p>
    <p>
      Through Vortex Robotics, my old FIRST Tech Challange Team, I led software development and team strategy as captain before becoming a coach for younger students.
      Teaching robotics, programming, and 3D modeling has helped me get better at explaining technical ideas clearly.
    </p>
    <p>Outside school, I enjoy cooking, spending time with friends and family, and going to the gym.</p>
  </div>
</section>

<section class="portfolio-section" aria-labelledby="featured-heading">
  <div class="section-heading">
    <h2 id="featured-heading">Featured Work</h2>
  </div>
  <div class="featured-grid">
    <article class="featured-card featured-card--primary">
      <div class="featured-card__media">
        <img src="{{ '/assets/img/scribe_poster.jpg' | relative_url }}" alt="SCRIBE research poster presented at AACR" loading="eager">
      </div>
      <div class="featured-card__body">
        <p class="featured-card__type">Computational biology · open source</p>
        <h3>SCRIBE</h3>
        <p>Analyzes single-cell RNA-seq data and surfaces interpretable biomarker candidates for further investigation.</p>
        <p class="featured-card__contribution">Co-developed the Python pipeline with Pragnya Keerthivasan and presented the work at AACR in April 2026.</p>
        <ul class="tag-list" aria-label="SCRIBE technologies">
          <li>Python</li><li>AnnData</li><li>Random Forests</li><li>scRNA-seq</li>
        </ul>
        <div class="card-actions">
          <a href="{{ '/projects/scribe/' | relative_url }}">Case study</a>
          <a href="https://github.com/shashmehta/SCRIBE">GitHub</a>
          <a href="https://shashmehta-scribe.hf.space/">Demo</a>
        </div>
      </div>
    </article>

    <article class="featured-card">
      <div class="featured-card__body">
        <p class="featured-card__type">Technical visualization</p>
        <h3>waveOrder Animation</h3>
        <p>A Blender animation explaining how an open-source microscopy tool visualizes cells without stains.</p>
        <p class="featured-card__contribution">Modeled microscope components and animated the imaging workflow for Video 3 of the waveOrder preprint.</p>
        <ul class="tag-list" aria-label="waveOrder technologies"><li>Blender</li><li>3D modeling</li><li>Animation</li></ul>
        <div class="card-actions"><a href="{{ '/projects/waveorder/' | relative_url }}">Case study</a></div>
      </div>
    </article>

    <article class="featured-card">
      <div class="featured-card__body">
        <p class="featured-card__type">Robotics leadership</p>
        <h3>Vortex Robotics</h3>
        <p>FTC robot software, design discussions, competition strategy, and technical mentoring for younger students.</p>
        <p class="featured-card__contribution">
          Led robot software and team strategy as captain, then coached younger students in programming, hardware integration, and debugging.
        </p>
        <ul class="tag-list" aria-label="Robotics technologies"><li>Java</li><li>FTC</li><li>Computer vision</li><li>Debugging</li></ul>
        <div class="card-actions"><a href="{{ '/cv/#leadership' | relative_url }}">View experience</a></div>
      </div>
    </article>

  </div>
</section>

<section class="portfolio-section" aria-labelledby="focus-heading">
  <div class="section-heading">
    <h2 id="focus-heading">Technical Focus</h2>
  </div>
  <div class="focus-grid">
    <article><h3>Computational Biology</h3><p>Single-cell RNA-seq analysis, batch correction, and interpretable candidate ranking through SCRIBE.</p></article>
    <article><h3>Software &amp; Machine Learning</h3><p>Python, Java, C++, data pipelines, Random Forest classifiers, and practical debugging.</p></article>
    <article><h3>Robotics &amp; Engineering</h3><p>FTC software, computer vision, hardware integration, mechanical design, and team strategy.</p></article>
    <article><h3>Technical Communication</h3><p>Research posters, technical animation, programming classes, and one-on-one mentoring.</p></article>
  </div>
</section>

<section class="portfolio-section contact-section" id="contact" aria-labelledby="contact-heading">
  <div><h2 id="contact-heading">Contact</h2></div>
  <p>I’m interested in software engineering, computational biology, robotics, and research internship opportunities.</p>
  <div class="portfolio-actions">
    <a class="button button--primary" href="mailto:{{ site.email }}">Email me</a>
    <a class="button" href="https://www.linkedin.com/in/shashvat-mehta/">LinkedIn</a>
    <a class="button" href="https://github.com/shashmehta">GitHub</a>
  </div>
</section>
