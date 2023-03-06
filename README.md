# Репозиторий для практикума
## Соответствие групп и тем на практикум.

1. Что такое система контроля версий - это система, регистрирующая изменения в одном или нескольких файлах с тем, чтобы в дальнейшем была возможность вернуться к определённым старым версиям этих файлов (типичный пример: выложили версию в проду, начали работу над новыми фичами и вдруг обнаружились ошибки. Нужно не потеряв новых наработок вернуться к рабочей версии, исправить ошибки).
2. Для чего нужна система контроля версий - cистема контроля версий, также называемая системой управления исходным кодом, позволяет отслеживать изменения исходного кода с течением времени. Эта система обеспечивает быстрое и эффективное сотрудничество разработчиков, сохраняя целостность кода. Это позволяет команде работать, не опасаясь конфликтов в коде.
3. Установка git на ваш ПК (в зависимости от системы) - загрузить и установить Git для Windows. После установки Git доступен из командной строки или PowerShell.
4. Установка VSCode на ваш ПК - загрузить и установить VS Code с сайта code.visualstudio.com 
5. Что такое репозиторий и инструкция по созданию локальных репозиториев. - Для того, чтобы добавить версионность к созданной папке, и создать в ней локальный репозиторий, для этого необходимо открыть окно терминала в этой папке и написать команду git init. Тогда Ваша папка станет репозиторием, и в ней появится скрытая папка .git
6. Базовая работа с локальным репозиторием - Для начала работы с центральным репозиторием, следует создать копию оригинального проекта со всей его историей локально.
7. Что такое ветки и для чего они нужны при работе с системой контроля версий. - ветка – это последовательность коммитов
8. Базовая работа с ветками в git. - git branch - показывает все ветки проекта и в какой ветке ведется работа сейчас. Если такой ветки не существует - создает ветку. Имеет кучу дополнительных параметров.
git merge - сливает ветки друг с другом. Работает по принцу "добавить к ветке, на которой ведется работа, ветку, имя которой указано в команде". Конфликты можно разрешить вручную.
9. Что такое удаленный репозиторий и для чего он нужен - удалённые репозитории представляют собой версии моего проекта, сохранённые в интернете или ещё где-то в сети. Дает возможность работать над проектом с любого места, где есть доступ к сети
10. Базовая работа с удаленными репозиториями GitHub - Команды: clone, fetch, push, pull
11. Как строится и для чего нужна совместная работа в системах контроля версий - для того чтобы работать над проектом совместно с другими участниками разработки.
12. Инструкция по созданию pull request git add, git commit -m, git remote, git push origin [Branch Name]
13. Книги и полезные ссылки по изучению git. Git Magic, Pro Git
14. Альтернативные системы контроля версий. Mercurial SCM, Fossil, Apache Subversion, Bazaar, darcs
