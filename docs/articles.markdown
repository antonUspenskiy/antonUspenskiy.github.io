---
layout: default
title: "Статьи"
permalink: /articles/
---
<h1>Статьи</h1>
{% for article in site.articles %}
  <h2><a href="{{ article.url | prepend: site.baseurl }}">{{ article.title }}</a></h2>
  <p>{{ article.excerpt }}</p>
{% endfor %}
