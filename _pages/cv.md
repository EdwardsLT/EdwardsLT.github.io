---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* BSc Physics, University of Bath, 2016
* MSc Physics, Cardiff University, 2017
* PhD Physics, Cardiff University, 2021 (expected)

Work experience
======
  
Skills
======

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Software
======
  <ul>{% for post in site.software %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>