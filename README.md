# Репозиторий для практикума
## Соответствие групп и тем на практикум.

1. Что такое система контроля версий
Git Возможность хранить разные версии одного и того же кода

2. Для чего нужна система контроля версий
* Возвращаться к прежней версии кода
* Если несколько человек занимаются один проектом
* Актуально если проект длиться больше одного дня

3. Установка git на ваш ПК (в зависимости от системы)
перейти най сайт Гита и скачать ГИТ для виндоус 7 х64


## Комманды Git основные настройки Git
* **git config --global** - показывает глобальные настройки системы.
* **git config --global user.name "Stanislav"** - устанавливает глобальное имя администратора.
* **git config user.name** - проверка имени администратора.
* **git config --global user.email "nelson-uo@mail.ru"** - устанавливает глобальную почту администратора.
* **git config user.email** - проверка почты администратора.
* **git config --global color.ui auto** - включает подсветку комманд в терминале.
* **git config --global core.editor** - "[ПРОГРАММА]"

* Settings -> Terminal -> Integrated Default Profile: **Git Bashg**

4. Установка VSCode на ваш ПК
Перйти на сайт VSCode и скачать приложение под свою ОС

5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
* **Репозиторий** - хранилище вашего кода и историй его изменений. Git работает локально и все ваши репозитории хранятся в определенных папках на жестком диске. Накладываются по слойно. (Репозитории бываю локальные и облачные).
Создать папку , перейти в папку, иницилизировать папку командой git init

6. Базовая работа с локальным репозиторием
 **git add ИМЯ ФАЙЛА** - добавить файл к индексу отслеживания.
* **git commit** - "i" - для добавления комментария, "Кнопка - Esc" - завершения добавления 
* **git log** - вывод на экран истории всех коммитов с ссылками на них.



7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
Для парарельной работы нескольких разработчиков над одним проектом

8. Базовая работа с ветками в git.
* **git checkout ССЫЛКА** - переход от одного коммита к другому по ссылке.
* **git checkout main** - вернуться на актуальную главную ветку.
* **git branch** - без значения показывает ветви.

9. Что такое удаленный репозиторий и для чего он нужен
Для обмена своей рабоы с другими участиками проекта

10. Базовая работа с удаленными репозиториями GitHub
* **git clone** - для получения доступа к удалённому репозиторию вставляем скопированную ссылку с GitHub: https://github.com/ilnar-geekbrains/version_control_lection_3.git .
ПРИМЕР:
git clone https://github.com/ilnar-geekbrains/version_control_lection_3.git
* **git remote** - подключает удаленный репозиторий к вашему под переданным именем.
ПРИМЕР:
git remote add ("origin" - СТАНДАРТНОЕ ИМЯ РЕПОЗИТОРИЯ) https://github.com/StanislavSergeevY/Lessons3.git
git remote add origin https://github.com/StanislavSergeevY/Lessons3.git
* **git remote -v** - показывает список подлюченных соединений.
* **git fetch** - получение изменений из удаленного репозитория.
* **git pull** - получение изменений из удаленного репозитория.
* **git push** - отправка изменений в удаленный репозиторий.
* **git push --set-upstream origin main** - отправляет новую ветку в общий репозиторий чтобы все остальные могли её видеть.
* **git push -u origin S.Sergeev** - 
* **git remote set-url origin ССЫЛКА** - если не правльно была указана ссылка и поймана ошибка (request **403**)
* **git remote add origin ССЫЛКА** - привязать свой существующий репозиторий к удалённому, в заранее созданному на GitHub с помощью ссылки на него.
ПРИМЕР: git remote add origin https://github.com/StanislavSergeevY/UltimaOnline_Macros.git


11. Как строится и для чего нужна совместная работа в системах контроля версий
Каждый разрабочик занимается свои блоком общео проекта

12. Инструкция по созданию pull request
* **git remote set-url origin ССЫЛКА** - если не правльно была указана ссылка и поймана ошибка (request **403**)


13. Книги и полезные ссылки по изучению git.
Git для профессионального промграммиста.pdf
https://learngitbranching.js.org/?locale=ru_RU
https://vimeo.com/showcase/5616060
Курсы GB

14. Альтернативные системы контроля версий.
с этой бы до конца разобраться ;)