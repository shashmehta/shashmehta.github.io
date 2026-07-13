---
layout: page
title: CV
permalink: /experience/
description: Projects, technical leadership, teaching, education, and selected recognition.
nav: true
nav_order: 3
---

<div class="experience-page">
  <section class="experience-summary" aria-labelledby="profile-heading">
    <div>
      <p class="experience-summary__label">Profile</p>
      <h2 id="profile-heading">Shashvat Mehta</h2>
      <p>High school senior building software for computational biology, robotics, and technical visualization.</p>
      <a class="button" href="{{ '/assets/pdf/shashvat-mehta-resume.pdf' | relative_url }}">Download résumé (PDF)</a>
    </div>
    <dl>
      <div><dt>Email</dt><dd><a href="mailto:{{ site.email }}">{{ site.email }}</a></dd></div>
      <div><dt>Website</dt><dd><a href="{{ site.url }}">{{ site.url | remove: 'https://' }}</a></dd></div>
      <div><dt>Location</dt><dd>San Mateo, California</dd></div>
    </dl>
  </section>

  <nav class="section-nav" aria-label="CV sections">
    <a href="#projects">Projects</a><a href="#leadership">Leadership</a><a href="#teaching">Teaching</a><a href="#education">Education</a><a href="#skills">Skills</a>
  </nav>

  <section class="experience-section" id="projects">
    <div class="section-heading"><h2>Projects &amp; Research</h2></div>
    <div class="experience-grid">
      <article class="experience-card">
        <p class="experience-card__meta">2026 · Research software</p>
        <p class="experience-card__category">Computational Biology</p>
        <h3>SCRIBE</h3>
        <p>
          Built an open-source Python pipeline with Pragnya Keerthivasan to explore interpretable biomarker candidates in
          single-cell RNA-seq data. Presented the work as an AACR research poster in San Diego in April 2026.
        </p>
        <ul class="tag-list"><li>Python</li><li>AnnData</li><li>Random Forests</li><li>ComBat</li><li>Harmony</li></ul>
        <a href="{{ '/projects/scribe/' | relative_url }}">View details</a>
      </article>
      <article class="experience-card">
        <p class="experience-card__meta">2024 · Technical visualization</p>
        <p class="experience-card__category">Design &amp; Engineering</p>
        <h3>waveOrder Animation</h3>
        <p>
          Modeled microscope components and animated the imaging workflow in Blender to explain label-free phase and
          polarization imaging. This project also reflects technical animation and 3D-modeling work on microscopy and
          laboratory equipment.
        </p>
        <ul class="tag-list"><li>Blender</li><li>3D modeling</li><li>Technical animation</li><li>Microscopy</li></ul>
        <a href="{{ '/projects/waveorder/' | relative_url }}">View details</a>
      </article>
    </div>
  </section>

  <section class="experience-section" id="leadership">
    <div class="section-heading"><h2> Leadership</h2></div>
    <div class="experience-grid">
      <article class="experience-card experience-card--wide">
        <p class="experience-card__meta">2021–present · Vortex Robotics, FTC Team 14969</p>
        <p class="experience-card__category">Robotics</p>
        <h3>Team Captain and Robotics Coach</h3>
        <p>
          Served as co-captain from 2021–2024, then coached newer team members from 2024 onward. Led design and software
          discussions, planning, teamwork, and technical instruction for an FTC regional championship team.
        </p>
        <ul class="tag-list"><li>Java</li><li>FTC robot software</li><li>Computer vision</li><li>Hardware debugging</li><li>Mentoring</li></ul>
        <a href="{{ '/teaching/ftc-youth-coach/' | relative_url }}">View details</a>
      </article>
      <article class="experience-card">
        <p class="experience-card__meta">2026–2027 · San Mateo High School</p>
        <p class="experience-card__category"> Leadership</p>
        <h3>Associated Student Body Treasurer</h3>
        <p>Managed event budgets, deposits, reimbursements, payments, ticket sales, and financial records with peers and staff.</p>
        <ul class="tag-list"><li>Budgeting</li><li>Financial records</li><li>Event operations</li></ul>
      </article>
      <article class="experience-card">
        <p class="experience-card__meta">2024–2026 · San Mateo High School</p>
        <p class="experience-card__category">Communication</p>
        <h3>Varsity Mock Trial Witness</h3>
        <p>Prepared testimony and practiced direct and cross-examinations, building clearer public speaking under pressure.</p>
        <ul class="tag-list"><li>Public speaking</li><li>Case analysis</li><li>Critical thinking</li></ul>
      </article>
    </div>
  </section>

  <section class="experience-section" id="teaching">
    <div class="section-heading"><h2>Teaching &amp; Mentoring</h2></div>
    <div class="experience-grid">
      <article class="experience-card">
        <p class="experience-card__meta">2024 · Personal tutoring</p>
        <p class="experience-card__category">Teaching</p>
        <h3>3D Modeling and Programming Tutor</h3>
        <p>Taught Blender, Python, and Scratch through one-on-one, project-based lessons.</p>
        <ul class="tag-list"><li>Blender</li><li>Python</li><li>Scratch</li><li>Curriculum design</li></ul>
        <a href="{{ '/teaching/Tutoring3D/' | relative_url }}">View details</a>
      </article>
      <article class="experience-card">
        <p class="experience-card__meta">2024 · Foster City Library</p>
        <p class="experience-card__category">Teaching</p>
        <h3>Summer Programming Instructor</h3>
        <p>Taught Python and Scratch fundamentals through hands-on lessons and creative projects for younger students.</p>
        <ul class="tag-list"><li>Python</li><li>Scratch</li><li>Programming fundamentals</li></ul>
        <a href="{{ '/teaching/summerPrograming24/' | relative_url }}">View details</a>
      </article>
      <article class="experience-card">
        <p class="experience-card__meta">2023–2024 · FIRST Lego League</p>
        <p class="experience-card__category">Mentoring</p>
        <h3>Youth Coach</h3>
        <p>Helped a rookie team debug code, improve robot consistency, and optimize autonomous routines.</p>
        <ul class="tag-list"><li>Robotics mentorship</li><li>Debugging</li><li>Autonomous routines</li></ul>
        <a href="{{ '/teaching/fll-youth-coach/' | relative_url }}">View details</a>
      </article>
      <article class="experience-card">
        <p class="experience-card__meta">2023 · Vortex Robotics</p>
        <p class="experience-card__category">Teaching</p>
        <h3>Summer Robotics Classes</h3>
        <p>Taught hardware, programming, and design fundamentals while students built and tested Arduino robots.</p>
        <ul class="tag-list"><li>Hardware</li><li>Programming</li><li>Robot design</li></ul>
        <a href="{{ '/teaching/summerRobotics23/' | relative_url }}">View details</a>
      </article>
    </div>
  </section>

  <section class="experience-section" id="community">
    <div class="section-heading"><h2>Community Work</h2></div>
    <div class="experience-grid">
      <article class="experience-card">
        <p class="experience-card__meta">2025 · Foster City Library</p>
        <p class="experience-card__category">Community work</p>
        <h3>Summer Intern</h3>
        <p>Supported youth programs, library operations, community outreach, and a Scratch programming class.</p>
        <ul class="tag-list"><li>Youth programming</li><li>Community outreach</li><li>Library operations</li></ul>
        <a href="{{ '/experience/foster-city-library/' | relative_url }}">View details</a>
      </article>
      <article class="experience-card">
        <p class="experience-card__meta">2025 · San Mateo County</p>
        <p class="experience-card__category">Community work</p>
        <h3>Clinic Volunteer</h3>
        <p>Greeted patients and supported day-to-day operations in a community healthcare setting.</p>
        <ul class="tag-list"><li>Patient support</li><li>Healthcare service</li><li>Community service</li></ul>
        <a href="{{ '/experience/san-mateo-county-clinic/' | relative_url }}">View details</a>
      </article>
    </div>
  </section>

  <section class="experience-section" id="education">
    <div class="section-heading"><h2>Education</h2></div>
    <div class="resume-grid">
      <section class="resume-panel">
        <p class="resume-panel__meta">2023–2027 · San Mateo High School</p>
        <h3>High School</h3>
        <p>Weighted GPA: 4.57/4.00. Coursework includes AP Biology, AP Computer Science, AP Calculus AB/BC, AP Physics, and Biotechnology.</p>
        <ul class="tag-list"><li>Computer science</li><li>Biology</li><li>Calculus</li><li>Physics</li></ul>
      </section>
      <section class="resume-panel">
        <p class="resume-panel__meta">Summer 2026 · Stanford Summer Session</p>
        <h3>CS106B: Programming Abstractions</h3>
        <p>Studied C++, data abstractions, recursion, and time and space complexity.</p>
        <ul class="tag-list"><li>C++</li><li>Data abstractions</li><li>Recursion</li><li>Complexity analysis</li></ul>
      </section>
    </div>
  </section>

  <section class="experience-section" id="skills">
    <div class="section-heading"><h2>Skills &amp; Selected Recognition</h2></div>
    <div class="resume-grid">
      <section class="resume-panel">
        <p class="resume-panel__meta">Languages &amp; data</p>
        <h3>Software and Machine Learning</h3>
        <ul class="tag-list"><li>Python</li><li>Java</li><li>C++</li><li>HTML/CSS</li><li>AnnData</li><li>Random Forests</li><li>Single-cell RNA-seq</li></ul>
      </section>
      <section class="resume-panel">
        <p class="resume-panel__meta">Robotics &amp; design</p>
        <h3>Engineering Tools</h3>
        <ul class="tag-list"><li>Computer vision</li><li>Autonomous routines</li><li>Hardware debugging</li><li>Blender</li><li>Onshape</li><li>Technical animation</li></ul>
      </section>
      <section class="resume-panel resume-panel--wide">
        <p class="resume-panel__meta">Selected recognition</p>
        <h3>Honors</h3>
        <p>AP Scholar; FTC Inspire, Think, Design, Connect, and Control Awards; and FTC Finalist Alliance recognition.</p>
      </section>
    </div>
  </section>

  <section class="experience-section" id="supporting-experience">
    <div class="section-heading"><h2>Supporting Experience</h2></div>
    <div class="resume-grid">
      <section class="resume-panel resume-panel--wide">
        <p class="resume-panel__meta">2024–present · Independent projects</p>
        <h3>Freelance 3D Modeling and Animation</h3>
        <p>Completed a small number of 3D modeling and animation projects for friends and family, building practical experience in scoping requests, iterating on visual work, and delivering clear technical and creative assets.</p>
        <ul class="tag-list"><li>Blender</li><li>3D modeling</li><li>Animation</li><li>Client communication</li></ul>
      </section>
    </div>
  </section>
</div>
