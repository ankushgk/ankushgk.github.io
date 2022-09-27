---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

This lists some of the projects that I have done/am doing. Click the link to know more about the project. 

{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

