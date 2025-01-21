---
layout: default
title: Статьи
permalink: /articles/
---

<link rel="stylesheet" href="https://antonuspenskiy.github.io/assets/style.css">

<div class="blocks-container">

<div class="articles-page">
  <h1>Статьи</h1>
  {% for post in site.categories.articles %}
    <div class="post-block">
      <h2 class="post-title">
        <a href="{{ post.url }}">{{ post.title }}</a>
      </h2>
      {% if post.image %}
        <img src="{{ post.image }}" alt="{{ post.title }} cover image" class="post-cover">
      {% endif %}
      <p class="post-excerpt">{{ post.excerpt }}</p>
      <a href="{{ post.url }}" class="read-more-btn">Читать далее</a>
    </div>
  {% endfor %}
</div>

</div>
