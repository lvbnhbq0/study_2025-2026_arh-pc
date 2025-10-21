## Front matter
title: "Отчёт по лабораторной работе №3"
subtitle: "дисциплина: Архитектура компьютера"
author: "Нестерова Дарья Антоновна"

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

Целью данной лабораторной работы является освоение процедуры оформления отчетов с помощью легковесного языка разметки Markdown.



# Выполнение лабораторной работы

## Компиляция шаблонов отчета

В терминале перехожу в директорию курса, обновляю репозиторий с удаленного на GitHub. (рис. -@fig:001)

![Обновление изменений в директории курса](image/1.png){#fig:001 width=50%}

Провожу компиляцию шаблона с помощью команды make (рис. -@fig:002), проверяю корректность исполнения команды (рис. -@fig:003)

![Компиляция шаблона](image/2.png){#fig:002 width=50%}

![Проверка](image/3.png){#fig:003 width=50%}

После проверки работоспособности компилятора шаблонов, я удаляю сгенерированные файлы с помощью команды make clean (рис. -@fig:004), проверяю корректность исполенения команды (рис. -@fig:005)

![Удаление сгенерированных шаблонов](image/4.png){#fig:004 width=50%}

![Проверка](image/5.png){#fig:005 width=50%}

Открываю файл report.md c помощью любого текстового редактора (geditС, предварительно установив его) (рис. -@fig:006), с помощью редактора выполняю отчет по выполненной лабораторной работе (рис. -@fig:007)

![Файл](image/6.png){#fig:006 width=50%}

![Подготовка отчёта](image/7.png){#fig:007 width=50%}

Дополнительно: в ходе работы мне было необходимо установить tinytex, что я и делаю (рис. -@fig:009)

![Установка tinytex](image/9.png){#fig:009 width=50%}

Загружаю файлы на Github (рис. -@fig:0010)

![Загрузка файлов](image/10.png){#fig:0010 width=50%}

## Задания для самостоятельной работы

Аналогично выполнению отчета по текущей лабораторной работе, я выполняю отчет в markdown и по второй лабораторной работе, для этого перехожу в директорию 2 лабораторной работы и готовлю отчет с помощью текстового редактора tinytex. (рис. -@fig:008)

![Выполнение отчета по 2 лабораторной работе](image/8.png){#fig:008 width=50%}

Загружаю файлы на Github (рис. -@fig:0011)

![Загрузка файлов](image/11.png){#fig:0011 width=50%}

# Выводы

Выполнение данной лабораторной работы позволило мне освоить методику оформления отчетов с применением языка разметки Markdown.

# Список литературы

1. [Курс на ТУИС](https://esystem.rudn.ru/course/view.php?id=112)
2. [Лабораторная работа №3](https://esystem.rudn.ru/pluginfile.php/2089083/mod_resource/content/0/%D0%9B%D0%B0%D0%B1%D0%BE%D1%80%D0%B0%D1%82%D0%BE%D1%80%D0%BD%D0%B0%D1%8F%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%B0%20%E2%84%963.%20%D0%AF%D0%B7%D1%8B%D0%BA%20%D1%80%D0%B0%D0%B7%D0%BC%D0%B5%D1%82%D0%BA%D0%B8%20.pdf)
3. [Пример выполнения лабораторной работы](https://github.com/evdvorkina/study_2022-2023_arh-pc/blob/master/labs/lab04/report/%D0%9B04_%D0%94%D0%B2%D0%BE%D1%80%D0%BA%D0%B8%D0%BD%D0%B0_%D0%BE%D1%82%D1%87%D0%B5%D1%82.md?plain=1)
