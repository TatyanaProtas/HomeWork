[Урок 1. Веб-технологии: вчера, сегодня, завтра](#урок-1-веб-технологии-вчера-сегодня-завтра)

[Урок 2. HTML, CSS](#урок-2-html-css)

[Урок 3. Основы JavaScript](#урок-3-основы-javascript)

[Урок 4.Основы бэкенда: PHP и MySQL](#урок-4основы-бэкенда-php-и-mysql)



# Урок 1. Веб-технологии: вчера, сегодня, завтра

1. Определите, на каком протоколе работает сайт youtube.com.
Сделайте скриншот с названием 1_protocol.jpg, по которому станет понятно, как вы определили протокол сайта.

<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/1_protocol.jpg?raw=true"/></kbd>
<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/2_protocol.jpg?raw=true"/></kbd>
_____

2. Создайте файл 2_analyze.txt, в котором проанализируйте структуру страницы сайта https://ru.wikipedia.org/ (опишите коротко, своими словами), а именно:
- Есть ли шапка сайта.

- Есть ли подвал сайта.

- Как и где расположен контент.

- Есть ли дополнительные элементы на странице.

[текстовый файл](https://github.com/TatyanaProtas/HomeWork/blob/main/2_analyze.txt)

____
3. Внесите не менее 10 изменений на страницу любой статьи сайта https://ru.wikipedia.org/, с помощью инструмента разработчика и представьте два скриншота было/стало. 

<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/3_before.jpg?raw=true"/></kbd>
<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/3_after.jpg?raw=true"/></kbd>

______

4. Создайте прототип низкой детализации сайта https://dzen.ru/ с помощью сайта https://wireframe.cc/. Предоставьте скриншот того, что получилось.
<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/4_proto.jpg?raw=true"/></kbd>


_____


# Урок 2. HTML, CSS
Формат сдачи ДЗ - один архив, со всеми файлами и скриншотами, либо pull request на github.

Создать сайт (html-документ с названием index.html), с рассказом о чём угодно. Например, о себе или о любимом коте.
Страница должна содержать как минимум:
1. Два заголовка.
2. Два абзаца (параграфа).
3. Одну картинку из интернета, которая находится в свободном доступе, то есть которая будет доступна без регстранции и смс ;) 
4. Одну картинку, которая будет браться локально. Все локальные картинки должны храниться в папке img, которая должна лежать рядом с html-документом.
5. Один нумерованный список со значениями.
6. Один маркированный список со значениями.
7. Одну ссылку.
8. Один локальный, подключенный css-файл, в котором прописаны пара стилей, применяемых на странице.

Примечание:
html-документ не должен содержать ошибок при проверке в https://validator.w3.org/#validate_by_input


_____
# Урок 3. Основы JavaScript


1. Необходимо пользователя попросить ввести температуру в градусах Цельсия, преобразовать введенное пользователем значение в соответствующую температуру в градусах по Фаренгейту и вывести в alert сообщение с текстом (пример): Цельсий: 21, Фаренгейт: 69.8 Советую округлить значение после рассчетов, так как в некоторых случаях может получиться "длинная дробь".

[решение](https://github.com/TatyanaProtas/HomeWork/blob/main/Урок%203/1.js)
<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/Урок%203/температура.png?raw=true"/></kbd>
<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/Урок%203/результат.png?raw=true"/></kbd>
___

2. Cоздать функцию greeting, которая принимает имя и выводит приветствие, используя переданное имя, в консоль. Необходимо у пользователя запросить имя и вызвать функцию greeting, передав туда данное значение.

[решение](https://github.com/TatyanaProtas/HomeWork/blob/main/Урок%203/2.js)
<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/Урок%203/имя.png?raw=true"/></kbd>
<kbd><img src="https://github.com/TatyanaProtas/HomeWork/blob/main/Урок%203/приветИмя.png?raw=true"/></kbd>
___

# Урок 4.Основы бэкенда: PHP и MySQL

1. На основе верстки из html-документа https://disk.yandex.ru/d/H9_wDMSChowFVg, необходимо создать php-файл с названием index.php и вставить в этот сайт все что есть в html-документе.

Необходимо создать массив в самом верху php-файла, в котором будет описываться опыт работы (правая верхняя часть сайта). Необходимо вставить из массива данные на странице, а именно, название работ, дату и описание для каждой работы.


Если хотите усложнить себе задание, то можете попробовать вывести с помощью цикла эти данные.


Примечание: файлы .php не стоит пробовать открывать как обычные html-файлы в браузере, браузеры не умеют выполнять php-код, для этого нужен интерпретатор (специальная программа, которая разбирает и выполняет код), если вы его не устанавливали себе на компьютер, то можете воспользоваться сайтом https://www.w3schools.com/php/phptryit.asp?filename=tryphp_compiler

Примечание №2: в песочнице php, на сайте https://www.w3schools.com/php/phptryit.asp?filename=tryphp_compiler, есть ограничение по количеству символов/строк, в случае если превысить лимит, то будет сгенерирован, в результате, пустой лист.


2. Создать файл my.sql, в котором должна создаваться таблица с информацией об одногруппниках. В таблице должно быть четыре поля: id, name, age, address. Все поля в таблице обязательны для заполнения.
Необходимо добавить 5-10 одногруппников в данную таблицу.

Необходимо написать запрос на получение имен всех одногруппников (только имен, без всего остального), которые живут в Москве и их возраст находится в диапазоне [18, 30) лет.

Примечание:

Квадратные скобки при указании диапазона, означают "включительно", а круглые "не включительно", то есть диапазон (7, 9] означает "от 7, где 7 не попадает в данный диапазон, до 9 включительно". Такой синтаксис нельзя использовать в sql, вам нужно найти решение, как такое условие можно записать в sql по-другому.

[решение](https://github.com/TatyanaProtas/HomeWork/blob/main/Урок%204/index.html)