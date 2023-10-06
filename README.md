# Работа с удаленными репозиториями #

**git remote -v** - вывести список добавленных удаленных репозиториев

**git remote show [name]** - дополнительная информация об удаленном репозитории

**git remote rename [old_name] [new_name]** - переименовать ссылку на репозиторий

**git remote rm [name]** - удалить ссылкуу на репозиторий

**git clone https** - клонировать уд.реп.

**git remote add origin [url]** - добавить удаленный репозиторий и назвать его origin

**git branch -M main** - назначить ветку main основной 

**git push -u origin main** - отправить в репозиторий origin

**git pull** - скачать изменения с уд.реп. и смержить


# Глобальные настройки GIT #  

**git config --global core.editor nano** - изменить стандартный редактор на nano

**git config --global user.name 'Name Name'** - имя сотрудника

**git config --global user.email 'email@adress'** - почта сотрудника

**git config --global alias.[name] [command]** - создать алиас с именем name, который будет выполнять действие command

# GIT TAG #

**git tag [tag]** - добавить тэг текущему коммиту

**git tag -a [tag] [checksum]** - добавить тэг конкретному коммиту

**git tag -d [tag]** - удалить тэг

# GIT BRANCH #  

**git branch** - показать ветки проекта

**git branch [name]** - создать ветку с именем name

**git merge [name]** - произвести слияние с веткой name

**git branch -d [name]** - удалить слитую ветку name

**git branch -D [name]** - удалить не слитую ветку name

**git checkout master** - перейти к ветке мастер

**git checkout [checksum]** - перейти к нужной ветке

**git checkout -b [name]** - создать и перейти к ветке name

# Cписок команд GIT #

**git init** - Инициализация репозитория

**git status** - статус проекта

**git add "fileName"** - добавить файл для отслеживания / индексировать

**git add .** - добавить все файлы и папки для отслеживания / индексировать

**git reset .** - убрать у всех  фалов в папке версионность

**git reset "fileName"** - убрать у файла версионность

**git commit -m "message"** - создать коммит (упрощенный вариант)

**git commit -am "message"** - создать коммит минуя команду git add

**git log** - журнал изменений

**git log --pretty=oneline** - история зафиксированных состояний

**git diff** - чем отличается текущий файл от коммита





1.fork - скопировать чужой репозиторий на свой акк. гитхаб.
2.Клонировать уд.реп в локальный реп. командой git clone 
3.Создать новую ветку
4.Внести измениния и сделать коммит
5.Запушить 
6.В гитхаб нажать ком. энд пул реквест




Чтобы игнорировать файл при индексации, необходимо создать файл с именем ".git ignore" и добавить туда название нужного файла. Затем выполнить команду git add .gitignore

[Руководство по Markdown](https://gist.github.com/Jekins/2bf2d0638163f1294637)
