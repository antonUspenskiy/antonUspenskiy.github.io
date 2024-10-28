---
layout: default
title: Статьи
permalink: /articles/
---

<h1>Статьи</h1>
{% for post in site.categories.articles %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
{% if post.image %}
  ![{{ post.title }} cover image]({{ post.image }}){: style="width: 800px; height: auto;"}
{% endif %}
  <p>{{ post.excerpt }}</p>
{% endfor %}
