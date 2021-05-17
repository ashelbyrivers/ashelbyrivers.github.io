---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

This page was last updated May 2020. Be sure to check my CV, ResearchGate, or Google Scholar for my most updated list of publications.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
