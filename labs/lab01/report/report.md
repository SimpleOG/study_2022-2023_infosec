---
# Front matter
lang: ru-RU
title: "Отчёт по лабораторной работе №1"
subtitle: "Развертывание виртуальной машины"
author: ""

# Formatting
toc-title: "Содержание"
toc: true # Table of contents
toc_depth: 2
lof: true # List of figures
fontsize: 12pt
linestretch: 1.5
papersize: a4paper
documentclass: scrreprt
polyglossia-lang: russian
polyglossia-otherlangs: english
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase
indent: true
pdf-engine: lualatex
header-includes:
  - \linepenalty=10 # the penalty added to the badness of each line within a paragraph (no associated penalty node) Increasing the value makes tex try to have fewer lines in the paragraph.
  - \interlinepenalty=0 # value of the penalty (node) added after each line of a paragraph.
  - \hyphenpenalty=50 # the penalty for line breaking at an automatically inserted hyphen
  - \exhyphenpenalty=50 # the penalty for line breaking at an explicit hyphen
  - \binoppenalty=700 # the penalty for breaking a line at a binary operator
  - \relpenalty=500 # the penalty for breaking a line at a relation
  - \clubpenalty=150 # extra penalty for breaking after first line of a paragraph
  - \widowpenalty=150 # extra penalty for breaking before last line of a paragraph
  - \displaywidowpenalty=50 # extra penalty for breaking before last line before a display math
  - \brokenpenalty=100 # extra penalty for page breaking after a hyphenated line
  - \predisplaypenalty=10000 # penalty for breaking before a display
  - \postdisplaypenalty=0 # penalty for breaking after a display
  - \floatingpenalty = 20000 # penalty for splitting an insertion (can only be split footnote in standard LaTeX)
  - \raggedbottom # or \flushbottom
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Выполнил работу:
Гаглоев Олег НПИбд-01-20

# Цели и задачи работы

## Цель лабораторной работы

Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.

# Процесс выполнения лабораторной работы

## Создаю виртуальную машину

![Создание новой виртуальной машины](../Img/0.png)

## Задаю конфигурацию оперативной памяти

![Конфигурация оперативной памяти](../Img/0_1.png)

## Задаю конфигурацию жёсткого диска

![Выделение памяти ](../Img/0001.png)

## Добавляю новый привод оптических дисков и выбираю образ

![Конфигурация системы](../Img/00001.png)

## Установка системы

#### Устанавливаю devtools 

![Установка devtools](../Img/2.png)

#### Отключаю kdump

![Отключение kdump](../Img/1.png)

#### Настраиваю подключение

![Подключение](../Img/3.png)

#### Выбираю пароль

![Пароль](../Img/4.png)

#### Устанавливаю систему

![Установка](../Img/5.png)

## Запуск ВМ

#### Устанавливаю образ диска дополнений гостевой ОС 

![Установка гостевого образа диска](../Img/6.png)

#### Просматриваю вывод dmesg| less

![Вывод команды ](../Img/7.png)

## Задания:
1. Версия ядра Linux (Linux version).
![Версия ядра Linux (Linux version)](../Img/8.png)

2. Частота процессора (Detected Mhz processor).
![Частота процессора](../Img/9.png)

3. Модель процессора (CPU0).
![Модель процессора](../Img/10.png)

4. Объем доступной оперативной памяти (Memory available).
![Объем доступной оперативной памяти (Memory available)](../Img/11.png)

![](../Img/12.png)

5. Тип обнаруженного гипервизора (Hypervisor detected).
![Тип обнаруженного гипервизора (Hypervisor detected)](../Img/13.png)

6. Тип файловой системы корневого раздела.
![Тип файловой системы корневого раздела](../Img/14.png)

7. Последовательность монтирования файловых систем.
![Последовательность монтирования файловых систем](../Img/15.png)


# Вывод

Приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов прошло успешно
