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

<span>[
  {% for tag in page.tags %}
    {% capture tag_name %}{{ tag }}{% endcapture %}
    <a href="/tag/{{ tag_name }}"><code class="highligher-rouge"><nobr>{{ tag_name }}</nobr></code>&nbsp;</a>
  {% endfor %}
]</span>