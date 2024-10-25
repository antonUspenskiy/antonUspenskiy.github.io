---
layout: default
title: "Статьи"
permalink: /articles/
---
{% for post in site.articles %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
