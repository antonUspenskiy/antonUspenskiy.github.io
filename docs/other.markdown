---
layout: default
title: "Другое" 
permalink: /other/
---
{% for post in site.other %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>{{ post.excerpt }}</p>
{% endfor %}
