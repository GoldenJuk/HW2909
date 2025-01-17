# Инструкция для работы с Markdown

## Выделение текста

Чтобы выделить текст курсивом, необходимо обрамить его звездочкой (*) или знаком нижнего подчеркивания (_). 
Например, *вот так* или _вот так_.

Чтобы выделить текст полужирным, необходимо обрамить его двумя звездочками (**) или двойным знаком нижнего подчеркивания (__).
Например, **вот так** или __вот так__.

Альтернативные способы выделения текста жирным и курсивом  нужны для того, чтобы мы могли совмещать оба этих способа.
Например, _текст может быть выделен курсивом и при этом быть **полужирным**_.

## Списки

Чтобы добавить ненумерованные списки, необходимо пункты выделить звездочкой (*) или знаком (+).
Например, вот так:
* Элемент 1
* Элемент 2
* Элемент 3
+ Элемент 4

Чтобы добавить нумерованные списки, необходимо пункты просто пронумеровать.
Например, вот так:
1. Первый пункт
2. Второй пункт

## Работа с изображениями

Чтобы вставить изображение в текст, достаточно написать следующее:
![Привет, это Тефтелька!](Teftelka.png) 

## Ссылки
Чтобы сделать ссылку, необходимо текст ссылки заключить в квадратные скобки [], а адрес страницы в круглые скобки ().
Например, вот так:
[Руководство по оформлению Markdown файлов] https://gist.github.com/Jekins/2bf2d0638163f1294637

## Работа с таблицами
Обязательно требуют заголовок и настройки выравнивания (второй строкой). Выравнивание задаётся двоеточием. Колонки задаются вертикальным палками (|).
Например, вот так:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

Внешние вертикальные палки (|) задавать необязательно, также не требуется подгонять колонки под один размер. Можно использовать стили, описанные выше.
Например:

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3

## Цитаты

> Цитаты задаются угловой скобкой.
> Это строка является частью цитаты.

Здесь цитата прерывается.

> Можно писать много-много текста, и он автоматически всё преобразует в одну цитату. Также можно использовать различные *начертания* в **цитате**. Красота!
