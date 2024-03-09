---
## Front matter
title: "Лабораторная работа № 4"
subtitle: ""
author: "Лисовская Арина Валерьевна"

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

Получение навыков правильной работы с репозиториями git.

# Задание
Выполнить работу для тестового репозитория.
Преобразовать рабочий репозиторий в репозиторий с git-flow и conventional commits.


# Выполнение лабораторной работы

Установка git-flow (рис. [-@fig:001]).

![git-flow](image/msg857167450-196327.jpg){#fig:001 width=70%}

добавим каталог с исполняемыми файлами, устанавливаемыми yarn, в переменную PATH (рис. [-@fig:002]).

![Настройка Node.js](image/msg857167450-196327(1).jpg){#fig:002 width=70%}

Созда. репозиторий на GitHub. Для примера назовём его git-extended.
Делаем первый коммит и выкладываем на github (рис. [-@fig:003])

![новый репозиторий](image/msg857167450-196329.jpg){#fig:003 width=70%}

заполняем несколько параметров пакета (рис. [-@fig:004])

![заполняем](image/msg857167450-196330.jpg){#fig:004 width=70%}

Сконфигурим формат коммитов. Для этого добавим в файл package.json команду для формирования коммитов (рис. [-@fig:005])

![заполняем](image/msg857167450-196328.jpg){#fig:005 width=70%}

Конфигурация git-flow (рис. [-@fig:006])

![кофигурация](image/msg857167450-196331.jpg){#fig:006 width=70%}

Создадим релиз с версией 1.2.3 (рис. [-@fig:007])

![релиз](image/msg857167450-196331.jpg){#fig:007 width=70%}

Зальём релизную ветку в основную ветку (рис. [-@fig:008])

![переделываем](image/msg857167450-196332.jpg){#fig:008 width=70%}

Отправим данные на github (рис. [-@fig:009])

![отпраляем](image/msg857167450-196333.jpg){#fig:009 width=70%}

# Выводы

Я научилась создавать и работать с репозиторием

# Список литературы{.unnumbered}

::: {#refs}
:::
