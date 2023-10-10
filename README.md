# git-lesson-05-10

Hello world

#Добавим все файлы проекта в нам будующий commit
git add .
#Или так
git add --all

#Если хотим добавить конкретный файл то можно так
git add <имя_файла> 

#Теперь создаем commit. Обязательно указываем комментарий.
#И не забываем про кавычки
git commit -m "<комментарий>"

git branch – посмотреть список веток в репозитории
git branch <название ветки> – создать новую ветку
git checkout -b <название ветки> – создать новую ветку и переход к другой ветке
git branch -d <название ветки> – удалить ветку

Git via Git
If you already have Git installed, you can get the latest development version via Git itself:
git clone https://github.com/git/git
You can also always browse the current contents of the git repository using the web interface.
