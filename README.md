# Проект-Помощник

---

## Знакомство с Bash-ом

### Что такое Bash

Bash — это командная оболочка для UNIX-подобных операционных систем (UNIX, GNU/Linux, MacOS). Она дает пользователю систему команд для работы с файлами и папками, поиском, настройкой окружения и позволяет управлять ОС прямо из командной строки. Слово bash читается как «баш» и расшифровывается как Bourne-Again Shell.

### Навигация

- `pwd` (от англ. print working directory) - Вывести директорию, где мы работаем
- `cd` (от англ. change directory) - Сменить директорию
- `ls` (от англ. list directory contents) - Вывести содержимое директории

---

### Работа с папками/файлами

#### Создание

- `mkdir` (от англ. make directory) - создание папки
- `touch` (от англ. make file) - создание файла

---

#### Копирование/перемещение

- `mv` (от англ. move file) - движение файла из директории A в B
- `cp` (от англ. copy file) - копирование файла из директории A в B

---

#### Удаление

- `rm` (от англ. remove file) - удаление файла
- `rmdir` (от англ. remove directory) - удаление папки

---

#### Чтение

- `cat` (от англ. concatenate and print) - чтение из файла

---

## Знакомство с GIT-ом

### что такое GIT

Git - система управления версиями с распределенной архитектурой. В отличие от некогда популярных систем вроде CVS и Subversion (SVN), где полная история версий проекта доступна лишь в одном месте, в Git каждая рабочая копия кода сама по себе является репозиторием. Это позволяет всем разработчикам хранить историю изменений в полном объеме.

---

### Что такое GitHub

GitHub — это сервис для совместной разработки и хостинга проектов. C помощью GitHub над кодом проекта может работать неограниченное количество программистов из любых точек мира. В GitHub есть система контроля (управления) версий Git: сервис позволяет просматривать и контролировать любые изменения кода любым разработчиком и возвращаться к состоянию до изменений.
Иными словами GitHub - это социальная сеть для разработчиков, в которой можно найти проекты с открытым кодом от других разработчиков, практиковаться в написании кода и хранить свое портфолио.

---

### Инициализация

- `git init` - инициализиация директории(директория становится git-репозиторием, в которую можно "заливать" версии проекта).

---

### отслеживане файла

`git add` - начинает отслеживание за файлом а если файл отслеживается и был изменен, то можно "сохрнанить" эти изменения с помощью этой команды.

---

### Снимок проекта

`git commit -m` - Делает "снимок" проекта и сохраняет в локальную репозиторию, у которого есть свое описание(сохраняет его как версию проекта). Здесь флаг `-m` указывает на сообщение или на описание "снимка".

---

### соединение с удаленным репозиторием

` git remote add` - Соединяет нашу локальную репозиторию с удаленным.

---

### Информация про соединение

`git remote -v` - Показывает ветку и за какую репозиторию он отвечат.

---

### Синхронизация с удаленным репозитрием

`git push` - Синхронизация локального репозитория с удаленным репозиторием. Данная команда "заливает" в удаленную репозиторию файлы или папки с данными, которые есть в локальном репозитории.
