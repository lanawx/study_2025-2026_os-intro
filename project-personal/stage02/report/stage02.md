---
## Front matter
title: "Индивидуальный проект 2 этап"
author: "Мартынова Милана Александровна"

## Generic options
lang: ru-Ru\
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
   - babelshorhands=true
polyglossia-otherlangs:
   name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
## Fonts
mainfont: Times New Roman
sansfont: Arial
monofont: Courier New
mathfont: Times New Roman
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
# 1. Цель работы

Осуществить дальнейшую работу с сайтом, привести его в соответствие с установленными требованиями и разместить на нем личные данные.

# 2. Задание

- Разместить фотографию владельца сайта.
- Разместить краткое описание владельца сайта (Biography).
- Добавить информацию об интересах (Interests).
- Добавить информацию от образовании (Education).
- Сделать пост по прошедшей неделе.
- Добавить пост на тему по выбору: Управление версиями. Git. Непрерывная интеграция и непрерывное развертывание (CI/CD).



# 3. Выполнение лабораторной работы

Скачиваю язык go для того чтобы изменения на сайте можно было тестировать локально. (рис. 1)

![Устновка go](02.1.jpg){#fig:001 width=70%}

Проверка запуска сайта на виртуальной машине. (рис. 2)

![Локальный запуск сайта](02.2.jpg){#fig:002 width=70%}

Загружаю в директорию сайта измененый файл с биографией и два поста. (рис. 3)

![Загрузка изменений](02.3.jpg){#fig:003 width=70%}

Проверка изменений на сайте. (рис. 4)

![Проверка изменений на сайте](02.4.jpg){#fig:004 width=70%}


# 4. Выводы

В ходе работы над сайтом были осуществлены его доработка согласно установленным требованиям и внесение информации о себе.

# Список литературы{.unnumbered}

::: {#refs}
:::