# Проектная работа: "Куда я поеду".

## Создана в рамках учебы в [Яндекс.Практикум](https://praktikum.yandex.ru/) на курсе ["Веб-разработчик"](https://praktikum.yandex.ru/web/).


## Описание:


Тестовый проект на знание технологий веб-разработки. 
Рассказываем о интересных местах для путешествий по России. 
Проект полностью адаптивный и подстраивается под любое разрешение экрана устройства.
Проект выполнял совместо с [Андреем Рогалевичем](https://github.com/Andrei199729)
Все изоброжения оптимизированны на [сайте доброй панды](https://tinypng.com).

[Посмотреть на GitHub Pages](https://sevamarkov88.github.io/Test-project/)


## Технологии:
![HTML](https://img.shields.io/badge/-HTML-05122A?style=flat&logo=HTML5)&nbsp;
![CSS](https://img.shields.io/badge/-CSS-05122A?style=flat&logo=CSS3&logoColor=1572B6)&nbsp;
![Git](https://img.shields.io/badge/-Git-05122A?style=flat&logo=git)&nbsp;
![GitHub](https://img.shields.io/badge/-GitHub-05122A?style=flat&logo=github)&nbsp;
![Visual Studio Code](https://img.shields.io/badge/-Visual%20Studio%20Code-05122A?style=flat&logo=visual-studio-code&logoColor=007ACC)&nbsp;

1. Grid Layout
```css
.place {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  grid-template-rows: 575px;
}
```
2. Медиазапросы
```css
@media (max-width: 1000px) {
  .place {
    grid-template-rows: 1fr;
  }
}
```
## Инструкция по установке:

Клонировать репозиторий:

`
git clone https://github.com/SevaMarkov88/Test-project.git
`
