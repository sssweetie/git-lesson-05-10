# git-lesson-05-10

Hello world 

# Основные команды Git! #

**git init** - Инициализация репозитория
фыв момеванта последнего комита. Что попадет в следующий коммит.
фы
**git add "file_name"** - добавить файлу с названием "file name" версионность
ыва
**git reset "file_name"** - удалить у файла версионность
asdfasdfasdfasdfasdf
**git add .** - добавить все файлы в папке в версиаонирование
фываф
**git reset .** - отменить версионность у папкифы
**git commit -m "Сообщение к коммиту"** - упрощгшб юенный варинль
ывавагшен(без предварительного add)
афы
**git log** - вывести список коммитов в иерархическом порядке (снизу первый, сверху последний)ваб 
аманды add.

**git branch** - работа с ветками.г ьброк5гпр Просмотр существогь 
**git branch "name_branch"** - сонздание веткasdfasdfasdfasdfasdfasdfasdfиа
**git merge "name_branch"** - добавление в текущую ветку измененийфыв изафывафыва ветки "name_branch".

**git branch -d "name_branch"*6нр* - удаление ветки дбгшame_branch".
фыдбгшдбгшюгоздать ветку и переместваиться в нее.
фываasdfasdfasdf
**.gitignore** - этот файл в репозитории позволяет указывать на те файлы, которые гиту нужно игнорировать (не индексировать и т.д.)

**git reset --hard HEAD~3** - опасная команда, которая отменяет последние три коммита.

**git clone "путь к репозиторию"** - клонирование репозитория с гитхаба. Папка, в которую клонируем репозиторий не должна иметь длинный путь, иначе будет ошибка fatal: '$GIT_DIR' too big

### Выгрузка репозитория в гитхаб:
* **git remote add origin https://github.com/casperito87/test.git** - связать локальный и удаленный репозиторий
* **git branch -M main** - установить основной ветку main
* **git push -u origin main** - выгрузить репозиторий в сервис Git (гит дает подсказки)

* После первичной связи локального и удаленного репозитория достаточно просто использовать команду git push.

**git pull** - актуализировать изменений из гитхаба. Скачивание из гитхаба. Команда составная и поэтому будет merge.

### Запомнить!
1. Создаем аккаунт в ГитХаб.
2. Создаем локальный репозиторий.
3. Дружим наш локальный и удаленный репозиторий. ГитХаб при создании нового репозитория подсказывает как это сделать.
4. Отправить (push) наш локальный репозиторий в сервис ГитХаб. При этом возможно нужно будет пройти авторизацию.
5. Провести изменения с другого компьютера
6. Выкачать (pull) актуальное состояние из удаленного репозитория.

### Как поучаствовать в оупенсорс?
1. Делаем форк интересующего проекта
2. Делаем гитклон для нашей версии репозитория
3. Создаем ветку для наших дополнений
4. Делаем все изменения только в этой ветке
5. Отправляем эти изменения на свой аккаунт (push)
6. В окне на ГитХаб появляется возможность отправки pull request.

## Команды терминала

**clear** - очистка сообщений в терминале.

**cd "path"** - перемества
**cd ..** - переместиться на пафывпку назад

**ls** или **dir** - просмотр содержимого папки

##### Автор: Никита Ганченков