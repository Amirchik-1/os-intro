---
## Front matter
title: "Лабораторная работа №7"
subtitle: "Командная оболочка Midnight Commander"
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

Освоение основных возможностей командной оболочки Midnight Commander. Приоб-ретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

# Задание

Задание по mc
1. Изучите информацию о mc, вызвав в командной строке man mc.
2. Запустите из командной строки mc, изучите его структуру и меню
. Выполните несколько операций в mc, используя управляющие клавиши (операции
с панелями; выделение/отмена выделения файлов, копирование/перемещение фай-
лов, получение информации о размере и правах доступа на файлы и/или каталоги
и т.п.)
4. Выполните основные команды меню левой (или правой) панели. Оцените степень
подробности вывода информации о файлах.
5. Используя возможности подменю Файл , создайте католог и поработайте  с  ним. 
6. С помощью соответствующих средств Команда осуществите некоторые преобразования
7. Вызовите подменю Настройки . Освойте операции, определяющие структуру экрана mc
(Full screen, Double Width, Show Hidden Files и т.д.)

Задание по встроенному редактору mc

1. Создайте текстовой файл text.txt.
2. Откройте этот файл с помощью встроенного в mc редактора.
3. Вставьте в открытый файл небольшой фрагмент текста, скопированный из любого
другого файла или Интернета.
4. Проделайте с текстом некотрые манипуляции, используя горячие клавиши:
5. Откройте файл с исходным текстом на некотором языке программирования (напри-
мер C или Java)
6. Используя меню редактора, включите подсветку синтаксиса, если она не включена,
или выключите, если она включена.

# Выполнение лабораторной работы
 Задание по mc
 
1. Изучим информацию о mc, вызвав в командной строке man и mc.

![информацию о mc.](image/1.png){#fig:001 width=70%}

2. Запустим из командной строки mc, изучим его структуру и меню

![Изучаем структуру mc](image/2.png){#fig:002 width=70%}


3. Выполним несколько операций в mc, используя управляющие клавиши (операции
с панелями; выделение/отмена выделения файлов, копирование/перемещение фай-
лов, получение информации о размере и правах доступа на файлы и/или каталоги
и т.п.)

![ пару операций  с  mc ](image/3.png){#fig:003 width=70%}


4. Выполним основные команды меню левой панели.Оценим степень подробности вывода инфрмации о файлахю
 
![ Выполняем основные команды  ](image/4.png){#fig:004 width=70%}

5. используя возможности подменю Файл , выполним следующие действия.

![ Импользуем подменю Файл](image/5.png){#fig:005 width=70%}

6. С помощью соответствующих средств подменю Команда осуществим некотры команды.

![ работа с подменю Команда ](image/6.png){#fig:006 width=70%}

![ работа с подменю Команда ](image/61.png){#fig:061 width=70%}

![ работа с подменю Команда ](image/62.png){#fig:062 width=70%}

7. Вызовим подменю Настройки . Освоим операции, определяющие структуру экрана mc

![ работа с  подменю Настройки](image/7.png){#fig:007 width=70%}

![ работа с  подменю Настройки](image/71.png){#fig:071 width=70%}

Задание по встроенному редактору mc

8. Создадаим текстовой файл text.txt.

![Создайм файл text.txt. ](image/8.png){#fig:008 width=70%}


9. Откроем этот файл с помощью встроенного в mc редактора.
 
![открываем файл с помошью редактора ](image/9.png){#fig:009 width=70%}

10. Вставим в открытый файл небольшой фрагмент текста, скопированный из любого другого файла или Интернета

![ проделывем операции с файлом и текостом в нём ](image/10.png){#fig:010 width=70%}


11. Проделаем с текстом следующие манипуляции, используя горячие клавиши

![ работаем с созданным файлом ](image/11.png){#fig:011 width=70%}

12.  Откроем файл с исходным текстом на некотором языке программирования .

![открываем файл  ](image/11.png){#fig:011 width=70%}

13. Используя меню редактора, включим подсветку синтаксиса, если она не включена, или выключим, если она включена.

![ включим подсветку синтаксиса](image/11.png){#fig:011 width=70%}


# Выводы

Освоение основных возможностей командной оболочки Midnight Commander. Приоб-ретение навыков практической работы по просмотру каталогов и файлов; манипуляций с ними.

## Контрольные вопросы

1. Какие режимы работы есть в mc? Охарактеризуйте их.
В командной оболочке mc есть два режима Информация и Дерево. В режиме Информация на панель выводятся сведения о файле и текущей файловой системе, расположенных на активной панели. В режиме Дерево на одной из панелей выводится структура дерева каталогов. Управлять режимами отображения панелей можно через пункты меню mc

2. Какие операции с файлами можно выполнить как с помощью команд shell, так и с помощью меню mc? Командные интерпретатор Shell и оболочка Midnight Commander имеют похожую структуру и многие одинаковые команды можно выполнить в обоих оболочках вот некоторые из них:
a) Системная информация
b) Поиск
c) Копирование

3. Опишите структуру меню левой панели mc, дайте характеристику командам.
Меню левой панели mc представляет собой следующую конструкцию:
a) Список файлов показывает файлы в домашнем каталоге.
b) Быстрый просмотр позволяет выполнить быстрый просмотр содержимого панели.
с) Информация позволяет посмотреть информацию о файле или каталоге 
d) Командная оболочка Midnight Commander В меню каждой (левой или правой) панели можно выбрать Формат списка: стандартный, ускоренный, расширенный  и определённый пользователем.
e) Порядок сортировки позволяет задать критерии сортировки при выводе списка файлов и каталогов: без сортировки, по имени, расширенный, время правки, время доступа, время изменения атрибута, размер, узел.

4. Опишите структура меню Файл mc и дайте характеристику командам.
Меню Фаил mc представляет собой следующую конструкцию:
a) Просмотр ( F3 )  позволяет посмотреть содержимое текущего файла без возможности редактирования. 
b) – Просмотр вывода команды ( М + ! ) функция запроса команды с параметрами.
c) Правка ( F4 ) открывает текущий (или выделенный) файл для его редактирования. 
d) Копирование ( F5 ) осуществляет копирование одного или нескольких файлов или каталогов в указанное пользователем во всплывающем окне место. 
e) Права доступа ( Ctrl-x c ) позволяет изменить права доступа к одному или нескольким файлам или каталогам.
f)  Права доступа на файлы и каталоги 
g) Жёсткая ссылка ( Ctrl-x l ) позволяет создать жёсткую ссылку к текущему (или выделенному) файлу1 . 
h) Символическая ссылка ( Ctrl-x s ) — позволяет создать символическую ссылку к текущему файлу . 
i) Владелец группы ( Ctrl-x o ) позволяет задать владельца и имя группы для одного или нескольких файлов или каталогов. 
j) Права (расширенные)  позволяет изменить права доступа и владения для одного или нескольких файлов или каталогов. 
k) Переименование ( F6 ) позволяет переименовать один или несколько файлов или каталогов.
l) Создание каталога ( F7 ) позволяет создать каталог. 
m) Удалить ( F8 ) позволяет удалить один или несколько файлов или каталогов. 
n) Выход ( F10 )  завершает работу mc. 

5. Опишите структура меню Команда mc, дайте характеристику командам
Меню Команда mc представляет собой следующую конструкцию:
a) Дерево каталогов отображает структуру каталогов системы.
b) Поиск файла выполняет поиск файлов по заданным параметрам.
c) Переставить панели меняет местами левую и правую панели. 
d) Сравнить каталоги ( Ctrl-x d ) сравнивает содержимое двух каталогов. 
e) Размеры каталогов отображает размер и время изменения каталога (по умол- чанию в mc размер каталога корректно не отображается).
f) История командной строки выводит на экран список ранее выполненных в оболочке команд. 
g) Каталоги быстрого доступа ( Ctrl-\ ) при вызове выполняется быстрая смена текущего каталога на один из заданного списка. 
h) Восстановление файлов позволяет восстановить файлы на файловых систе- мах ext2 и ext3. 
i) Редактировать файл расширений позволяет задать с помощью определённого синтаксиса действия при запуске файлов с определённым расширением (напри- мер, какое программного обеспечение запускать для открытия или редактирова- ния файлов с расширением .c или .cpp). 
j) Редактировать файл меню позволяет отредактировать контекстное меню поль- зователя, вызываемое по клавише F2 . 
k) Редактировать файл расцветки имён позволяет подобрать оптимальную для пользователя расцветку имён файлов .
6. Опишите структура меню Настройки mc, дайте характеристику командам
Меню Настройки mc представляет собой следующую конструкцию:
a) Конфигурация позволяет скорректировать настройки работы с панелями. 
b) Внешний вид и Настройки панелей определяет элементы, отображаемые при вызове mc, а также цветовое выделение. 
c) Биты символов задаёт формат обработки информации локальным термина- лом. 
d) Подтверждение позволяет установить или убрать вывод окна с запросом подтверждения действий при операциях удаления и перезаписи файлов, а также при выходе из программы.
e) Распознание клавиш диалоговое окно используется для тестирования функциональных клавиш, клавиш управления курсором и прочее.
f) Виртуальные ФС настройки виртуальной файловой системы: тайм-аут, пароль и прочее.

7. Назовите и дайте характеристику встроенным командам mc.
В командную оболочку mc встроены стандартные команды. Вот некоторые из них.
a) F1 Вызов контекстно-зависимой подсказки.
b) F2 Вызов пользовательского меню с возможностью создания and/or.
c) F3 Просмотр содержимого файла, на который указывает подсветка в активной панели.
d) F4 Вызов встроенного в mc редактора для изменения содержания файла, на который указывает подсветка в активной панели.
d) F5 Копирование одного или нескольких файлов, отмеченных в первой (активной) панели, в каталог, отображаемый на второй панели.
e) F6 Перенос одного или нескольких файлов, отмеченных в первой панели, в каталог, отображаемый на второй панели.
f) F7 Создание подкаталога в каталоге, отображаемом в активной панели.
g) F8 Удаление одного или нескольких файлов, отмеченных в первой панели файлов.
h) Вызов меню mc.
i) F10 Выход из mc.

8. Назовите и дайте характеристику командам встроенного редактора mc.
В редактор mc встроено немало команд. Вот некоторые из них.
a) Ctrl+y удалить строку.
b) Ctrl+u отмена последней операции. 
c) Ins вставка/замена.
d)F7 поиск.
d)Shift+F7 повтор последней операции поиска.
e) F4 замена файла.
f) F3 первое нажатие начало выделения, второе это окончание выделения.
g) F5 копировать выделенный фрагмент F6 переместить выделенный фрагмент.
h) F8 удалить выделенный фрагмент.
i) F2 записать изменения в файл.
j) F10 выйти из редактора.

9. Дайте характеристику средствам mc, которые позволяют создавать меню, определяемые пользователем.
Один из четырех форматов списка в Midnight Commander -Пользовательский определённый самим пользователем позволяет ему редактировать меню любого из двух списков. А меню пользователя – это меню, состоящее из команд, определенных пользователем. При вызове меню используется файл ~/.mc.menu. Если такого файла нет, то по умолчанию используется системный файл меню /usr/lib/mc/mc.menu. Все строки в этих файлах  , начинающиеся с пробела или табуляции, являются командами, которые выполняются при выборе записи.

10. Дайте характеристику средствам mc, которые позволяют выполнять действия, определяемые пользователем, над текущим файлом
Когда мы выделяем файл не являющегося исполняемым, Midnight Commander сравнивает расширение выбранного файла с расширениями, прописанными в «файле расширений» ~/mc.ext. Если в файле расширений найдется подраздел, задающий процедуры обработки файлов с данным расширением, то обработка файла производится в соответствии с заданными в этом подразделе командами и файлами:
a) файл помощи для MC. /usr/lib/mc.hlp
b) файл расширений, используемый по умолчанию. /usr/lib/mc/mc.ext
c)  файл расширений, конфигурации редактора. $HOME/.mc.ext
d) системный инициализационный файл. /usr/lib/mc/mc.ini
e) фаил который содержит основные установки. /usr/lib/mc/mc.lib
g) инициализационный файл пользователя. Если он существует, то системный файл mc.ini игнорируется. $HOME/.mc.ini
h) этот файл содержит подсказки, отображаемые в нижней части экрана. /usr/lib/mc/mc.hint
i) системный файл меню MC, используемый по умолчанию. /usr/lib/mc/mc.menu
j) файл меню пользователя. Если он существует, то системный файл меню игнорируется. $HOME/.mc.menu
k) инициализационный файл пользователя. Если он существует, то системный файл mc.ini игнорируется. $HOME/.mc.tree

