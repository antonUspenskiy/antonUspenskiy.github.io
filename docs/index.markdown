---
layout: default
title: Главная страница
permalink: /
---

<link rel="stylesheet" href="https://antonuspenskiy.github.io/assets/style.css">

<!-- Верхний блок с информацией -->
<div class="intro-section" style="display: flex; align-items: center; margin-bottom: 40px;">
    <!-- Левая колонка -->
    <div class="intro-text" style="background-color: #2c3e50; color: white; padding: 40px; width: 33%; text-align: center;">
        <h1 style="margin-bottom: 20px;">Антон Успенский</h1>
        <p style="margin-bottom: 40px; font-size: 18px;">Технический писатель, автор статей</p>
        <a href="/CV/" class="print-button" style="display: inline-block; background-color: #3498db; color: white; padding: 10px 20px; text-decoration: none; border-radius: 5px;">Распечатать резюме</a>
    </div>
    <!-- Правая колонка (фотография) -->
    <div class="intro-image" style="width: 67%;">
        <img src="https://antonuspenskiy.github.io/assets/index/Main.jpg" alt="Антон Успенский" style="width: 100%; height: auto; object-fit: cover;">
    </div>
</div>

<!-- Приветственный текст -->
<div class="welcome-text" style="margin-bottom: 40px;">
    <p>Добро пожаловать на мой сайт! Здесь вы найдете примеры моих работ, статей и технических проектов. </p>
    <p>Пожалуйста, ознакомьтесь с моим портфолио ниже.</p>
</div>

<!-- Кнопки для перехода -->
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
