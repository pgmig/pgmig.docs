---
title: "PgMig"
description: "PG Mig"
date: 2021-10-07T14:23:34+03:00
draft: false
landing:
  height: 530
  title:
    - Postgresql Migrator
  text:
  -  Миграции БД postgresql для разработчиков хранимого кода
  titleColor:
  textColor:
  spaceBetweenTitleText: 25
  buttons:
    - link: https://github.com/pgmig/pgmig
      text: GitHub
      color: primary
    - link: https://github.com/topics/pgmig-used
      text: Кто использует
      color: primary
    - link: docs
      text: Документация
      color: default
sections:
  - bgcolor: \#49a1e4

    type: card
    description: "PgMig предназначен для разработчиков хранимого кода Postgresql, которым нужны миграции БД, в которых
    <ul><li>1. изменения выполняются в одной транзакции загрузкой исходного кода из файлов в алфавитном порядке их имен
    <li>2. имена файлов с хранимым кодом и его тестами имеют заданную маску и они выполняются при любом изменении
    <li>3. для отката от версии Б к версии А достаточно иметь содержимое БД (версии Б) и исходники версии А
    <li>4. номер версии БД может определяется по git-атрибутам загружаемого исходного кода
    <li>5. история изменений хранимого кода контролируется git
    </ul>"
    header: 
      title: Преимущества pgmig
      hlcolor: DarkKhaki #"#8bc34a"
      color: landing-button-primary
      fontSize: 32
      width: 360
---
