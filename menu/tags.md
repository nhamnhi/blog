---
layout: page
title: Tags
permalink: /tags
---


<h1> dev f </h1>
<ul class="tags">
    {% for tag in site.tags %}
      <li>
        <a href="/tags/#{{ tag[0] }}" class="post-tag">{{ tag[0] }}</a>
      </li>
    {% endfor %}
</ul>

