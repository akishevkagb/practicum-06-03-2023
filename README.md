# Репозиторий для практикума
## Соответствие групп и тем на практикум.

1. Что такое система контроля версий

Система контроля версий — это система, записывающая изменения в файл или набор файлов в течение времени и позволяющая вернуться позже к определённой версии.

2. Для чего нужна система контроля версий

Для хранения изменений в файле, и для возможности возвращения к изменениям с целью работы над ними.

3. Установка git на ваш ПК (в зависимости от системы)

Установка заключается в загрузке на ПК приложения Git с сайта программы и настройке ее.

4. Установка VSCode на ваш ПК

Для установки VSCode, необходимо загрузить программу на ПК с сайта программы.

5. Что такое репозиторий и инструкция по созданию локальных репозиториев.

Репозиторий это папка с проектом иннициализированная в системе контроля версий.

Для создания локального репозитория необходимо создать папку проекта и открыть ее в программе VSCode. Затем иннициализировать ее командой git init.

6. Базовая работа с локальным репозиторием

Базовая работа заключается в создании файлов, сохранении их и добавления, а так же установкой коммитов изменений, добавления веток с изменениями.

7. Что такое ветки и для чего они нужны при работе с системой контроля версий.

Ветки это черновики с изменениями.

8. Базовая работа с ветками в git.

Ветки создаются командой git branch name (name - имя ветки), переход к ветке команда git checkout name, удаление ветки команда git branch -d name, для сливания веток команда git merge name.

9. Что такое удаленный репозиторий и для чего он нужен

Это репозиторий размещенный на специальном сервере. Он служит для совместной работы над проектами.

10. Базовая работа с удаленными репозиториями GitHub

Базовая работа состоит в создании аккаунта на GitHub и размещении своего проекта (создании удаленного репозитория) для совместной работы, копирования чужого и размещения отредактированной версии чужого с целью помощи.   

11. Как строится и для чего нужна совместная работа в системах контроля версий

Для того, чтобы начать работать над совместным проектом необходимо либо разместить свой проект для возможности другим людям работать над ним, либо создать свою копию чужого проекта, работая над ней вносить изменения и предлагать их "хозяину" проекта. После проведенной совместной работы закачать с помощью команды git pull проект на свой ПК.

12. Инструкция по созданию pull request

Сделать Fork, то-есть добавить копию чужого проекта к себе в аккаунт. Создать клон проекта. Загрузить клон к себе на ПК в программе VSCode с помощью команды git clone. Добавить изменения в проект, добавляя их в новые ветки (не в основной ветке). Отправить измененный проект к себе в удаленный репозиторий командой git push. На удаленном репозитории появится кнопка Pull request (команда для предложения изменений и вливания их в репозиторий).

13. Книги и полезные ссылки по изучению git.

https://gbcdn.mrgcdn.ru/uploads/asset/4245110/attachment/d4eb8c232f8f2bdf4e42ba7cb49e0c50.pdf

14. Альтернативные системы контроля версий.

SVN, Mercurial, CVS (Concurrent Versions System), Bazaar.
