---
layout: default
title: "Статьи"
permalink: /articles/
---
<h1>Статьи</h1>
{% for post in site.categories.articles %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
