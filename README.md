<p align="center">
  <img src='misc/pereval_logo.png'/>
</p>

# The Pereval server

_In develompent_

## Описание

**Перевал** - это сборка настроенных web-сервисов, которую можно развернуть на локальном или удалённом сервере. Сервисы предназначены для совместной деятельности небольших групп людей в области поиска, сбора, анализа и хранения информации. 

## Запуск

1. Установить Docker и Docker Compose
1. Склонировать репозиторий и развернуть сервер:
```
git clone https://github.com/pereval-team/pereval-server.git
cd pereval-server && sudo docker-compose up --build
```

## Сервисы

- [OSINT](#OSINT)

  - [Анализ](#Анализ)

  - [Поиск](#Поиск)

- [Записи](#Записи)

  - [Текст](#Текст)

  - [Таблицы](#Таблицы)

  - [Схемы](#Схемы)

- [Архивирование](#Архивирование)

  - [Ссылки](#Ссылки)

  - [Веб-контент](#Веб-контент)

  - [Файлы](#Файлы)

- [Централизация](#Централизация)

### OSINT

К сервисам для OSINT (Open source intelligence, разведка на основе открытых источников) отнесены веб-приложения, позволяющие искать информацию через API других сервисов, путём сканирования URL и IP, а также веб-приложения для анализа данных.

#### Поиск

- IVRE

- Spiderfoot

- Intrigue

- Openwebspider

#### Анализ

- CyberChef

### Записи

#### Текст 

#### Таблицы

#### Схемы

### Архивирование

#### Ссылки

#### Веб-контент

#### Файлы

### Централизация