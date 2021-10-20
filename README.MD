# Проект: Куда я поеду?

### Обзор

* Интро
* Технологии

---

**Интро**

Тестовый проект на знание технологий веб-разработки от [ЯндексПрактикум](https://practicum.yandex.ru)
Проект выполнял совместо с [Андреем Рогалевичем](https://github.com/Andrei199729)
Все изоброжения оптимизированны на [сайте доброй панды](https://tinypng.com).

И конечно [ссылка на GitPages](https://sevamarkov88.github.io/Test-project/)


**Технологии**

1. Немного гридов
```css
.place {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
  grid-template-rows: 575px;
}
```
2. И чуть-чуть медиазапросов
```css
@media (max-width: 1000px) {
  .place {
    grid-template-rows: 1fr;
  }
}
```
