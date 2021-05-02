---
title: Как настроить Private Call DMR
date: 2019-03-05
guid: https://retevis.com.ua/?p=609
permalink: /ru/rt3s-privat-call/
teaser: /wp-content/uploads/2020/03/Знімок-екрана-2020-03-15-о-17.16.11.png
categories:
  - DMR рации
 tags:
  - RT3S
---
Retevis RT3S - двухдиапазонная DMR-радиостанция. Она поддерживает групповые и частные переговоры. Эта статья поможет вам выяснить, как осуществлять частный вызов на Retevis RT3S.

## Private Calls (приватный вызов)

Частный вызов (Private Call) - это звонок на определенный идентификатор DMR (DMR ID). Коммуникация является частной. Сообщение доступно для всех, кто слушает поток DMR или со станций DMR с идентичным DMR ID. При использовании станции Retevis RT3S у вас есть 3 способа осуществления частного вызова (Private Call) на RT3S.

### Первый метод: Private ID (частный идентификатор)
Первым методом можно вручную набрать частный идентификатор (private ID), выбрав в меню Контакт (Contact), выбрать Ручной набор (Manual Dial) и переключиться между групповым (Group) или частным идентификатором (Private ID).

![RT3S настройка контактов](/wp-content/uploads/2020/03/Private-call-on-RT3S-Cherry-169x300.jpg)

### Второй метод
Ви можете создать приватный канал в програмном обеспечении.

![RT3S privat call.](https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1.jpg)

Прежде всего вам нужно указать ваш **radio ID** и создать новый **new private call contact**.

![Retevis RT3s Privat Call](/wp-content/uploads/2020/03/Private-call-set-on-Retevis-RT3S-Cherry-169x300.jpg)
(
![RT3S privat call](/wp-content/uploads/2020/03/private-call-number-on-Retevis-RT3S-169x300.jpg)

Затем установите информацию о канале, частоту, выберите частный контакт, таймслот (time slot), color code, всю основную конфигурацию.

![Ретевис RT3S (приватный вызов)](/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting.jpg)

Следующий шаг, я думаю, самый важный - добавьте этот канал в зону, иначе вы не можете найти этот канал в радиостанции.

![RT3S zone](https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting.jpg)

Все настройки закончены. Запишите настройки в радиостанцию. Выберите канал и нажмите PTT. Теперь вы передаёте сигнал на частный ID.

### Третий способ
Добавьте новый цифровой канал в рацию. Для этого нужно поставить галочку (Program Radio) в программном обеспечении.

![RT3S вкл Program radio](/wp-content/uploads/2020/03/retevis-rt3s-program-radio-setting.jpg)

Если у вас возникли вопросы, пожалуйста, пишите их в комментариях.
