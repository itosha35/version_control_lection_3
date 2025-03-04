# Инструкция по написанию текстов в MrakDown

## Выделение текстов

В MarkDown есть несколько различных способов выделить текст. 

Например, Вы можете обрамить слово (или кусок текста) звездочками (*) или нижним подчеркиванием (_) и тогда он будет написан курсивом - *вот так* или _вот так_.

Также вы можете выделить текст полужирным шрифтом, для этого необходимо обрамить текст двойными звездочками (**) или двойными подчеркиванием (__) - **полужирный текст** или __полужирный текст__.

Мы можем комбинировать разные способы выделения полужирным и курсивом. Например, вот так - _Курсивный и одновременно **полужирный текст**_.

## Работа со списками

Списки выбают нумерованными и ненумерованными. Если нам нужен нумерованный список, то мы просто пишем каждый элемент со своим номером на новой строке, а MarkDown сам его красиво оформит. Например, вот так:
1. первый элемент
2. второй элемент
3. третий элемент

Если нам нужны ненумерованные списки, то мы вместо числа (номера элемента) можем поставить +. Например, вот так:
+ Элемент
+ Элемент

## Картинки в тексте

Чтобы добавить картинку в текст необходимо использовать следующий синтаксис - ставим восклицательный знак, потом в квадратных скобках указываем текст, а в круглых - адрес файла с картинкой. Адрес относительный или абсолютный. Например, вот так:
![Это Тефтелька](Teftelka.jpg)

## Ссылки в текста

Ссылка на [GitHub](https://github.com/)

## Таблицы

## Заголовки
Заголовки пишем через #

## Заключение

## Работа с удаленными репозиториями

**Список команд** для работы с удаленными репозиториями:
* git branch -M main (или как угодно мы хотим)
* git remote add origin (URL paste here)
* **git push** - отправить локальные изменения на сервер в GitHub
* **git add** - получить/скачать информацию с удаленного репозитория на GitHub

Далее еще пару полезных комманд:
* _git remote show origin_ - показать к чему привязан origin (URL)
* _git commit -a_ - сразу закоммитить без git add, данная комана относится просто к git'у

