---
## Front matter
lang: ru-RU
title: Презентация лабораторной работы №6
subtitle: "Мандатное
разграничение прав в Linux"
author:
  - Тасыбаева Н.С.
institute:
  - Российский университет дружбы народов, Москва, Россия
date: 14 октября 2023

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
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Цели и задачи работы


Развить навыки администрирования ОС Linux. Получить первое практическое знакомство с технологией SELinux1.
Проверить работу SELinx на практике совместно с веб-сервером
Apache.

## Результаты

![Запуск сервера](image/0.png){#fig:001 width=70%}

## Результаты

![Параметр ServerName](image/1.png){#fig:002 width=70%}

## Результаты

![Команды getenforce и sestatus. Запуск apache](image/1_2.png){#fig:003 width=70%}

## Результаты

![Контест безопасности и Cостояние переключателей SELinux](image/3_4.png){#fig:004 width=70%}

## Результаты

![Статистика по политике](image/5.png){#fig:005 width=70%}

## Результаты

![Типы файлов и поддиректории](image/6_10.png){#fig:006 width=70%}

## Результаты

![Запуск в браузере](image/11.png){#fig:007 width=70%}

## Результаты

![Изменение контеста безопасности](image/13.png){#fig:008 width=70%}

## Результаты

![Запуск в браузере с ошибкой](image/14.png){#fig:009 width=70%}

## Результаты

![Лог файлы](image/15_16.png){#fig:010 width=70%}

## Результаты

![Настройки](image/18_20.png){#fig:011 width=70%}

## Результаты

![Запуск в браузере](image/21.png){#fig:012 width=70%}

## Результаты

![Открытие файла](image/21_24.png){#fig:013 width=70%}

# Выводы по проделанной работе

Я изучила механизмы изменения идентификаторов, применения SetUID- и Sticky-битов, получила практические навыки работы в консоли с дополнительными атрибутами. Рассмотрела работу механизма смены идентификатора процессов пользователей, а также влияние бита Sticky на запись и удаление файлов.
