---
layout: archive
title: "Projets"
permalink: /portfolio/
author_profile: true
---

{% include base_path %}

{% for post in site.portfolio reversed %}
  {% include archive-single.html %}
{% endfor %}
