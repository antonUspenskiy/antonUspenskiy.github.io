---
layout: default
title: Статьи
permalink: /articles/
---

<h1>Статьи</h1>
{% for article in site.articles %}
  <h2><a href="{{ article.url }}">{{ article.title }}</a></h2>
  {% if article.image %}
    <img src="{{ article.image }}" alt="{{ article.title }} изображение" style="width:200px; height:auto;">
  {% endif %}
  <p>{{ article.excerpt }}</p>
{% endfor %}
