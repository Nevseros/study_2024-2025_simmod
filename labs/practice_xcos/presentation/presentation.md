---
## Front matter
lang: ru-RU
title: Презентация по упражнению по xcos
subtitle: Имитационное моделирование
author:
  - Екатерина Канева, НФИбд-02-22
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 6 марта 2025

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
---

# Информация

## Докладчик

* Канева Екатерина Павловна
* студент группы НФИбд-02-22
* Российский университет дружбы народов
* [1132222004@rudn.ru](mailto:1132222004@rudn.ru)
* <https://nevseros.github.io/ru/>

# Вводная часть

## Цель

Познакомиться с xcos.

## Задания

Построить с помощью xcos фигуры Лиссажу со следующими параметрами:

1) A = B = 1, a = 2, b = 2, d = 0; pi/4; pi/2; 3pi/4;pi;
2) A = B = 1, a = 2, b = 4, d = 0; pi/4; pi/2; 3pi/4;pi;
3) A = B = 1, a = 2, b = 6, d = 0; pi/4; pi/2; 3pi/4;pi;
4) A = B = 1, a = 2, b = 3, d = 0; pi/4; pi/2; 3pi/4;pi.

# Выполнение работы

## Построение схемы

Для начала я запустила xcos, собрала схему из нужных блоков:

![Схема в xcos.](image/23.png){#fig:23 width=40%}

## Параметры блоков

Для блоков Gensin я задала следующие параметрыg:

![Параметры блока Gensin.](image/1.png){#fig:1 width=40%}

## Параметры блоков

Для блока Cscopxy ввела следующие параметры:

![Параметры блока Cscopxy.](image/2.png){#fig:2 width=30%}

## Построение

Запустила, получила следующий график:

![Кривая Лиссажу при b = 2, d = 0.](image/3.png){#fig:3 width=50%}

## Построение

![Кривая Лиссажу при b = 2, d = pi/4.](image/4.png){#fig:4 width=50%}

## Построение

![Кривая Лиссажу при b = 2, d = pi/2.](image/5.png){#fig:5 width=50%}

## Построение

![Кривая Лиссажу при b = 2, d = 3pi/4.](image/6.png){#fig:6 width=50%}

## Построение

![Кривая Лиссажу при b = 2, d = pi.](image/7.png){#fig:7 width=50%}

## Построение

![Кривая Лиссажу при b = 4, d = 0.](image/8.png){#fig:8 width=50%}

## Построение

![Кривая Лиссажу при b = 4, d = pi/4.](image/9.png){#fig:9 width=50%}

## Построение

![Кривая Лиссажу при b = 4, d = pi/2.](image/10.png){#fig:10 width=50%}

## Построение

![Кривая Лиссажу при b = 4, d = 3pi/4.](image/11.png){#fig:11 width=50%}

## Построение

![Кривая Лиссажу при b = 4, d = pi.](image/12.png){#fig:12 width=50%}

## Построение

![Кривая Лиссажу при b = 6, d = 0.](image/13.png){#fig:13 width=50%}

## Построение

![Кривая Лиссажу при b = 6, d = pi/4.](image/14.png){#fig:14 width=50%}

## Построение

![Кривая Лиссажу при b = 6, d = pi/2.](image/15.png){#fig:15 width=50%}

## Построение

![Кривая Лиссажу при b = 6, d = 3pi/4.](image/16.png){#fig:16 width=50%}

## Построение

![Кривая Лиссажу при b = 6, d = pi.](image/17.png){#fig:17 width=50%}

## Построение

![Кривая Лиссажу при b = 3, d = 0.](image/18.png){#fig:18 width=50%}

## Построение

![Кривая Лиссажу при b = 3, d = pi/4.](image/19.png){#fig:19 width=50%}

## Построение

![Кривая Лиссажу при b = 3, d = pi/2.](image/20.png){#fig:20 width=50%}

## Построение

![Кривая Лиссажу при b = 3, d = 3pi/4.](image/21.png){#fig:21 width=50%}

## Построение

![Кривая Лиссажу при b = 3, d = pi.](image/22.png){#fig:22 width=50%}

# Заключение

## Вывод

Познакомилась с xcos, построив простейшие примеры.