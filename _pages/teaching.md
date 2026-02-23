---
layout: archive
title: "Teaching"
permalink: /teaching/
author_profile: true
---

I teach courses in biostatistics, medical informatics, and epidemiology at the University Medical Center Rostock. My teaching focuses on quantitative methods for medical research and modern high-throughput technologies in biomedical sciences.

## Current Courses (Winter Semester 2025/26)

Below are the courses I'm currently teaching at the University of Rostock. For detailed course information and registration, please visit the [university course catalog](https://lsf.uni-rostock.de).

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}
