# GIT-comands

git init - создание папки .git 
git clone [url] - клонирование репозитория
git clone [url] *name* - клонирование репозитория и присваивание имени name
git status - определение состояниф файлов
git add *file* - делает файл отслеживаемым (файлы через пробел)
cat .gitignore - игнорирвоание файлов
git diff - подробная команда, выводящая добавленные и удаленные файлы
git commit - фиксация изменений 
git commit -m - фиксация изменений и комментарий коммита
git commit -a - фиксация изменений + команда git add
git rm *file* - удаление файла из отслеживаемых и репозитория
git rm *file* -f - принудительно
git rm --cached *file* - удаление файла из отслеживаемых, сохранение его в репозитории
git mv *file_first* *file_second* - переименовать файл
git log - просмотр истории версий
git log -p - просмотр истории версий c разницей между коммитами
git log -3(-2) - просмотр истории 3(2) последних версий
git log -stat - показывает измененные файлы
git log --author=*author_name* - просмотр истории коммитов определнного автора
git commit --amend - повторное сохранение предыдущего коммита
git reset HEAD *file* - отмена индексированного файла
git checkout -- *file* - возвращает файл к состоянию предыдущего коммита
git remote - показывает удаленные сервера
git remote -v - показывает удаленные сервера с URL-ссылками
git fetch *server* - извлечение данных из удаленного репозитория
git pull - извлечение данных с ветки и слияние с текущей локальной веткой
git push *server* *branch* - указывает ветку, куда пушить
git remote show *server* - показывает информацию о конкретном сервере
git config --global alias.*alias* *command* - создание псевдонима alias для команды command
git config --global alias.br branch
git config --global alias.co checkout
git config --global alias.ci commit
git config --global alias.st status
git branch *name* - создание новой ветки
git checkout *name* - переход на ветку name
git checkout -b *name* - создание новой ветки и переход на нее
git merge *branch* - объединение веток (HEAD должна быть на главной ветке)
git branch -d *name* - удаление ветки


