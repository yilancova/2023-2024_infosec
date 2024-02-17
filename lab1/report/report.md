---
## Front matter
title: "Отчет по лабораторной работе №1"
subtitle: "Дисциплина: Информационная безопасность"
author: "Ланцова Яна Игоревна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Начать знакомство с ОС Rocky Linux, вспомнить основы работы с GitHub, создать репозитрий. Вспомнить основы работ с Markdown.

# Теоретическое введение

Репозиторий (от англ. repository — хранилище) — место, где хранятся и поддерживаются какие-либо данные. Чаще всего данные в репозитории хранятся в виде файлов, доступных для дальнейшего распространения по сети. 

Контроль версий - это способ сохранять изменения с течением времени, не перезаписывая предыдущие версии. 

Распределенное ПО для контроля версий - каждый разработчик, работающий с репозиторием, имеет копию всего этого репозитория. 

# Описание результатов выполнения задания:

1. Настройка VirtualBox и ОС

(рис. [-@fig:001])

![ Создание виртуальной машины. 1](images/1.png){ #fig:001 width=70% }

(рис. [-@fig:002])

![ Создание виртуальной машины. 2](images/2.png){ #fig:002 width=70% }

(рис. [-@fig:003])

![ Создание виртуальной машины. 3](images/3.png){ #fig:003 width=70% }

(рис. [-@fig:004])

![ Создание виртуальной машины. 4](images/4.png){ #fig:004 width=70% }

(рис. [-@fig:005])

![ Запуск виртуальной машины](images/5.png){ #fig:005 width=70% }

2. Произведем первичные настройки ОС

(рис. [-@fig:006])

![ Установка английского языка интерфейса ОС](images/6.png){ #fig:006 width=70% }

(рис. [-@fig:007])

![ Окно настройки установки образа ОС](images/7.png){ #fig:007 width=70% }

(рис. [-@fig:008])

![ Окно настройки установки: отключение KDUMP](images/8.png){ #fig:008 width=70% }

(рис. [-@fig:009])

![ Выбор дополнительного языка](images/9.png){ #fig:009 width=70% }

(рис. [-@fig:010])

![ Настройка интернет-подключения](images/10.png){ #fig:010 width=70% }

(рис. [-@fig:011])

![ Установка пароля для root](images/11.png){ #fig:011 width=70% }

(рис. [-@fig:012])

![ Окно настройки установки образа ОС](images/12.png){ #fig:012 width=70% }

(рис. [-@fig:013])

![ Установка](images/13.png){ #fig:013 width=70% }

(рис. [-@fig:014])

![ Завершение установки](images/14.png){ #fig:014 width=70% }

3. Запустим виртуальную машину:

(рис. [-@fig:015])

![ Проверка работы Rocky Linux](images/15.png){ #fig:015 width=70% }

# Домашнее задание

(рис. [-@fig:016])

![ Результат выполнения команды dmesg](images/16.png){ #fig:016 width=70% }

(рис. [-@fig:017])

![  Поиск различной информации с помощью grep](images/17.png){ #fig:017 width=70% }


# Вывод

Начала знакомство с ОС Rocky Linux, вспомнила основы работы с GitHub. Вспомнила основы работ с Markdown.

# Контрольные вопросы для самопроверки

1. Какую информацию содержит учётная запись пользователя?

Учетная запись пользователя содержит такое данные как полное имя пользователя, username пользователя и его пароль.

2. Укажите команды терминала и приведите примеры:

– для получения справки по команде - man (man bash);
– для перемещения по файловой системе - cd (cd bin);
– для просмотра содержимого каталога - ls (ls bin);
– для определения объёма каталога - du -sh (du -sh ./Загрузки);
– для создания / удаления каталогов / файлов - rmdir (rmdir bin);
– для задания определённых прав на файл / каталог - chmod (chmod o-r month.txt);
– для просмотра истории команд - history.

3. Что такое файловая система? Приведите примеры с краткой характеристикой.

Файловая система – это инструмент, позволяющий операционной системе и программам обращаться к нужным файлам и работать с ними. Пример файловых систем: Apple File System (64-битная файловая система для IOS, MacOS, tvOS и watchOS оптимизированная для SSD), ext (Расширенная ФС, разработанная для ОС на ядре Linux), FAT (Классическая файловая система Windows применяется для небольших носителей информации и несложного структурирования сведений).

4. Как посмотреть, какие файловые системы подмонтированы в ОС?

Команда findmnt — это простая утилита командной строки, используемая для отображения списка смонтированных файловых систем.

5. Как удалить зависший процесс?

Зависший процесс можно удалить с помощью команды kill
