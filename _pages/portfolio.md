---
layout: archive
title: "Projets"
permalink: /portfolio/
author_profile: true
---

# Projets
## Projets

{% include base_path %}

{% assign projects = site.portfolio | sort: "order" %}
<div class="portfolio-grid">
{% for post in projects %}
  {% include archive-single.html type="portfolio" %}
{% endfor %}
</div>

<script>
  document.querySelectorAll(".portfolio-card").forEach(function (card) {
    card.addEventListener("click", function (event) {
      if (!event.target.closest("a")) {
        window.location.href = card.dataset.url;
      }
    });

    card.addEventListener("keydown", function (event) {
      if ((event.key === "Enter" || event.key === " ") && !event.target.closest("a")) {
        event.preventDefault();
        window.location.href = card.dataset.url;
      }
    });
  });
</script>
