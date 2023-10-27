### Cheat sheets for working with git
1. Задать или изменить имя пользователя можно с помощью команды:
    * git config --global user.name "Your name"
2. Задать или изменить имя почту пользователя можно с помощью команды:
    * git config --global user.email "Your email"
3. Инициализация репозитория:
    * git init
4. Добавление отдельных файлов или всех файлов в область подготовленных файлов:
    * git add file_name 
5. Проверка статуса репозитория:
    * git status
6. Внесение изменений однострочным сообщением или через редактор:
    * git commit -m "Your short summary about the commit"
7. Просмотр истории коммитов с изменениями
    * git log -p
8. Просмотр изменений до коммита:
    * git diff
9. Создание новой ветки и переход в неё
    * git branch new_branche_name
10. Просмотр списка веток:
    * git branch
11. Слияние двух веток:
    * git merge existing_branch_name
12. Отправка новой ветки в удалённый репозиторий:
    * git push -u origin new_branch