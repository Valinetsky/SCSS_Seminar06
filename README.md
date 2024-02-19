# Урок 6

1. Создать мобильную версию для всех 5 страниц интернет-магазина
2. Проверить работу сайта на разрешении 375px
3. Проверить работу сайта на разрешении 425 px
4. Проверить сайта на валидность

## Замечания

Ссылка на макет страницы:
https://www.figma.com/file/TQaPa1gzsX6Qb4Gqj4fve7/Shop-(Copy)?type=design&node-id=0-1&mode=design&t=jRXMmNm04xKXBoxX-0

Ссылка на предыдущий семинар с исходным кодом и скриншотами на разных разрешениях:
https://github.com/Valinetsky/SCSS_Seminar05/

Ссылка на github pages текушего проекта:
https://valinetsky.github.io/SCSS_Seminar06/

Ссылка на сайт-валидатор:
https://validator.w3.org

## Ошибки валидации

В файлах catalog.html и product.html была ошибка "тег summary не может содержать элемент…".

Пример ошибки валидации из файла catalog.html:

Error: Element p not allowed as child of element summary in this context. (Suppressing further errors from this subtree.)

From line 146, column 29; to line 146, column 55

    <p class="menu__text_bold">FILTER

Contexts in which element p may be used:
Where flow content is expected.
Content model for element summary:
Phrasing content, optionally intermixed with heading content.

---

Файл product.html — исправлен (устранены ошибки валидации).

В файле catalog.html ошибка валидации не устранена из-за особенностей меню FILTER. На отображение страницы в браузере Chrome в различных разрешениях — влияния ошибки не выявлено. Однако неприятно.
