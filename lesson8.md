# <a href="http://java.u-rise.com/">U-Rise. Онлайн Курс по Java SE</a>.
# Восьмое занятие

## Разбор Домашнего Задания-7: объектная модель резюме

## Работа с датами и временем
- <a href="http://www.intuit.ru/studies/courses/16/16/lecture/27131?page=1">Класс Date, Calendar, TimeZone</a>
- <a href="https://github.com/winterbe/java8-tutorial#date-api">Java 8 Date API</a>

## Работа с файлами. Ввод/вывод
 - <a href="http://www.intuit.ru/studies/courses/16/16/lecture/27133">Пакет java.io</a>
 - <a href="http://ru.wikipedia.org/wiki/Декоратор_(шаблон_проектирования)">Паттерн Декоратор</a>.
 - <a href="http://www.intuit.ru/studies/courses/16/16/lecture/27133?page=4">Классы Reader и Writer.</a>
 - Реализация `Storage` используя `DataInputStream/DataOutputStream`.

## Домашнее задание
- Переделать модель резюме: учесть, что на одной работе (в одном учебном заведении) можно работать/ учиться в разные периоды и при этом имя организации не дублируется
- Заполнить в `AbstractStorageTest` резюме данными и дополнить в Resume `equals/hashCode`
- Выделить `AbstractFileStorage` и реализовать `DataStreamStorage.doCopyAll()` и `size()`
