# Репозиторий для практикума
## Соответствие групп и тем на практикум.

### 1. Что такое система контроля версий
Системы контроля версий — это программные инструменты, помогающие командам разработчиков управлять изменениями в исходном коде с течением времени
### 2. Для чего нужна система контроля версий
Система контроля версий помогает разработчикам параллельно работать над проектом, не мешать друг другу и добавлять в master-ветку только качественный код.
### 3. Установка git на ваш ПК (в зависимости от системы)
 Официальная сборка доступна для скачивания на официальном сайте Git. Просто перейдите на страницу https://git-scm.com/download/win, и загрузка запустится автоматически. Далее все по дефолту
### 4. Установка VSCode на ваш ПК
Перейти на сайт https://code.visualstudio.com/docs/setup/windows. Скачать для винды. Далее все по дефолту.
### 5. Что такое репозиторий и инструкция по созданию локальных репозиториев.
Репозитории — это классы или компоненты, которые содержат логику, необходимую для доступа к источникам данных.
1. Создать папку
2. Открыть папку в VSC
3. Создать папку (например в формате`md`)
4. Открыть терминал и прописать `git init <название папки>`
5. Конец
### 6. Базовая работа с локальным репозиторием
Основные команды:<br>
```
git init
```
```
git add
```
Команда git add добавляет изменение из рабочего каталога в раздел проиндексированных файлов
```
git commit -m
```
Добавляет сохранение и комментарий 
```
git log
```
История всех изменений 
### 7. Что такое ветки и для чего они нужны при работе с системой контроля версий.
Помогают при работе.Можно оставить ветку и работать там, если ты неуверн в чем-то
8. Базовая работа с ветками в git.
```
git branch
```
Посмотреть все ветки
```
git checkout
```
Переход по веткам 
```
git branch -d <name>
```
Удалить ветку 
### 9. Что такое удаленный репозиторий и для чего он нужен
На удаленном репозитории может работать большая команда и вносить свои изменения.
### 10. Базовая работа с удаленными репозиториями GitHub
```
git clone
```
Клонировать репозиторий 
```
git pull
```
Скачать все данные 
```
git push
```
Отослать свои изменения 
### 11. Как строится и для чего нужна совместная работа в системах контроля версий
Удобно для работы в команде
### 12. Инструкция по созданию pull request
* В своём аккаунте на GitHub создать копию репозитория с помощью кнопки "Fork".
* Клонировать копию репозитория на локальный компьютер.
* Создать новую ветку.
* Добавить файл с инструкцией в новую ветку.
* Дополнить инструкцию разделами по работе с удалёнными репозиториями, pull request.
* Зафиксировать изменения (коммиты).
* Отправить изменения на GitHub.
* На сайте GitHub выполнить Pull request.
### 13. Книги и полезные ссылки по изучению git.
Есть, но не помню названия
### 14. Альтернативные системы контроля версий.
SVN, Mercurial
