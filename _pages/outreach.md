---
layout: default
permalink: /outreach/
title: outreach
nav: true
years: [2020]
nav_order: 3
---

Coming soon!

<!-- _pages/outreach.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f pub_talks -q @*[year={{y}}]* %}
{% endfor %}

</div>