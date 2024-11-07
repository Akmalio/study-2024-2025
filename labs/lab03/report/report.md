---
## Front matter
title: "Лабораторная работа 3"
subtitle: "Язык разметки Markdown"
author: "Мадалиев А.А"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Ознакомиться с работой языка разметки Markdown, выполнить задания в соот-
ветствии с лабораторной работы, а также составить отчет о выполненной работе

# Задание

1. Ознакомиться с базовыми сведениями о Markdown
2. Перейти в каталог “arch-pc” выполнить команду git pull
3. Выполнить команду make для компиляция шаблона
4. Удалите полученный файлы с использованием Makefile
5. Откройте файл report.md c помощью любого текстового редактора
6. Заполните отчет и скомпилируйте отчет с использованием Makefile.
7. Загрузить файлы на Github
8. Выполнить задание для самостоятельной работы
# Теоретическое введение

Здесь описываются теоретические аспекты, связанные с выполнением работы.

Например, в табл. [-@tbl:std-dir] приведено краткое описание стандартных каталогов Unix.

: Описание некоторых каталогов файловой системы GNU Linux {#tbl:std-dir}

| Имя каталога | Описание каталога                                                                                                          |
|--------------|----------------------------------------------------------------------------------------------------------------------------|
| `/`          | Корневая директория, содержащая всю файловую                                                                               |
| `/bin `      | Основные системные утилиты, необходимые как в однопользовательском режиме, так и при обычной работе всем пользователям     |
| `/etc`       | Общесистемные конфигурационные файлы и файлы конфигурации установленных программ                                           |
| `/home`      | Содержит домашние директории пользователей, которые, в свою очередь, содержат персональные настройки и данные пользователя |
| `/media`     | Точки монтирования для сменных носителей                                                                                   |
| `/root`      | Домашняя директория пользователя  `root`                                                                                   |
| `/tmp`       | Временные файлы                                                                                                            |
| `/usr`       | Вторичная иерархия для данных пользователя                                                                                 |

Более подробно про Unix см. в [@tanenbaum_book_modern-os_ru; @robbins_book_bash_en; @zarrelli_book_mastering-bash_en; @newham_book_learning-bash_en].

# Выполнение лабораторной работы

1. Выполнение git pull (см Рис 1)

![git pull](image/hgh.png){#fig:001 width=70%}    
git pull (рис 1)
2. Выполнение make (рис 2)

![Make](image/make.png){#fig:002 width=70%}    
Make (Рис 2)
3. Удаление файлов (Рис 3)

![Удаление файлов](image/delete.png){#fig:003 width=70%}    
Удаление файлов (Рис 3)

4. Открыть файл report.md (Рис 4)

![report.md](image/report md.png){#fig:004 width=70%}    
report.md (Рис 4)

5. Заполнить и скомплирировать отчет (см Рис 5)
![report mdd](image/report mdd.png){#fig:005 width=70%}    
report mdd (Рис 5)

6. Загрузить файлы в гитхаб (см Рис 6)
![


# Выводы

В процессе выполнения работы, я ознакомился с языком разметки Markdowrn.

# Список литературы{.unnumbered}

::: {#refs}
:::
