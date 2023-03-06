# Репозиторий для практикума
## Соответствие групп и тем на практикум.

1. Что такое система контроля версий
практика, которая позволяет отслеживать
изменения исходного кода и управлять ими.
2. Для чего нужна система контроля версий
1. хранить разные версии проекта;
2. возвращаться к разным версиям проекта.
3. Установка git на ваш ПК (в зависимости от системы)
Прежде чем создавать репозиторий и инициализировать Git, проверим текущую установленную версию пограммы. 
Для этого в терминале введём команду:
_git --version_

Если Git установлен на компьютер, вы увидите его текущую версию.

### Создание Git-репозитория:

1. Берём локальный каталог, который не
находится под версионным контролем,
и превращаем его в репозиторий.

2. Клонируем существующий репозиторий
из любого места.

4. Установка VSCode на ваш ПК
sudo apt vscode 
5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
**Команда git init**

Инициализация: указываем папку, в которой
git начнёт отслеживать изменения
В папке создаётся скрытая папка .git
6. Базовая работа с локальным репозиторием
git status
git add
git commit
git log
7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
Для хранения черновых версий
Для работы над одним проектом разными программистами
8. Базовая работа с ветками в git.
git branch name_of_branch
git checkout branch_name
git branch -d name_of_branch
9. Что такое удаленный репозиторий и для чего он нужен
For many reasons 
10. Базовая работа с удаленными репозиториями GitHub
git clone

11. Как строится и для чего нужна совместная работа в системах контроля версий
Для работы над одним проектом
Каждый программист работает в своей ветке. После этого выполняется git merge
12. Инструкция по созданию pull request
1.делаем (ответвление) репозиторияfork;
2. делаем git clone версии репозитория;
3. создаем новую ветку и в НЕЕ вносим свои изменения;
4. фиксируем изменения (делаем коммиты);
5. отправляем свою версию в свой GitHub;
6. на сайте GitHub нажимаем кнопку pull request.
13. Книги и полезные ссылки по изучению git.
Курс на гикбрейнс, который указан под первой лекцией
14. Альтернативные системы контроля версий.
Неизвестно
