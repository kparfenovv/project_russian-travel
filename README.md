# Путешествие по России

Адаптивный одностраничный сайт, созданный по макету Figma. Сайт адаптирован для просмотра на экранах различных устройств от 320 пикселей до широких экранов 1280 пикселей. При вёрстке использован подход Desktop First.

## Стек

- HTML
- CSS

## Функциональность

- Сетка на основе grid
- Выстраивание элементов блоков с помощью flexbox
- Media queries, адаптивность страницы для разных разрешений экрана
- Использование принципов БЭМ для организации селекторов и файлов CSS
- Использование псевдоэлементов
- Семантика страницы
- Анимации и трансформации
- Подключение шрифтов

## Планы по доработке

- Реализовать добавление элементов в DOM с помощью JavaScript и избавиться от дублирования кода в index.html
- Реализовать переключение языков с помощью JavaScript
- Сделать анимированный логотип в шапке страницы
- Добавить popup увеличенного просмотра фото с помощью JavaScript
- Сборка проекта посредством Webpack

На странице может возникать проблема длительной загрузки из-за большого количества импортов блоков, элементов и модификаторов в основном файле стилей "./pages/index.css". Хотя все изображения были оптимизированы, и для тегов img был добавлен атрибут loading со значением "lazy", чтобы загрузка картинок не замедляла загрузку страницы. Этот атрибут позволяет загружать изображения не сразу, а по мере прокрутки пользователем, что помогает смягчить негативное влияние множества импортов в "./pages/index.css".

## Ссылка https://kparfenovv.github.io/project_russian-travel/


# Project 3: Travel across Russia

This project is the final assignment from the third sprint of the "Web Developer" course by Yandex Practicum.

## Description

The project is an adaptive single-page website, developed from a Figma prototype. The site is optimized for viewing on screens of various devices, ranging from 320 pixels to wide screens of 1280 pixels, using the desktop-first approach.

## Stack

- HTML
- CSS

## Realization

The project uses the following techniques:

- Flexbox for element positioning
- Grid-layout for creating the website's grid
- Adaptive layout for screen sizes of 1280px, 1024px, 768px, 320px
- BEM Nested methodology for organizing CSS selectors
- CSS pseudoclasses for adding styles to elements

## Future Improvements

There are plans for further improving the project:

- Implement JavaScript to add elements to the DOM and remove duplicated markup
- Add a language switcher for better user experience
- Create an animated logo in the page header
- Add a photo popup for enlarged viewing using JavaScript
- Optimize the project's build process with Webpack

## URL

[Link to the project](https://kparfenovv.github.io/project_russian-travel/)


