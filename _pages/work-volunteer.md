---
layout: page
title: Volunteer
permalink: /volunteer/
description: Community service and volunteer experience
nav: false
display_categories: [Volunteer]
horizontal: false
---

<p class="compatibility-note">Community work is now part of the <a href="{{ '/experience/#community' | relative_url }}">CV</a>. Existing detail pages remain available.</p>

<div class="work-volunteer">
{% if page.display_categories %}
  {% for category in page.display_categories %}
  <a id="{{ category | slugify }}" href=".#{{ category | slugify }}">
    <h2 class="category">{{ category }}</h2>
  </a>
  {% assign categorized_experiences = site.experience | where: "category", category %}
  {% assign sorted_experiences = categorized_experiences | sort: "importance" %}
  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_experiences %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
  {% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_experiences %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
  {% endif %}
  {% endfor %}
{% endif %}
</div>
