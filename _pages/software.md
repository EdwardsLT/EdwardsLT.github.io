---
layout: archive
title: "Software"
permalink: /software/
author_profile: true
---

{% if author.github %}
  You can also find my software on <u><a href="{{author.github}}">my Github page</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.software reversed %}
  {% include archive-single.html %}
{% endfor %}
