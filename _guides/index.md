---
layout: archive
title: "Οδηγοι"
author_profile: false
index : true
permalink: /guides/
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  teaser: /assets/img/headers/guides-header.jpeg
  overlay_image: /assets/img/headers/guides-header.jpeg
---

<div class="grid__wrapper">
  {% for post in site.guides %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>