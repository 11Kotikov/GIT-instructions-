# Instructions for working with GIT

![](https://fuzeservers.ru/wp-content/uploads/3/0/c/30c29ce4cc08523ecc6e1f205bc207d0.jpeg)

>## Basic GIT commands:


## 1. *User registration:*

1. *git config --* - **git config --global user.name «Your name»**

2. *git config --global user.email example@example.com* - **Введите e-mail**

## 2. *Other commands:*

* *git --version* - **Версия Git**

* *git init* - **создание локального репозитория**

* *git status* - **вывод статуса системы на данный момент**

* *git add* - **Добавляет версионность файлу**

* *git commit -m* **Фиксирует версию файла (создаёт коммит)**

* *git diff* - **просмотр изменений в двух последних ветках**

* *git log* - **Вывод версий в хронологическом порядке**

* *git checkout <Хэш номер коммита или название_ветки>* - **Переключает между различными зафиксированными версиями или ветками файла**

## 3. *Auxiliary programs:* 

* *git branch -d < branch name >*  **Удаляет ветку по имени**

* *git help* **список различных git команд**

## <span style="color:green"> *Recommended sequence of commands:* </span>

|Первая   |Вторая   |Третья|Четвёртая|
|----------|-----------|---------|------------|
|git status|git add    |git status  |git commit -m

>![e.g.:](https://ie.wampi.ru/2022/10/02/ss-git-status.jpg "Example")

## <span style="color:orange"> *Unrecommended commands for novice/begginer:*</span>
* *git pull* - **Стягивает фиксацию с репозиториев**

* *git fetch* - **Собирает все коммиты с целеврой ветки которые не находятся в текущей и записывает их в локальный репо (не добавляет в ветку master)**

* *git merge < merged brunch >* - **Сливает изменения из "сливаемой ветки" в текущую**

> *Воспользуйтесь для получения доп. информации* [документацией по GIT](https://git-scm.com/doc)

>*Для тренировки и обучению по GIT используйте* [онлайн-тренажёр](https://learngitbranching.js.org/)