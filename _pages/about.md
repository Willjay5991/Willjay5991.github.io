---
layout: about
title: About
permalink: /
description: 

profile:
  align: right
  image: me2.jpg
  address: 

news: true  # includes a list of news items
selected_papers: true # includes a list of papers marked as "selected={true}"
social: false  # includes social icons at the bottom of the page
---

P.H.D, China <br>
yjiedu [at] foxmail.com<br>
[Google scholar](https://scholar.google.com/citations?user=g_HnkmIAAAAJ&hl=en) | [Github](https://github.com/Willjay5991) || [gitee](https://gitee.com/willjayhomesite) | 

Ph.D  2023 NWPU <br>
Bachelor 2017 Xinjiang U <br>


**Research interest:** transfer learning, machine learning, federated learning, privacy-preserving

<div class="About">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>