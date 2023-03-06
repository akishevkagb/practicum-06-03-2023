# Репозиторий для практикума
## Соответствие групп и тем на практикум.

1. Что такое система контроля версий
Это система контроля изменений в файлах.

2. Для чего нужна система контроля версий
Система контроля версий нужна для того, чтобы хранить разные версии файлов, а также иметь возможность вернуться к ранее созданным версиям.

3. Установка git на ваш ПК (в зависимости от системы)


4. Установка VSCode на ваш ПК:
- Открываем сайт VSCode 
- Выбираем ОС (необходимую)
- Скачиваем установщик на ПК
- Установливаем следуя инструкциям установщика
- Запускаем VSCode и проверяем работу

5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
Репозито́рий — место, где хранятся и поддерживаются какие-либо данные. Чаще всего данные в репозитории хранятся в виде файлов, доступных для дальнейшего распространения по сети.
Для создания локального репозитория необходимо:
- создать папку;
- открыть папку в VSCode;
- завести команду git init.

6. Базовая работа с локальным репозиторием
7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
Ветки нужны для того, чтобы была возможность работать с разными версиями файла, в том числе разным пользователям. 

8. Базовая работа с ветками в git.
git branch -- показывает все ветки проекта и в какой ветке ведется работа сейчас. Если такой ветки не существует - создает ветку. Имеет кучу дополнительных параметров.

git merge -- сливает ветки друг с другом. Работает по принцу "добавить к ветке, на которой ведется работа, ветку, имя которой указано в команде". Конфликты можно разрешить вручную.

9. Что такое удаленный репозиторий и для чего он нужен
10. Базовая работа с удаленными репозиториями GitHub
11. Как строится и для чего нужна совместная работа в системах контроля версий
12. Инструкция по созданию pull request
- на Github делаем Fork репозитория;
- Копируем ссылку удаленного репозитория;
- Открываем папку и терминал редактора исходного кода;
- Вводим команду в терминале, которой выполняем копирование удаленного репозитория;
- git clone <Ссылка на удаленный репозиторий>
- Вводим команду в терминале, которой переключаемся с изначальной открытой папки на репозиторий, который скопировали:
cd <Наименование скопированного репозитория>;
- Создаем ветку, в которой разрабатываем код:
git branch <Наименование ветки>;
- Сохраняем изменения в созданной ветке:
git add <Наименование папки>
git commit -m "Комментарий к сохранению"
- Отправляем локальный репозиторий на Github
git push;
- В удаленном репозитории на Githum нажимаем кнопку "Contribute", затем кнопку "Open pull request";
- Добавляем комментарий к своему Fork и нажаимаем кнопку "Create pull request".
13. Книги и полезные ссылки по изучению git.
jQuery Recipes: Find Ready-Made Solutions to All Your jQuery Problems, 2nd Edition (2021)
Автор: Bintu Harwani
Количество страниц: 710

14. Альтернативные системы контроля версий.
