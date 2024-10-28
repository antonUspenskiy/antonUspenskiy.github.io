---
layout: default
title: Статьи
permalink: /articles/
---

<h1>Статьи</h1>
{% for post in site.categories.articles %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% if post.image %}
  ![{{ post.title }} cover image]({{ post.image }}){: style="width: 300px; height: auto;"}
{% endif %}
{% endfor %}
