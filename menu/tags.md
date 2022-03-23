---
layout: page
title: Tags
permalink: /tags
---

<ul>
  {% for tags in page.tags %}
    <li>{{ tags }}</li>
  {% endfor %}
</ul>