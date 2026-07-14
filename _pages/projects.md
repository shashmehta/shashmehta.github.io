---
layout: page
title: Projects
permalink: /projects/
description: Research software, computational microscopy animation, and selected independent 3D projects.
nav: true
nav_order: 2
display_categories: [Research & Software, 3D Design & Animation]
horizontal: false
---

{% comment %}[TODO: Consider adding the FTC application after it is ready for public presentation.]{% endcomment %}

<div class="projects-intro">
  <p>
    My work ranges from computational biology software to microscopy animation and independent Blender projects.
  </p>
</div>

<div class="projects">
  {% for category in page.display_categories %}
    <section class="project-category" aria-labelledby="{{ category | slugify }}">
      <h2 class="category" id="{{ category | slugify }}">{{ category }}</h2>
      {% assign categorized_projects = site.projects | where: 'category', category %}
      {% assign sorted_projects = categorized_projects | sort: 'importance' %}
      <div class="row row-cols-1 row-cols-md-2">
        {% for project in sorted_projects %}
          {% include projects.liquid %}
        {% endfor %}
      </div>
    </section>
  {% endfor %}
</div>
