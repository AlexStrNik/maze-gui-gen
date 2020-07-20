# maze-gui-gen

**А вы сможете создать упражнение для Трик Студио за 30 секунд?**

Я создал кроссплатформенное приложение, которое может помочь учителям и ученикам, которые работают с симулятором Трик Студио, сгенерировать поля программно, вместо того, чтобы вручную изменять (.xml) файл.

**Что для этого нужно?**

1. Скачиваете программу
1. Создаете карту с размером, который вам нужен (Инструменты - Создать карту)
1. Самостоятельно выбираете куда поставить "стенки" или генерируете рандомно (Инструменты - Случайно расставить стенки)
1. Нажимаете один раз на любую клетку, чтобы сделать её стартовой, дважды, чтобы указать на финиш.
1. Чтобы сохранить карту с лабиринтом выбираете (Инструменты - Экспортировать поле с лабиринтом), для лабиринта в виде линий (Инструменты - Экспортировать поле с линиями)
1. Открываете Трик Студио и загружаете свою модель мира.
1. Круто, теперь вы создали упражнение.


**Подробнее о возможностях программы.**

1. Для удобства можно увеличивать и уменьшать размер карты колёсиком мыши или (Ctrl + Plus, Ctrl + Minus).
1. Если у вас большая карта, то можно перемещаться по ней, перетаскивая мышкой, чтобы минимизировать задержки при отрисовке, максимальный размер карты - 2000 ячеек.
1. Количество стартовых и финишных зон не ограничено, каждая из них будет функционировать
![ru 1](/source/app_screenshots/out_ru_1.png)
1. Вы можете также экспортировать матрицу смежности, чтобы вставить её в свою программу и продолжить изучение теории графов (Инструменты - Экспортировать матрицы смежностей)

**Более гибкая генерация полей и дополнительные настройки.**

1. В окне настроек можно выбрать размер одной ячейки для лабиринта со стенками и с линиями отдельно (система измерения - ячейка Трик Студио)
1. Для лабиринта с линиями в настройках можно отдельно выбирать цвет линии, по умолчанию - чёрный.
1. Ограничение по времени выполнения тоже можно отдельно настроить (первое число - минуты, второе - секунды)
![ru 3](/source/app_screenshots/out_ru_3.png)

