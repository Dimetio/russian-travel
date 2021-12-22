# Проект: Путешествие по России

**Проект выполнен по макету**
* [Ссылка на макет в Figma](https://www.figma.com/file/5S2WSbEFL6awjVWJ0NWL8Q/Sprint-3_-Russia-_-desktop-mobile?node-id=28503%3A0)

## Описание проекта:
Представляет собой одностраничный сайт, рассказывающий и позывающий небольшую поездку по городам России и красивый местам.

## Что было реализовано:
**Создана файловая структура по БЭМ (Nested):**
  * в файле каждого блока, элемента и модификатора описаны только стили, которые к ним относятся
  * директории с блоками не вложены в другие блоки
  * модификаторы содержат только те CSS-свойства, которые изменяются в элементах. Модифицируемый
элемент или блок не содержит изменяющееся в модификаторе CSS-свойство
  * не используется «повышение веса» селектора модификатора, такое как ```block-name.block-name_mod-name```
  * Отсутствуют классы с числовыми значениями, такие как <div class="block__first block__1">

**Доступность интерфейса:**
* Все ссылки и интерактивные элементы имеют состояние наведения ```:hover```
* Контентные изображения имеют ```alt``` с корректным описанием, которое соответствует языку страницы

**CSS:**
* Контент на странице отцентрован.
* Установлен серый фон ```#2A2C2F``` для всей страницы, нет белых полей по бокам.
Не используется ```!important```
Используется шрифт ```Inter```. Размеры, начертания и цвет шрифта как в макете.
* Для каждого шрифта указаны альтернативные варианты из системных шрифтов.
* Отсутствует горизонтальная прокрутка при изменении ширины окна
* Реализована адаптивная верстка через **media** запросы
``` css
  @media (max-width: 1024px) {

  }
```
* [Ссылка на github pages](https://dimetio.github.io/PR2/)
