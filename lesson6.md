# <a href="http://java.u-rise.com/">U-Rise. Онлайн Курс по Java SE</a>.
# Пятое занятие

## Разбор Домашнего Задания-5

## Вложенные, внутренние, локальные и анонимные классы. Iterable
- <a href="http://www.javenue.info/post/101">Iterator / Iterable</a>. Устаревшие коллекции Vector, Stack.
- <a href="http://easy-code.ru/lesson/java-nested-classes">Вложенные и внутренние классы</a>. Примеры в Collections API: Arrays.asList, Map.Entry, LinkedList.Node, Collections, Iterator
- <a href="http://easy-code.ru/lesson/local-anonymous-nested-classes-java">Локальные и анонимные классы.</a>
- Comparator.

## Новое в Java 8.
- <a href="http://devcolibri.com/4137#t2">Default методы для Interface. Lambda выражения. </a>
- <a href="http://devcolibri.com/4274#t9">Встроенные функциональные интерфейсы. Date API</a>

## Параметризация. Стирание типов.
- <a href="http://developer.alexanderklimov.ru/android/java/generic.php">Обобщения (Generic)</a>
- <a href="http://www.quizful.net/post/java-generics-tutorial">Дженерики (Java, обучающая статья)</a>
- <a href="http://docs.oracle.com/javase/tutorial/java/generics/restrictions.html">Ограничения.</a>

## Enum
- <a href="http://easy-code.ru/lesson/enum-types-java">Перечисляемые типы (enum) в Java</a>

## Домашнее задание: сделать объектную модель резюме (диаграмма и классы).

- Образец резюме (делаем упрощенно):
  - Делать только классы, включаемые в Resume.
  - Схожие по структуре и функциональности сущности делаем одним классом.
  - Модель упрощаем для хранения только необходимой информации для вывода/ редактирования резюме.
  - Resume - главный класс. В него все включается (композиция - строгий вид агрегации).
  - В модели резюме должны быть представлены контакты и следующие разделы:
    - PERSONAL("Личные качества")
    - OBJECTIVE("Позиция")
    - ACHIEVEMENT("Достижения")
    - QUALIFICATIONS("Квалификация")
    - EXPERIENCE("Опыт работы")
    - EDUCATION("Образование")
  - В секциях Достижения и Квалификация хранить список строк
  - Учесть в классах модели, что обработка резюме (вывод в html, сохранение, чтение) будет сделано следующим образом:
обработка специальных полей (`fullName` нарпимер), цикл обработки по контактам, цикл обработки по секциям (т.е. использовать полиморфизм, как для фигур круг, квадрат..).
При добавлении/удалении новых видов контактов (например домашний телефон) или разделов изменения в коде (и БД) должны быть минимальны.

#### Инструменты для рисования:

- <a href="http://stackoverflow.com/questions/8942751/use-intellij-to-generate-class-diagram#26926334">Generate class diagram in IntelliJ IDEA</a> (<a href="https://www.jetbrains.com/help/idea/2016.1/working-with-diagrams.html?origin=old_help">Help: working with Diagrams</a>)
- Нарисовать и сфотографировать
- <a href="http://www.draw.io">Online: www.draw.io</a>
- <a href="https://www.yworks.com/">yEd - Graph Editor</a>