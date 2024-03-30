---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Дисциплина "Информационная безопасность"
author:
  - Ланцова Я. И.
institute:
  - Российский университет дружбы народов, Москва, Россия
  - Объединённый институт ядерных исследований, Дубна, Россия

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---


# Вводная часть

## Актуальность

- Необходимость навыков работы с различными ОС, git, Markdown.

## Объект и предмет исследования

- Операционная система Rocky Linux
- Атрибуты файлов и директорий в Linux
- Язык разметки Markdown

## Цели и задачи

- Получение практических навыков работы в консоли с расширенными атрибутами файлов.

## Процесс выполнения работы

![ От имени пользователя guest определим расширенные атрибуты файла /home/guest/dir1/file1 командой lsattr /home/guest/dir1/file1](images/1.png){ #fig:001 width=50% }

## Процесс выполнения работы

![ Снимим расширенный атрибут a с файла /home/guest/dirl/file1 от имени суперпользователя командой chattr -a /home/guest/dir1/file1 (рис. @fig:04). Повторим операции, которые ранее не удавалось выполнить. Операции могут быть успешно выполнены](images/4.png){#fig:002 width=50%}

## Процесс выполнения работы

![ Повторим действия по шагам, заменив атрибут «a» атрибутом «i». В отличие от атрибута «a», с атрибутом «i» дозаписать информацию в файл нет возможности](images/5.png){#fig:003 width=50%}

# Результаты

- Выполнены все необходимые действия.

## Вывод

Получены практические навыкы работы в консоли с расширенными атрибутами файлов.
