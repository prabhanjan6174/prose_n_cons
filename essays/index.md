---
layout: page
title: Essays
excerpt: 'Origin Stories'
search_omit: true
---


<ul class="post-list">
{% for post in site.categories.essays %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></article></li>
{% endfor %}
</ul>
