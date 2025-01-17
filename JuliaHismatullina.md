# Инструкция по работе с Git

 ## Основные команды в Git:

 * **git init** - создать репозиторий;
 * **git add имя_файла.расширение** - добавить файл для отслеживания изменений;
 * **git status** - проверить изменения в текущем файле;
 * **git commit -m "Описание изменений"** - подтвердить изменения в файле, создать версию файла;
 * **git log** - журнал версий файла;
 * **git checkout XXXX** - загрузить выбранную версию файла, где ХХХХ - первые четыре символа коммита;
 * **git diff** - разница между текущим сохранённым (Ctrl + S) файлом и последней закоммиченной версией.

Для того, чтобы объединить команды *git add* и *git commit*, можно использовать команду **git commit -a -m "Описание изменений"**.

**Важно!** Не забывать сохранять изменения в файле с помощью *Ctrl + S*.

## Функции для работы с ветками в Git:

* **git branch** - отобразить существующие ветки;
* **git branch имя_ветки** - создать новую ветку;
* **git branch -d** - удалить ветку;
* **git checkout имя_ветки** - перейти на другую ветку;
* **git merge имя_ветки** - слить ветку *имя_ветки* в текущую ветку.

__Важно!__ _Merge_ вызывается оттуда, __куда__ вы хотите добавить изменения.

## Работа с удалёнными репозиториями с помощью GitHub

Основные функции при работе с удалёнными репозиториями:

* __git clone ссылка__ - склонировать внешний репозиторий на наш ПК;
* __git pull__ - скачать всё из текущего удалёнонго репозитория и автоматически _merge_ с нашей версией;
* __git push__ - отправить нашу версию репозитория на удалённый репозиторий. __Требует авторизации__ на удалённом репозитории.

Как сделать __Pull Request__:

1. Сделать _Fork_ репозитория.
2. Сделать _clone_ своей версии репозитория.
3. Создать новую ветку и в неё вносить свои измнения.
4. Фиксировать изменения (делать коммиты).
5. Отправить свою версию в свой репозиторий на GitHub.
6. На сайте GitHub нажать кнопку _Pull Request_.
