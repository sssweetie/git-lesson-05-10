# git-lesson-05-10

Hello world 
**ПАМЯТКА ПО КОМАНДАМ**

git config --global uzer.name 'Ivan Ivanov' создать имя в Гите

git config --global uzer.email 'ivan@mail.ru' создать почту в Гите

git config user.name просмотр имени

git config user.email просмотр почты

new-item readme.md создать фаил readme.md

git init - Инициализация репозитория

git status - Статус репозитории

git add readme.md - добавить версионость файлу readme.md

git reset readme.md - добавить версионость файлу readme.md

git add . - добавить версионность всем файлам в папке

git reset . - удалить версионность всем файлам в папке

cd.. вернуться на папку назад
сd имя папки переместиться в папку

git commit -m "init commit" - сохранить

git commit -m "commit_message" - сохранить

git commit -am "second commit" сохранить без добавления версионности

git log - посмотреть изменения, выйти из логирования Q с англ раскладкой

git branch - Посмотреть какие есть ветки

git checkout и 4 цифр комита, чтоб откатиться

git checkout (имя ветки master) чтоб перейти на ветку мастер

git checkout -b feat/new-(имя ветки)- создать новую ветку находясь в комите к примеру мастера (откатить)

git diff - отображает последние изменения

mkdir название папки, создать папку

ls посмотреть все файлы в папке в которой находишься

git branch user1 создать ветку user1

git branch -d user1_name удалить ветку user1_name

git merge branch - слить в текушую ветку изменения из branch

git branch -d имя ветки удалить  слитую ветку

git branch -D имя ветки удалить еще не слитую ветку

git merge user1 сделать сравнение с user 1

git clone "ссылка" создать репозиторий на основе удаленого

git clone "ссылка" пробел "Название папки" создать депозиторий в этой папке

git commit -am "любое название" комит

git push - загрузить в облако

git pull - загрузить с облака

fork - Переходим по сылке на чужой репозиторий, чтоб склонировать