---
layout: archive
title: "Blog"
permalink: /blog/
author_profile: true
---

## Upcoming Posts
* Introduciton to Level-Sets for Image Segmentation
* My experience as a Machine Learning/ Software Engineering intern in San Francisco
* Query Open Street Maps Data using a Python Wrapper
* Multi-processing in Python
* How to solve the class imbalance problem in Machine Learning

## Past Posts
{% include base_path %}

{% for post in site.blog reversed %}
  {% include archive-single.html %}
{% endfor %}
