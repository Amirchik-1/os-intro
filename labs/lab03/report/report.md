---
## Front matter
title: "Лабораторная работа №3"
subtitle: "Архитектура вычислительных систем"
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
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Научиться оформлять отчёты с помощью легковесного языка разметки Markdown.

# Задание

– Сделайте отчёт по предыдущей лабораторной работе в формате Markdown.
– В качестве отчёта просьба предоставить отчёты в 3 форматах: pdf, docx и md 


# Выполнение лабораторной работы

1. Базовая настройка git так же настроим  utf-8 в выводе сообщений git. Зададим имя начальной ветки (будем называть её master). 

![Базовая настройка git](image/1.png){#fig:001 width=70%}



2. Создадим ключ SSH.По алгоритму rsa с ключём размером 4096 бит.По алгоритму ed25519

![ Создадим ключ SSH](image/2.png){#fig:002 width=70%}


 
3. Создам ключ pgp.Генерируем ключ.

 
![ Создадим ключ SSH](image/3.png){#fig:003 width=70%} 



4. Добавляем PGP ключа в  GitHub

 
![Добавляем PGP ключа в  GitHub](image/4.png){#fig:004 width=70%} 


 
5.Настройка автоматических подписей коммитов git 


![ Настройка автоматических подписей коммитов git](image/8.png){#fig:005 width=70%}


 
 6. Создадаим репозиторий курса на основе шаблона 
 
 
![ создадаим репозиторий курса ](image/5.png){#fig:006 width=70%}


 
 7. Настроим католог курса .
 
 

![ настраиваем католог курса ](image/6.png){#fig:007 width=70%}


# Выводы

Я научился оформлять отчёты с помошью легковесного языка разметки  Markdown. Сделал отчёты по предедущей лабораторной работе .


