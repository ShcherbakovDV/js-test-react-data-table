# js-test-react-data-table

## Постановка задачи

Первое что тебе
потребуется сделать - это прочесть, понять и сказать свою оценку времени выполнения задания :)
Суть задачи следующая: вывести в таблицу данные о ключевых словах.
url: /stats/

Данные брать POST: https://hq.asodesk.com/api/us/demo/keyword-analytics/data-stats

Первая колонка - чекбокс. Можно выделить несколько чекбоксов, нельзя убрать все
чекбоксы, хотя бы один всегда должен остаться.

Вторая - вывод поля keyword

Третья - кнопка перехода в другой инструмент, с передачей keyword как параметра. По клику на explore открывать страницу с url '/explore', ее оставить пустой

Четвертая - Открытие попапа, число у Show - вывод поля suggestions_count. Попап - реально открывать, можно оставить пустым.

Пятая и далее вывод соответствующих параметров (только для iphone): Traffic Score в JSON именуется как users_per_day, Total Apps так и называется, Rank это position_info.
Color - один из 6 цветов, соответствующих числам 0-5, цвета любые, в мокапе
предложенные.

Последняя - удаление строки. По клику строку удалять, состояние можно не хранить.
Стили в финальном результате не важны, но бонусом будет опрятный продуктовый
вид.

Захостить решение по своему усмотрению, можем дать выделенный сервер по
запросу. Доступ к исходнику предоставить обязательно.

Условия задачи можно обсуждать, я на связи по почте, скайпу, телефону.

Использовать ES5, ES6, TS по усмотрению. За TS отдельный бонусный балл.
Фреймворк - React, таблица - react-tables [желательно самый свежий], либо аналогичный модуль на выбор (выбор обосновать), важна функциональность пагинаций.
