**git init** - Инициализация репозитория

**git add "file_name**  - добавить указанному файлу версионность

**git reset** "file_name" - удалить у указанного файла версионность

**git add .** - добавить всем файлам версионность

**git reset .** - убрать всем файлам версионность 

**git commit -m "commit_messge"** - упрощенный вариаент коммита

**git commit** -обычный вариант коммита

**git commit -am**- Если файл имеет состояние modified (т.е. был tracked и мы его добавили с помощью git add), то можно проаустить этап с командой git add посредством использования данной команды

**git checkout "hash_number"** -Переместить на коммит с хэшем "hash_number" (для того, чтобы вернуться git checkout master/main)

**git diff** - последнее изменение (начиная от коммита)

![Тут должен быть лес](forest.jpg)

**git branch** - показывает список веток

<https://gist.github.com/Jekins/2bf2d0638163f1294637> - руководство по оформлению Markdown файлов

**git clone [ссылка на удалённый репозиторий]**  - копирование удаленного репозитория 

**git pull**  - Подтягивает в локальный репозиторий последнюю версию проект

**git push** -Отправляет все зафиксированные изменения с локального репозитория в удалённый