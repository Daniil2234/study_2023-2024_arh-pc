---
## Front matter
title: "Лабораторная работа №3"
subletit: "Язык разметки Markdown"
author: "Седохин Даниил Алексеевич"

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
Освоить процедуры оформления отчётов с помощью легковесного языка разметки Markdown.

# Выполнение лабораторной работы
1) Перейдём в каталог курса сформированный при выполнении лабораторной работы №2 с помощью команды cd (рис. @fig:001).

![Переход в каталог курса](image/1.jpeg){#fig:001 width=100%} 

2) Обновим локальный репозиторий, скачав изменения из удалённого репозитория с помощью команды git pull (рис. @fig:002).

![Обновление локального репозитория](image/2.jpeg){#fig:002 width=100%}

3) Перейдём в каталог с шаблоном отчёта по лабораторной работе №3 (рис. @fig:003).

![Переход в каталог lab03](image/3.jpeg){#fig:003 width=100%}

4) Проведём компиляцию шаблона с использованием Makefile с помощью команды "make" (рис. @fig:004). После этого у нас сгенерируются файлы report.pdf и report.docx.

![Компиляция с помощью "make"](image/4.jpeg){#fig:004 width=100%}

5) Удалим полученные файлы с использованием Makefiel с помощью команды "make clean" (рис. @fig:005). После этой команды будут удалены файлы report.pdf и report.docx.

![Удаление файлов с помощью "make clean"](image/5.jpeg){#fig:005 width=100%}

6) Откроем файл report.md с помощью текстогого редактора report.md (рис. @fig:006).

![Открытие report.md](image/6.jpeg){#fig:006 width=100%}



# Выводы
В ходе выполнения лабораторной работы №3 мы освоили процедуры оформления отчётов с помощью легковесного языка разметки Markdown.

