---
layout: about
title: About
permalink: /
custom_about: true
social: false
---

<section class="portfolio-hero" aria-labelledby="hero-heading">
  <div class="portfolio-hero__copy">
    <p class="eyebrow">Student software engineer · computational biology · robotics</p>
    <h1 id="hero-heading">I build software for biological research and robotics.</h1>
    <p class="portfolio-hero__lede">
      My recent work includes SCRIBE, an open-source single-cell RNA-sequencing pipeline presented at AACR, and software
      and technical leadership for an FTC regional championship robotics team. I like turning complex technical problems
      into tools and explanations that other people can use.
    </p>
    <div class="portfolio-actions" aria-label="Primary links">
      <a class="button button--primary" href="{{ '/projects/' | relative_url }}">View Projects</a>
      <a class="button" href="{{ '/cv/' | relative_url }}">View Résumé</a>
      <a class="button" href="https://github.com/shashmehta" rel="me">GitHub</a>
    </div>
    <p class="todo-note">[TODO: Add final one-page résumé PDF]</p>
  </div>
  <figure class="profile-portrait profile-portrait--hero">
    <img src="{{ '/assets/img/prof_pic.PNG' | relative_url }}" alt="Portrait of Shashvat Mehta" loading="eager">
    <figcaption>Shashvat Mehta · San Mateo High School</figcaption>
  </figure>
</section>

<section class="portfolio-section" aria-labelledby="featured-heading">
  <div class="section-heading">
    <p class="eyebrow">Selected projects</p>
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
        <p class="featured-card__contribution">
          <strong>Contribution:</strong> Built the Python pipeline with a collaborator and presented it at AACR in April 2026.
        </p>
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
        <h3>recOrder Animation</h3>
        <p>A Blender animation explaining how an open-source microscopy tool visualizes cells without stains.</p>
        <p class="featured-card__contribution"><strong>Contribution:</strong> Modeled microscope components and animated the imaging workflow.</p>
        <ul class="tag-list" aria-label="recOrder technologies"><li>Blender</li><li>3D modeling</li><li>Animation</li></ul>
        <div class="card-actions"><a href="{{ '/projects/recOrder/' | relative_url }}">Case study</a></div>
      </div>
    </article>

    <article class="featured-card">
      <div class="featured-card__body">
        <p class="featured-card__type">Robotics leadership</p>
        <h3>Vortex Robotics</h3>
        <p>FTC robot software, design discussions, competition strategy, and technical mentoring for younger students.</p>
        <p class="featured-card__contribution">
          <strong>Contribution:</strong> Served as team captain and software lead for a regional championship team.
        </p>
        <ul class="tag-list" aria-label="Robotics technologies"><li>Java</li><li>FTC</li><li>Computer vision</li><li>Debugging</li></ul>
        <div class="card-actions"><a href="{{ '/experience/#leadership' | relative_url }}">View experience</a></div>
      </div>
    </article>

  </div>
</section>

<section class="portfolio-section" aria-labelledby="focus-heading">
  <div class="section-heading">
    <p class="eyebrow">What I work with</p>
    <h2 id="focus-heading">Technical Focus</h2>
  </div>
  <div class="focus-grid">
    <article><h3>Computational Biology</h3><p>Single-cell RNA-seq analysis, batch correction, and interpretable candidate ranking through SCRIBE.</p></article>
    <article><h3>Software &amp; Machine Learning</h3><p>Python, Java, C++, data pipelines, Random Forest classifiers, and practical debugging.</p></article>
    <article><h3>Robotics &amp; Engineering</h3><p>FTC software, computer vision, hardware integration, mechanical design, and team strategy.</p></article>
    <article><h3>Technical Communication</h3><p>Research posters, technical animation, programming classes, and one-on-one mentoring.</p></article>
  </div>
</section>

<section class="portfolio-section about-summary" aria-labelledby="about-heading">
  <div class="about-summary__copy">
    <div class="section-heading"><p class="eyebrow">A little context</p><h2 id="about-heading">About</h2></div>
    <p>
      I’m a senior at San Mateo High School who builds software for computational biology and robotics. I enjoy problems
      that require understanding a complex system, testing ideas carefully, and making the result useful to someone else.
    </p>
    <p>
      Through Vortex Robotics, I have led software and team strategy while mentoring younger students. Teaching robotics,
      programming, and 3D modeling has also made me more deliberate about how I explain technical decisions.
    </p>
    <p class="personal-note">Outside school, I enjoy cooking, spending time with friends and family, and going to the gym.</p>
  </div>
</section>

<section class="portfolio-section contact-section" id="contact" aria-labelledby="contact-heading">
  <div><p class="eyebrow">Get in touch</p><h2 id="contact-heading">Contact</h2></div>
  <p>I’m interested in software engineering, computational biology, robotics, and research internship opportunities.</p>
  <div class="portfolio-actions">
    <a class="button button--primary" href="mailto:{{ site.email }}">Email me</a>
    <a class="button" href="https://www.linkedin.com/in/shashvat-mehta/">LinkedIn</a>
    <a class="button" href="https://github.com/shashmehta">GitHub</a>
  </div>
</section>
