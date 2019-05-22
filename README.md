# git & github
# Commands
git init : Создание репозитория в существующем каталоге

# git config

git config --global user.name "UseName"

git config --global user.email UseName@gmail.com

git config --list // все данные настроек

# git ignore // игнорирование файлов и папок

.gitignore

 -# folder logs
logs/
 -# folder Users
Users/

docs/*.txt // игнорировать фали txt в папке docs

# git status

git status

git status --untracked-files=all

git status --untracked-files=normal

# git add // Добавление файлов

git add
git add . // добавить все файлы

git rm --cached 123.txt // удаление файла из git

git add 123.txt // добавить файл

git add "*.php" // индексирование всех модифицированих php фалов

# git commit

git commit -a -m"init" // поместить в индекс -- стартовая система git

git commit -m"commitName"

# github

git remote add origin https://github.com/UserName/project.git

git push -u origin master

git push

git clone https://github.com/UserName/project.git

git pull