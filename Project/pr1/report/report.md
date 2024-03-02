---
## Front matter
title: "Отчет по индивидуальному проекту №1"
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

Установить дистрибутив Kali Linux в виртуальную машину.

# Описание результатов выполнения задания:

(рис. [-@fig:001])

![ Скачаем образ Кali Linux с официального сайта](images/1.png){ #fig:001 width=70% }

(рис. [-@fig:002])

![ Создание виртуальной машины. 1](images/2.png){ #fig:002 width=70% }

(рис. [-@fig:003])

![ Создание виртуальной машины. 2](images/3.png){ #fig:003 width=70% }

(рис. [-@fig:004])

![ Создание виртуальной машины. 3](images/4.png){ #fig:004 width=70% }

(рис. [-@fig:005])

![ Запуск виртуальной машины](images/5.png){ #fig:005 width=70% }

(рис. [-@fig:006])

![ Установка английского языка интерфейса ОС](images/6.png){ #fig:006 width=70% }

(рис. [-@fig:007])

![ Зададим имя пользователя](images/7.png){ #fig:007 width=70% }

(рис. [-@fig:008])

![ Настройка установщика 1](images/8.png){ #fig:008 width=70% }

(рис. [-@fig:009])

![ Настройка установщика 2](images/9.png){ #fig:009 width=70% }

(рис. [-@fig:010])

![ Настройка установщика 3](images/10.png){ #fig:010 width=70% }

(рис. [-@fig:011])

![ Настройка установщика 4](images/11.png){ #fig:011 width=70% }

(рис. [-@fig:012])

![ Установка](images/12.png){ #fig:012 width=70% }

(рис. [-@fig:013])

![ Вход в систему](images/13.png){ #fig:013 width=70% }

(рис. [-@fig:014])

![ Работа виртуальной машины](images/14.png){ #fig:014 width=70% }

# Вывод

Начала знакомство с ОС Kali Linux, вспомнила основы работы с GitHub. Вспомнила основы работ с Markdown.

