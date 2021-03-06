# Intecmedia HTML Reset

Это внутри-корпаративный стандарт/шаблон для верстки сайтов компании Интекмедиа.

License: Public Domain

## Особености:

* сбрасывает стандартные стили браузера
* совсместимо со всеми современны браузерами (для IE6 используются фиксы)
* готово к использованию HTML5 разметки
* содержит базовую типографику текста, форм, таблиц, списков, заголовков

## Стилистика кода

### CSS

* отсупы в два пробела
* каждый селектор на отлдельной строке
* открывающя скобка на одной строке с слектором
* закрывающая скобка на отедельной строке после атрибутов стилей
* крупные блоки заключаются в открывающий и закрывающий комментарий

#### пример

```css
/* block */
.block {
  font-size:14px;  
  width:100px;  
}
.block .block-inner {
  color:#0000FF;
  border:1px solid #FF0000;
}
/* /block */
```

### HTML

* отсупы в два пробела
* атрибуты заключены в двойные ковычки
* все блочные теги на отедельной строке
* крупные блоки заключаются в открывающий и закрывающий комментарий

#### пример

```html
<!-- block -->
<div class="block">
  Inline <a href="#">text</a> on one line.
  <div class="block-inner">
    Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
  </div>
</div>
<!-- /block -->
```

## Именования классов и переменных
* ...

## Стандарты размещения файлов
* ...

## Лицензиции

### Major components:
* jQuery: MIT/GPL license
* Normalize.css: Public Domain
* HTML5 Shiv: MIT/GPL2 Licensed