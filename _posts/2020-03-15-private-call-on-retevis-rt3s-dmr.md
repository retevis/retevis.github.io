---
id: 505
title: 'RT3S: Як здійснити приватний виклик DMR (private call)'
date: 2020-03-15T14:54:08+00:00
author: Retevis Україна
layout: post
guid: http://54.93.109.229/?p=505
permalink: /private-call-on-retevis-rt3s-dmr/
ap_mark:
  - Это пост был добавлен через AftParser
ap_link:
  - https://blog.retevis.com/index.php/how-to-do-private-call-on-retevis-rt3s/
image: /wp-content/uploads/2020/03/Знімок-екрана-2020-03-15-о-17.16.11.png
categories:
  - Цифрові рації
---
[Retevis RT3S](https://retevis.com.ua/shop/retevis-rt3s/) &#8211; дводіапазонна радіостанція DMR. Вона підтримує групові та приватні дзвінки. Ця стаття допоможе вам з&#8217;ясувати, як здійснювати приватний виклик на Retevis RT3S.



### Private Calls (приватні виклики)

Приватний виклик (Private Call) &#8211; це дзвінок на певний ідентифікатор DMR (DMR ID). Комунікація є приватною. Повідомлення доступне для всіх, хто слухає потік DMR або зі станцією DMR з ідентичним програмованим ідентифікатором DMR. Під час використання станції Retevis RT3S у вас є 3 способи здійснення приватного дзвінка на RT3S.

  1. Першим методом ви можете вручну набрати приватний ідентифікатор (private ID), вибравши в меню Контакт (**Contact)**, вибрати Ручний набір (**Manual Dial)**&nbsp;і переключитися між груповим (Group) або приватним ідентифікатором (Private ID)

<img loading="lazy" class="aligncenter wp-image-596 size-medium" src="https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-on-RT3S-Cherry-169x300.jpg" alt="RT3S налаштування контактів" width="169" height="300" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-on-RT3S-Cherry-169x300.jpg 169w, https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-on-RT3S-Cherry.jpg 338w" sizes="(max-width: 169px) 100vw, 169px" /> 

2. Другий метод, Ви можете створити приватний канал у програмному забезпеченні.

<img loading="lazy" class="aligncenter wp-image-598 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1.jpg" alt="RT3S privat call. Створити приватний канал" width="695" height="241" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1.jpg 695w, https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1-300x104.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1-600x208.jpg 600w" sizes="(max-width: 695px) 100vw, 695px" /> 

Перш за все вам потрібно вказати ваш&nbsp;**radio ID**&nbsp; та створити новий&nbsp;**new private call contact**.

<img loading="lazy" class="size-medium wp-image-599 aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-set-on-Retevis-RT3S-Cherry-169x300.jpg" alt="Retevis RT3s Privat Call" width="169" height="300" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-set-on-Retevis-RT3S-Cherry-169x300.jpg 169w, https://retevis.com.ua/wp-content/uploads/2020/03/Private-call-set-on-Retevis-RT3S-Cherry.jpg 338w" sizes="(max-width: 169px) 100vw, 169px" /> 

<img loading="lazy" class="size-medium wp-image-600 aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/private-call-number-on-Retevis-RT3S-169x300.jpg" alt="RT3S privat call (приватний виклик)" width="169" height="300" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/private-call-number-on-Retevis-RT3S-169x300.jpg 169w, https://retevis.com.ua/wp-content/uploads/2020/03/private-call-number-on-Retevis-RT3S.jpg 338w" sizes="(max-width: 169px) 100vw, 169px" /> 

Потім встановіть інформацію про канал, частоту, виберіть приватний контакт, таймслот (time slot), color code, всю основну конфігурацію.

<img loading="lazy" class="aligncenter wp-image-602 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting.jpg" alt="Ретевис RT3S (приватный вызов)" width="939" height="501" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting.jpg 939w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting-300x160.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting-768x410.jpg 768w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting-600x320.jpg 600w" sizes="(max-width: 939px) 100vw, 939px" /> 

Наступний крок, я думаю, найважливіший &#8211; додайте цей канал у зону, інакше ви не можете знайти цей канал у радіостанції.

<img loading="lazy" class="aligncenter wp-image-603 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting.jpg" alt="RT3S вибрати зону" width="909" height="221" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting.jpg 909w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting-300x73.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting-768x187.jpg 768w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-zone-setting-600x146.jpg 600w" sizes="(max-width: 909px) 100vw, 909px" /> 

Усі налаштування закінчені. Запишіть налаштування на радіо. Увімкніть цей канал і натисніть PTT. Тепер ви передасте сигнал на приватний ідентифікатор.

Третій спосіб, додайте новий цифровий канал на радіо. Для цього потрібно поставити галочку &#8220;Програмне радіо&#8221; (Program Radio) в програмному забезпеченні.

<img loading="lazy" class="wp-image-604 size-full aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-program-radio-setting.jpg" alt="RT3S увімкнути Program radio" width="593" height="391" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-program-radio-setting.jpg 593w, https://retevis.com.ua/wp-content/uploads/2020/03/retevis-rt3s-program-radio-setting-300x198.jpg 300w" sizes="(max-width: 593px) 100vw, 593px" /> 

Якщо у вас виникли питання &#8211; будь-яка пишіть їх у коментарях.

<div>
  <div>
  </div>
</div>