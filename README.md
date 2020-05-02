# free-from-worries-loader

## Description (Описание)

(en) A loader, that is free from worries.
An author of original meme is Konstantin Brilevsky ([vk: brilevsky](https://vk.com/brilevsky)). I just brought it to life.
<br/>(ru) Лоадер, свободный от забот.
Автор оригинальной иллюстрации Константин Брилевский ([vk: brilevsky](https://vk.com/brilevsky)). Я же просто оживил его.

## [PREVIEW (ПРИМЕР)](https://codepen.io/holyslippers/pen/JLyOWG)

## Installation (Установка)

* NPM

  ```bash
  npm install free-from-worries-loader
  ```

## Usage (Использование)

1. Include the stylesheet in the document `<head>` (Добавьте стили в заголовок страницы).

  ```html
  <link rel="stylesheet" href="free-from-worries-loader.min.css">
  ```

2. Add a loader to the document body (Вставьте в страницу следующий фрагмент).

  ```html
  <div class="lazy-loader">
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
    <div class="lazy-stick"></div>
  </div>
  ```
3. If you need larger loader add class "lazy-loader_large" to lazy-loader wrapper (Если нужен лоадер большего размера добавьте класс "lazy-loader_large" к обертке лоадера).
