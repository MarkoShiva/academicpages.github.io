---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

A placeholder for some of the projects that I will write here.

{% include base_path %}


{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}
