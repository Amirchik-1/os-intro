---
## Front matter
title: "Лабораторная работа №9"
subtitle: "Текстовой редактор emacs "
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

Познакомиться с операционной системой Linux. Получить практические навыки рабо-
ты с редактором Emacs.

# Задание

1. Ознакомиться с теоретическим материалом.
2. Ознакомиться с редактором emacs.
3. Выполнить упражнения.
4. Ответить на контрольные вопросы.


# Выполнение лабораторной работы

1.  открываем emacs

![создаём католог](image/1.png){#fig:001 width=70%}

2.Создаём файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f)

![ перейдём к созданный католог](image/2.png){#fig:002 width=70%}


3. Набираем в редактор данный нам текст.

![ вызовим vi ](image/3.png){#fig:003 width=70%}


4. Сохраняю файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s).
 
![ введём текст ](image/4.png){#fig:004 width=70%}

5. Проделаю с текстом стандартные процедуры редактирования.

![ вводим двоеточие](image/5.png){#fig:005 width=70%}

6. Научился использовать команды по перемещению курсора.

![ запишем и сохраним ](image/6.png){#fig:006 width=70%}


7. Работем с управлениями буфера

![ делаем файл исполняемым ](image/7.png){#fig:007 width=70%}

8. Работаем с управлениями окнами

![ делаем файл исполняемым ](image/8.png){#fig:008 width=70%}

9. Учимся управлять режимом поиска

![ делаем файл исполняемым ](image/9.png){#fig:009 width=70%}

#Контрольные вопросы

Emacs представляет собой мощный экранный редактор текста, написанный на языке высокого уровня Elisp.
    Развитие Emacs в сторону его многогранности послужило причиной того, что и без того интуитивно непонятная программа стала чрезвычайно сложной в применении. В частности, управление осуществляется при помощи различных клавиатурных комбинаций, запомнить которые будет непросто.
    Буфер – что-то, состоящее из текста. Окно – область с одним из буферов.
    В одном окне можно открыть больше 10 буферов.
    После запуска emacs без каких-либо параметров в основном окне отображается буфер scratch, который используется для оценки выражений Emacs Lisp, а также для заметок, которые вы не хотите сохранять. Этот буфер не сохраняется автоматически.
    Чтобы ввести следующую комбинацию C-c | я нажму клавиши: Control+c и Shift+, и для C-c C-|: Control+c и Control+Shift+.
    Поделить текущее окно на две части можно двумя комбинациями клавиш: C-x 3 или C-x 2.
    Настроить или расширить Emacs можно написав или изменив файл ~/.emacs.
    Клавиша  выполняет функцию перемещения курсора в открытом окне также, как и многие другие клавиши её можно переназначить.
    Редактор emacs показался мне удобнее из-за возможности открытия нескольких окон с буферами и работать комбинациями клавиш в этот редакторе мне было проще.

# Выводы

Познакомился с операционной системой Linux. Получил практические навыки рабо-
ты с редактором Emacs.



