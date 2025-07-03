git clone url_гита
git init
ls -a

git remote -v проверка привязки к гиту
git remote add origin url_гита

git config user.name
git config user.email
git config user.email "" для изменения почты
-------
git reset __name_file убрать из stage
git diff name_file просмотреть измен файла
git reset --hard отменяет то что можно посмотреть в gitstatus

--------

git status
git add [files] добавить файлы в stage
git add . (все файлы через точку)
git commit -m "commit"
git log просмотр записи вся 
git log --oneline кратк запись о коммитах
git push [link] [branch name] отправить на гит
git branch какая ветка все ветки
git branch develop создать ветку
git checkout develop переключится на ветку выбранная ветка под звездочкой
git push origin master отправить в гит
-
Чтобы подключить к гиту созданному на github


echo "# git_info" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/grig1505/git_info.git
git push -u origin main

git remote add origin https://github.com/grig1505/git_info.git
git branch -M main
git push -u origin main
--
слияние веток  pull request на гите
git pull origin master забрать с гита
git branch -d develop удалить с лок репоз ветку

!(слияние веток ) Чтобы смержить ветку нужно перключится на master : git merge develop (ветка с которой переносим)
---------------
gitFlow методика по работе с git
1 создать репозиторий и склонировать git clone url_...
2 создать ветку для разработки от главной ветки master или main
3 создать от ветки develop под ветки и после когда будут фичи сделаны замержить на основную develop ранее создануую
4 создание ветки реализ relese/0.1.0 
5 когда закончена и мержится в develop и main затем удаляется relese/0.1.0
6 если в ветке main обнаружена ошибка то создается hotfix ветка
7 когда работа над hotfix веткой завершается то ее нужно мержить в develop и main

git branch просмотреть все ветки
git branch develop создать ветку
git checkout develop выбрать ветку
git checkout develop создать и переключится на ветку
git push origin develop отправить на гит ветку
git add .
git commit -m 'nazvanie comitta'

--------------
создание ключа
ssh-keygen -o
-
cat __директория к ключу  (прочитать ключ)
-
ssh-add __директория к ключу
git clone (и ссылка на ссш)

