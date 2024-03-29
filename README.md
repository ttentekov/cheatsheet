# Cheatsheet
## Основы командной строки
**man** - Документация команд.

**pwd** - Показывает текущую папку.

**ls** - Выводит список файлов текущей папки. Добавив флаг **-a** покажет скрытые файлы, **-l** доп. информацию.

**cd** - Перемещение по папкам. "**cd ..**" вернет в предыдущую папку.

**cat** - Выводит в консоль содержимое файла.

**touch** - Создает файл.

**mkdir** - Создает папку.

**rm, rmdir** - Удаляет файл, папку.

**&&** - Выполнение команд одну за другой.

## Работа с git

**git clone <rep. link>** - Клонирует указанный репозиторий.

**git branch + <branch name>** - Посмотреть, какие в проекте есть ветки и в какой из них вы сейчас находитесь.

**git checkout <branch name>** - Позволяет переключаться на другую ветку. Флаг "**-b**" создаст новую ветку и сразу перейдет на неё.

**git init** - Создает локальный репозиторий.

**git add** - Указывает какие файлы надо сохранить.

**git  commit** - Сохраняет указанные файлы. Флаг "**-m**" Добавить комментарий, "**--amed**" Изменение последнего коммита, "**--no-edit**" Дополнит последний коммит новым файлом.

**git log** - Выводит в консоль историю коммитов. Флаг "**--oneline**" упрощенная версия.

**git push** - Отправляет изменения на удаленный репозиторий.

**git status** - Выводит в консоль состояние файлов.

**git restore** - Откатит указанный файл до последнего коммита. Флаг "**--staged**" Вернет указанный файл в untracked/modified.

**git reset** - Флаг "**--hard <commit hash>**" Откатит коммит до указаного хэша.

**git diff** - Узнать изменение до и после (+хэш1 и хэш2). Флаг "**--staged**" сравнивает в "списках на коммит". Git есть суффикс навигации ~N, где N — это число коммита.

**git merge <name branch>** - Соединяет ветку с текущей.

## Ссылки

[Шпаргалка по Markdown](https://gist.github.com/fomvasss/8dd8cd7f88c67a4e3727f9d39224a84c)

## Картинки

#### Жизненный цикл файла в Git

![](https://pictures.s3.yandex.net/resources/M2_T5_1686651284.png)

#### Процесс «отката» с помощью git reset --hard <hash>

![](https://pictures.s3.yandex.net/resources/M2_T6_1686651127.png)