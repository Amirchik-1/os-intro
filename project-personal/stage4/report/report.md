---
## Front matter
title: "Индивидуальный проект "
subtitle: "Четвёртый этап"
author: "Зарифбеков Амир Пайшанбиевич"

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

Научиться добовлять к сайту ссылку на научные и бибилиометрические ресурсы

# Задание

Зарегестрироватьтся на сайтах 
Создать отчёт по прошедшей неделе 
Сделать отчйт на выбранную тему 



# Выполнение лабораторной работы

1. регестрируемся на чайтах котрые даны нам в задании 

![сайты ](image/1.png){#fig:001 width=90%}

![как мы это сделали](image/2.png){#fig:002 width=90%}

2. Сделал пост по прошедшей неделе 

![как мы делали это в индекс.мд](image/3.png){#fig:003 width=90%}

![как это выглядит на сайте](image/4.png){#fig:004 width=90%}

3. Сделаю пост по теме работа с библиографией

![как мы делали это в индекс.мд](image/5.png){#fig:005 width=70%}

![как это выглядит на сайте](image/6.png){#fig:006 width=70%}


# Выводы

Я научился добовлять к сайту ссылку на научные и бибилиометрические ресурсы и приобрёл практические навыки


