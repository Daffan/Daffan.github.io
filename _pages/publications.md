---
layout: page
permalink: /publications/
title: Publications
years: [2024, 2023, 2022, 2021]
nav: true
---

<div class="publications">

{% for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>