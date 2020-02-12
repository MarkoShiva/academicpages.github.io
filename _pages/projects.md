---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

A placeholder for some of the projects that I will write here.


{% if author.github %}
  You can also find some of my projects on <u><a href="{{author.github}}">my GitHub profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
