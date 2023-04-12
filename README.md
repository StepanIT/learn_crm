# git-config

git config --global user.name "Степан Рудаков"
git config --global user.email "19stepan94@mail.ru"

git config --list # посмотреть настройки

git config --global core.autocrlf true
git config --global core.safecrlf warn
git config --global core.quotepath off
git config --global init.defaultBranch main # Ветка по умолчанию

git init # инициализация репозитория
git add . # добавить все файлы
git commit -m 'описание' # сделать коммит
git status
git diff # текущие изменения
git diff --color-words # более развернуто изменения
git checkout . # вернуть всё к предыдущему комиту