---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Главная страница
permalink: /
---
<link rel="stylesheet" href="{{ '/assets/style.css' | relative_url }}">
<div class="button-container">
    <div class="button" style="background-image: url('{{ '/assets/image1.jpg' | relative_url }}');">
        <a href="/articles/" style="color: white; text-decoration: none;">Статьи</a>
    </div>
    <div class="button" style="background-image: url('{{ '/assets/image2.jpg' | relative_url }}');">
        <a href="/reports/" style="color: white; text-decoration: none;">Отчеты</a>
    </div>
    <div class="button" style="background-image: url('{{ '/assets/image3.jpg' | relative_url }}');">
        <a href="/other/" style="color: white; text-decoration: none;">Другое</a>
    </div>
</div>
