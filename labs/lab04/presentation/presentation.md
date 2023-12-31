---
## Front matter
lang: ru-RU
title: Дискреционное разграничение прав в Linux. Расширенные атрибуты
author: |
	 Гаглоев Олег Мелорович\inst{1}

institute: |
	\inst{1}Российский Университет Дружбы Народов

date: 30 сентября, 2023, Москва, Россия

## Formatting
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
toc: false
slide_level: 2
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true

---

# Цели и задачи работы

## Цель лабораторной работы

Получение практических навыков работы в консоли с расширенными атрибутами файлов.

# Процесс выполнения лабораторной работы

## Теоретическое введение

Помимо прав доступа каждый из файлов стандартной файловой системы Linux имеет набор атрибутов, регламентирующих особенности работы с ним. Chattr - это команда в Linux,
которая позволяет пользователю устанавливать и снимать определенные атрибуты файла. Доступны следующие атрибуты: a, A, c, C, D, e, i, j, s, S, t, u.

## Проверка атрибутов папки

![Атрибуты](../img/1.png)

## Расширенный атрибут a

![Атрибут а](../img/5.png)

## Работа с атрибутом 

![Атрибут а, запреты](../img/8.png)

## Работа с атрибутом 

![Атрибут а, возможности](../img/6.png)


## Расширенный атрибут i

![Проверка атрибута](../img/12.png)

## Работа с атрибутом 

![Возможности](../img/14.png)

## Вывод

Получены практические навыки работы в консоли с расширенными атрибутами файлов.
