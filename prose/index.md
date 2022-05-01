---
layout: page
title: Prose
excerpt: 'Origin Stories'
search_omit: true
---



<ul class="post-list">
{% for post in site.categories.prose %}
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span>
{% endfor %}
</ul>
