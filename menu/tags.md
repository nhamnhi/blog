---
layout: page
title: Tags
permalink: /tags
---

<ul>
  {% for tag in site.tags %}
    <li>{{ tag }}</li>
  {% endfor %}
</ul>
