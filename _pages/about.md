---
layout: about
title: About
permalink: /
custom_about: true

news: false # includes a list of news items
selected_papers: false # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page
---

<section class="about-hero" aria-labelledby="about-hero-heading">
  <div class="about-hero__content">
    <h1 id="about-hero-heading"><span>Shashvat</span> Mehta</h1>
    <p class="about-hero__subtitle">High school senior passionate about the intersection of computer science, engineering, and biology.</p>
  </div>
</section>

<section class="about-section about-intro" aria-labelledby="about-intro-heading">
  <div class="about-intro__content">
    <h2 id="about-intro-heading">About</h2>
    <p>
      I'm Shashvat Mehta, a senior at San Mateo High School interested in the intersection of computer science,
      engineering, and biology. I'm drawn to projects where technical problem-solving can make complex systems easier to
      understand, whether that means building robotics software, analyzing biological data, or creating tools others can
      use.
    </p>
    <p>
      A lot of my growth has come through Vortex Robotics, my FIRST Tech Challenge team. As captain, I helped lead
      design, software, and competition strategy, and I now mentor younger students in robotics, programming, and project
      development. I also tutor students in 3D modeling and coding, which has strengthened both my technical foundation
      and my ability to explain ideas clearly.
    </p>
    <p>
      My research work focuses on using machine learning to analyze single-cell RNA sequencing data and identify
      interpretable cancer biomarkers. Through SCRIBE, an open-source Python pipeline, I've explored how computational
      tools can support biological research.
    </p>

    <section class="about-inline-section" aria-labelledby="about-focus-heading">
      <h2 id="about-focus-heading">Focus Areas</h2>
      <div class="about-focus-grid">
        <a class="about-focus-card" href="{{ '/projects/' | relative_url }}">
          <h3>Computational Biology</h3>
          <p>Machine learning, single-cell RNA sequencing, and interpretable cancer biomarker discovery.</p>
        </a>
        <a class="about-focus-card" href="{{ '/projects/' | relative_url }}">
          <h3>Robotics &amp; Engineering</h3>
          <p>FTC leadership, robot design, software development, and mentoring younger students.</p>
        </a>
        <a class="about-focus-card" href="{{ '/projects/' | relative_url }}">
          <h3>Teaching &amp; Communication</h3>
          <p>Tutoring, workshops, technical explanation, and public speaking.</p>
        </a>
      </div>
    </section>

    <section class="about-inline-section about-personal" aria-labelledby="about-personal-heading">
      <h2 id="about-personal-heading">Outside of academics</h2>
      <p>
        Outside of academics, I love to spend time cooking, for both myself and my family. I love to try new recipes and
        show my creativity through my dishes. Other than cooking, I enjoy spending time with my freinds and family and
        going to the gym.
      </p>
    </section>
  </div>
  <figure class="about-intro__media">
    <img
      class="img-fluid rounded z-depth-1"
      src="{{ '/assets/img/prof_pic.PNG' | relative_url }}"
      alt="Portrait of Shashvat Mehta"
      loading="eager"
    >
    <figcaption>
      <span>San Mateo High School</span>
      <span>12th Grade</span>
    </figcaption>
  </figure>
</section>
