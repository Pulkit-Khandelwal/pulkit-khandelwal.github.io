---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

{% include base_path %}

{% for post in site.blog reversed %}
  {% include archive-single.html %}
{% endfor %}
