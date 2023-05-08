---
layout: page
permalink: /talks/
title: talks
description: I enjoy presenting/sharing projects I worked on, both in technical and research contexts. Find below a selected list of meetups, workshops or conferences I was invited as speaker.
nav: true
nav_order: 4
horizontal: true
years: [2023, 2019]
selected_papers: true # includes a list of papers marked as "selected={true}"
---

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>