---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021]
nav: true
---


#### Papers

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>