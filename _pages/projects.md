---
layout: page
title: projects
permalink: /projects/
description: Selected research projects in computational neuroimaging, medical image analysis, and computational anatomy.
nav: true
nav_order: 3
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{% assign sorted_projects = site.projects | sort: "importance" %}

<div class="row row-cols-1 row-cols-md-3">
{% for project in sorted_projects %}
  {% include projects.liquid %}
{% endfor %}
</div>
</div>
