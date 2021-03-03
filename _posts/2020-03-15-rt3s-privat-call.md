---
id: 609
title: 'RT3S: Как настроить Private Call DMR'
date: 2020-03-15T14:54:08+00:00
author: Retevis Україна
layout: post
guid: https://retevis.com.ua/?p=609
permalink: /ru/rt3s-privat-call/
ap_mark:
  - Это пост был добавлен через AftParser
ap_link:
  - https://blog.retevis.com/index.php/how-to-do-private-call-on-retevis-rt3s/
image: /wp-content/uploads/2020/03/Знімок-екрана-2020-03-15-о-17.16.11.png
categories:
  - DMR рации
---
[Retevis RT3S](https://retevis.com.ua/shop/retevis-rt3s/) &#8211; двухдиапазонная DMR-радиостанция. Она поддерживает групповые и частные переговоры. Эта статья поможет вам выяснить, как осуществлять частный вызов на Retevis RT3S.



### Private Calls (приватный вызов)

Частный вызов (Private Call) &#8211; это звонок на определенный идентификатор DMR (DMR ID). Коммуникация является частной. Сообщение доступно для всех, кто слушает поток DMR или со станций DMR с идентичным DMR ID. При использовании станции Retevis RT3S у вас есть 3 способа осуществления частного вызова (Private Call)&nbsp;на RT3S.

Первым методом можно вручную набрать частный идентификатор (private ID), выбрав в меню Контакт (Contact), выбрать Ручной набор (Manual Dial) и переключиться между групповым (Group) или частным идентификатором (Private ID)

<img loading="lazy" class="aligncenter wp-image-596 size-medium" src="https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-on-RT3S-Cherry-169x300.jpg" alt="RT3S налаштування контактів" width="169" height="300" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-on-RT3S-Cherry-169x300.jpg 169w, https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-on-RT3S-Cherry.jpg 338w" sizes="(max-width: 169px) 100vw, 169px" /> 

2. Второй метод: Ви можете создать приватный канал в програмном обеспечении.

<img loading="lazy" class="aligncenter wp-image-598 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1.jpg" alt="RT3S privat call. Створити приватний канал" width="695" height="241" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1.jpg 695w, https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1-300x104.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1-600x208.jpg 600w" sizes="(max-width: 695px) 100vw, 695px" /> 

Прежде всего вам нужно указать ваш **radio ID** и создать новый **new private call contact**.

<img loading="lazy" class="size-medium wp-image-599 aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-set-on-Retevis-RT3S-Cherry-169x300.jpg" alt="Retevis RT3s Privat Call" width="169" height="300" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-set-on-Retevis-RT3S-Cherry-169x300.jpg 169w, https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-set-on-Retevis-RT3S-Cherry.jpg 338w" sizes="(max-width: 169px) 100vw, 169px" /> 

<img loading="lazy" class="size-medium wp-image-600 aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/private-call-number-on-Retevis-RT3S-169x300.jpg" alt="RT3S privat call (приватний виклик)" width="169" height="300" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/private-call-number-on-Retevis-RT3S-169x300.jpg 169w, https://retevis.com.ua/wp-content/uploads/2020/03/private-call-number-on-Retevis-RT3S.jpg 338w" sizes="(max-width: 169px) 100vw, 169px" /> 

Затем установите информацию о канале, частоту, выберите частный контакт, таймслот (time slot), color code, всю основную конфигурацию.

<img loading="lazy" class="aligncenter wp-image-602 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting.jpg" alt="Ретевис RT3S (приватный вызов)" width="939" height="501" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting.jpg 939w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting-300x160.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting-768x410.jpg 768w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting-600x320.jpg 600w" sizes="(max-width: 939px) 100vw, 939px" /> 

Следующий шаг, я думаю, самый важный &#8211; добавьте этот канал в зону, иначе вы не можете найти этот канал в радиостанции.

<img loading="lazy" class="aligncenter wp-image-603 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting.jpg" alt="RT3S вибрати зону" width="909" height="221" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting.jpg 909w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting-300x73.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting-768x187.jpg 768w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting-600x146.jpg 600w" sizes="(max-width: 909px) 100vw, 909px" /> 

Все настройки закончены. Запишите настройки в радиостанцию. Выберите канал и нажмите PTT. Теперь вы передаёте сигнал на частный ID.

Третий способ, добавьте новый цифровой канал в рацию. Для этого нужно поставить галочку (Program Radio) в программном обеспечении.

<img loading="lazy" class="wp-image-604 size-full aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-program-radio-setting.jpg" alt="RT3S увімкнути Program radio" width="593" height="391" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-program-radio-setting.jpg 593w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-program-radio-setting-300x198.jpg 300w" sizes="(max-width: 593px) 100vw, 593px" /> 

Если у вас возникли вопросы &#8211; пожалуйста пишите их в комментариях.

<div>
  <div>
  </div>
</div>