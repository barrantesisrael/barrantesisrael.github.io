---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

I teach courses related to Bioinformatics and Medical Informatics at the University of Rostock. My teaching focuses on quantitative methods for medical research and modern high-throughput technologies in biomedical sciences.

## Courses

Below are the courses I regularly teach at the University of Rostock. For detailed course information and registration, please visit the [university course catalog](https://lsf.uni-rostock.de).

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
