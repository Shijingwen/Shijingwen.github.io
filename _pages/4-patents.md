---
layout: page
permalink: /patents/
title: Patents
# description: publications by categories in reversed chronological order. generated by jekyll-scholar.
years: [2019]
nav: true
nav_order: 3
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f patents -q @*[year={{y}}]* %}
{% endfor %}

</div>