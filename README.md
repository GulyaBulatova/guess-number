# Описание проекта
Игра "Угадай число" (guess-number).
Компьютер загадывает число в диапазоне от 1 до максимального числа, заданного в настройках. Игрок должен угадать это число за несколько попыток (максимальное количество попыток задано в настройках). После каждой попытки компьютер сообщает, было ли введенное числе больше или меньше загаданного.

* * *

* В программе реализованы три режима, которым соответствуют ключи:
    * `--new`. Новая игра.
    * `--list`. Вывод списка всех сохраненных игр.
    * `--list win`. Вывод списка всех игр, в которых победил человек.
    * `--list loose`. Вывод списка всех игр, в которых человек проиграл.
    * `--top`. Вывод статистики по игрокам.
    * `--replay id`. Повтор игры с идентификатором id.

* * *

## Требования

Минимальная версия PHP: 7.4.7 (Раскомментировать строки в `php.ini`: `extension=pdo_sqlite` и `extension=sqlite3`)\
Минимальная версия Composer: 1.9.3

* * *

## Инструкция по установке и запуску игры

Из Github:

1. Склонировать проект на локальную машину;
2. Установить composer, если он не установлен;
3. Перейти в корневой каталог;
4. Выполнить в консоли команду `composer update`;
5. Перейти в каталог bin из корнегого каталога и запустить файл guess-number.bat.

Из Packagist:

1. Установить composer, если он не установлен;
2. Перейти в каталог, в который вы будете клонировать проект;
3. Выполнить команду `composer require bulatova/guess-number`;
4. Перейти в каталог vendor/bin;
5. Запустить файл guess-number.bat.

* * *

## Ссылки

Packagist: <https://packagist.org/packages/bulatova/guess-number>