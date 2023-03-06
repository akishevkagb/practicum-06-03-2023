# Репозиторий для практикума
## Соответствие групп и тем на практикум.

1. Что такое система контроля версий
Система контроля версий (СКВ) - это программное обеспечение, которое позволяет отслеживать изменения в коде и документации, а также управлять их версиями.
2. Для чего нужна система контроля версий
Система контроля версий (СКВ) используется для управления изменениями в коде программного обеспечения, документации и других файлов.
3. Установка git на ваш ПК (в зависимости от системы)
Установка Git на ПК может отличаться в зависимости от операционной системы. Вот несколько инструкций по установке Git на различные платформы:
Установка Git на Windows:
Скачайте установочный файл для Windows с официального сайта Git (https://git-scm.com/download/win).
Запустите установочный файл и следуйте инструкциям на экране. По умолчанию Git устанавливается в папку "C:\Program Files\Git".
После завершения установки запустите Git Bash, чтобы убедиться, что Git установлен корректно.
4. Установка VSCode на ваш ПК
Для установки Visual Studio Code на ПК необходимо выполнить следующие шаги:
Перейдите на официальный сайт Visual Studio Code по адресу https://code.visualstudio.com/.
Нажмите на кнопку "Download for Windows" или "Download for Mac" в зависимости от операционной системы вашего ПК.
После загрузки установочного файла запустите его и следуйте инструкциям на экране для завершения установки.
После установки запустите Visual Studio Code и начните работать.
Обратите внимание, что на ПК также должен быть установлен Git, если вы планируете использовать его вместе с Visual Studio Code для контроля версий.
5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
Репозиторий - это хранилище, где хранятся файлы и история изменений для проекта. Система контроля версий (например, Git) используется для управления изменениями в репозитории. Репозиторий может быть локальным (хранится на компьютере) или удаленным (хранится на сервере).

Для создания локального репозитория с помощью Git, выполните следующие шаги:

Установите Git на свой компьютер, если он еще не установлен.

Создайте пустую папку, которая будет являться корневой папкой вашего локального репозитория.

Откройте командную строку (Windows) или терминал (Mac/Linux) и перейдите в созданную пустую папку.

Используйте команду git init, чтобы инициализировать пустой локальный репозиторий в этой папке.

Добавьте файлы в ваш локальный репозиторий с помощью команды git add.

Сделайте коммит изменений с помощью команды git commit -m "Описание ваших изменений". Коммит создаст новую версию в вашем локальном репозитории.

Повторяйте шаги 5 и 6 по мере необходимости для сохранения изменений в вашем локальном репозитории.
6. Базовая работа с локальным репозиторием
Работа с локальным репозиторием Git включает в себя следующие основные шаги:

Создание репозитория: для создания локального репозитория вам нужно выполнить команду git init в папке проекта. Это создаст пустой репозиторий Git в папке проекта.

Добавление файлов в репозиторий: после создания репозитория необходимо добавить файлы в репозиторий, чтобы Git мог отслеживать изменения в файлах. Для добавления файлов в репозиторий можно использовать команду git add <filename>.

Создание коммита: после добавления файлов в репозиторий нужно создать коммит, чтобы сохранить изменения в репозитории. Для создания коммита используется команда git commit -m "Commit message".

Просмотр истории коммитов: для просмотра истории коммитов в локальном репозитории используется команда git log.

Отмена изменений: если вам нужно отменить изменения, которые вы внесли в файлы, можно использовать команду git checkout -- <filename> для отмены изменений в конкретном файле или команду git reset для отмены всех изменений, которые были добавлены в последний коммит.

Работа с ветками: для создания новых веток или переключения между существующими ветками используются команды git branch <branch_name> и git checkout <branch_name> соответственно.

Синхронизация с удаленным репозиторием: чтобы отправить изменения из локального репозитория на удаленный сервер, необходимо выполнить команду git push. А чтобы получить изменения из удаленного репозитория, нужно выполнить команду git pull.

Это основные шаги, которые позволяют работать с локальным репозиторием Git.
7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
Ветки (branches) в системах контроля версий позволяют работать с несколькими версиями одного и того же проекта, при этом не затрагивая основную ветку, называемую обычно "материнской" (master).

Ветки обычно используются для разработки новых функций, исправления ошибок и тестирования, не мешая работе других участников проекта.
8. Базовая работа с ветками в git.
Основные команды для работы с ветками в Git:

git branch – просмотр всех веток репозитория и текущей ветки.
git branch <название_ветки> – создание новой ветки с указанным именем.
git checkout <название_ветки> – переключение на другую ветку.
git merge <название_ветки> – объединение указанной ветки с текущей веткой.
git branch -d <название_ветки> – удаление указанной ветки.
9. Что такое удаленный репозиторий и для чего он нужен
Удаленный репозиторий в системе контроля версий - это хранилище, расположенное на удаленном сервере, в котором хранятся версии кода, которые можно загрузить и использовать для работы над проектом. Он является основным механизмом для совместной работы нескольких разработчиков над одним проектом.
10. Базовая работа с удаленными репозиториями GitHub
Вот несколько команд Git, которые используются при работе с удаленным репозиторием на GitHub:

git clone - клонирует удаленный репозиторий на ваш компьютер.
git remote - позволяет просмотреть список удаленных репозиториев, связанных с вашим локальным репозиторием.
git pull - получает изменения с удаленного репозитория и обновляет ваш локальный репозиторий.
git push - отправляет изменения с вашего локального репозитория на удаленный репозиторий.
git fetch - получает изменения с удаленного репозитория, но не обновляет ваш локальный репозиторий, пока вы не выполните команду git merge.
Кроме того, при работе с удаленным репозиторием на GitHub, вы можете использовать такие функции, как:

Pull requests - позволяет вам отправлять свои изменения на проект другого разработчика и запросить их включение в основную ветку проекта.
Issues - позволяет вам отслеживать ошибки, запросы на функции и другие проблемы, связанные с проектом, и общаться с другими участниками проекта для их решения.
11. Как строится и для чего нужна совместная работа в системах контроля версий
Совместная работа в системах контроля версий (VCS) представляет собой процесс, в котором несколько человек могут работать над одним и тем же проектом одновременно, совместно управляя исходным кодом, документами и другими файлами в общем репозитории.
12. Инструкция по созданию pull request
Инструкция по созданию pull request:

Находясь в своем репозитории на GitHub, перейдите во вкладку "Pull requests".
Нажмите на кнопку "New pull request".
Выберите "base" ветку, в которую вы хотите внести изменения. Это может быть главная ветка проекта или какая-то другая ветка, созданная членом команды.
Выберите "compare" ветку, содержащую изменения, которые вы хотите внести в "base" ветку.
Нажмите на кнопку "Create pull request".
Введите описание изменений, которые вы внесли в "compare" ветку.
Нажмите на кнопку "Create pull request" еще раз, чтобы отправить запрос на проверку.
13. Книги и полезные ссылки по изучению git.
Некоторые из лучших книг и ресурсов для изучения git:

"Pro Git" от Scott Chacon и Ben Straub (https://git-scm.com/book/en/v2)
"Git Pocket Guide" от Richard E. Silverman (https://www.oreilly.com/library/view/git-pocket-guide/9781449327507/)
"Git for Teams" от Emma Jane Hogbin Westby (https://gitforteams.com/)
"Git Internals" от Peff (https://github.com/pluralsight/git-internals-pdf)
Git Cheat Sheet (https://education.github.com/git-cheat-sheet-education.pdf)
14. Альтернативные системы контроля версий.
из них:

Mercurial - распределенная система контроля версий, созданная для обеспечения быстрой и эффективной работы с большими проектами.

Subversion (SVN) - централизованная система контроля версий, использующаяся для управления исходным кодом, документами и другими файлами.

Perforce - коммерческая система контроля версий, предназначенная для управления большими проектами и коллективной разработки.

CVS - старейшая система контроля версий, которая используется в различных проектах для управления версиями кода.

Bazaar - распределенная система контроля версий, созданная на основе концепции управления версиями в распределенной среде.

GitLab - веб-приложение для управления кодом, которое предоставляет инструменты для хранения, управления и распространения кода.

Bitbucket - веб-приложение для управления кодом, разработанное компанией Atlassian.