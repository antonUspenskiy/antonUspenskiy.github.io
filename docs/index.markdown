---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Главная страница
permalink: /
---
<link rel="stylesheet" href="{{ '/assets/style.css' | relative_url }}">
<div class="button-container">
    <a href="/articles/" class="button" style="background-image: url('{{ 'https://antonuspenskiy.github.io/assets/cover-1920.jpg' | relative_url }}');">
        <h2 style="color: white; text-decoration: none;">Статьи</h2>
    </a>
    <a href="/reports/" class="button" style="background-image: url('{{ 'https://antonuspenskiy.github.io/assets/cover-1920.jpg' | relative_url }}');">
        <h2 style="color: white; text-decoration: none;">Отчеты</h2>
    </a>
    <a href="/other/" class="button" style="background-image: url('{{ 'https://antonuspenskiy.github.io/assets/cover-1920.jpg' | relative_url }}');">
        <h2 style="color: white; text-decoration: none;">Другое</h2>
    </a>
</div>
