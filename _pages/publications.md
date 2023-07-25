---
layout: page
permalink: /publications/
title: papers
description: \* means equal contribution. Full list on <a href="[https://www.nature.com/articles/s42256-023-00626-4](https://scholar.google.com/citations?user=uZXQuYAAAAAJ&hl=zh-CN)">Google Scholar</a>.
years: [Preprint, 2023, 2022, 2021, 2020, 2019]
nav: true
nav_order: 2
---

<div class="publications">

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
