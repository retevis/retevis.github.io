---
id: 399
title: Як у Retevis RT3S працює функція GPS?
date: 2020-03-14T05:25:00+00:00
author: Retevis Україна
layout: post
guid: http://54.93.109.229/?p=399
permalink: /retevis-rt3s-gps-switch-on/
ap_mark:
  - Это пост был добавлен через AftParser
ap_link:
  - https://blog.retevis.com/index.php/how-rt3s-gps-function-works/
wpglobus_language:
  - ru
image: /wp-content/uploads/2020/03/Check-RT3S-GPS-information.jpg
categories:
  - Цифрові рації
tags:
  - RT3S
---
GPS глобальна система позиціонування &#8211; це супутникова навігаційна система, що використовується для визначення наземного положення об&#8217;єкта. DMR рація Retevis RT3S з функцією GPS може визначати вашу позицію за допомогою супутника і отримувати GPS-інформацію від інших радіостанцій. Давайте розберемось, як працює ця функція.

<img loading="lazy" class="aligncenter wp-image-400 size-large" src="http://54.93.109.229/wp-content/uploads/2020/03/RT3S-GPS--578x1024.jpg" alt="" width="578" height="1024" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--578x1024.jpg 578w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--169x300.jpg 169w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--768x1360.jpg 768w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--867x1536.jpg 867w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--600x1063.jpg 600w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS-.jpg 1080w" sizes="(max-width: 578px) 100vw, 578px" /> 

## Що вам потрібно?

  1. Купити радіостанцію Retevis RT3S в [авторизованому магазині Retevis](https://retevis.com.ua/shop/retevis-rt3s-dmr/).
  2. Скачати програмне забезпечення для Retevis RT3S&nbsp;з [ресурсного центру](https://www.retevis.com/resources-center/) на офіційному сайті.
  3. Купити [кабель програмування](http://54.93.109.229/shop/special-retevis-usb-programming-cable-for-retevis-rt3-rt8-rt3s-rt52-for-tyt-md-380-md-390-md-380-dmr-radio-walkie-talkie-j9110p/).

## Як налаштувати RT3S GPS в програмному забезпеченні?

  1. По-перше, відкрийте програмне забезпечення та у пункті &#8220;menu item&#8221; поставте галочку &#8220;GPS&#8221;.

<img loading="lazy" class="aligncenter wp-image-6531 size-full" title="How does Retevis RT3S Digital radio GPS function works?" src="http://blog.retevis.com/wp-content/uploads/2018/10/RT3S-GPS-1.jpg" alt="" width="822" height="386" /> <span style="font-size: inherit;"><br /> 2. Створіть один канал, який потрібно використовувати з функцією GPS. Важливо поставити галочки навпроти &#8221; відправити дані GPS&#8221; і &#8220;отримувати дані GPS&#8221; та вибрати одну систему GPS.</span>

<img loading="lazy" class="aligncenter wp-image-6532 size-full" title="How does Retevis RT3S Digital radio GPS function works?" src="http://blog.retevis.com/wp-content/uploads/2018/10/R33S-GPS-2.png" alt="" width="926" height="505" /> 

<span style="font-size: inherit;">3. Створена система GPS.</span>

<img loading="lazy" class="aligncenter wp-image-6533 size-full" title="How does Retevis RT3S Digital radio GPS function works?" src="http://blog.retevis.com/wp-content/uploads/2018/10/RT3S-3.png" alt="" width="471" height="349" /> 

### Як перевірити чи працює GPS у RT3S?

Вийти на вулицю, почекати кілька хвилин, поки значок GPS активується. Відкрити меню, знайти GPS/BeyDou інформацію.

<figure id="attachment_6548" aria-describedby="caption-attachment-6548" style="width: 544px" class="wp-caption alignnone"><img loading="lazy" class="wp-image-6548 size-full" title="How does Retevis RT3S Digital radio GPS function works?" src="http://blog.retevis.com/wp-content/uploads/2018/10/check-rt3s-GPS.gif" alt="Retevis RT3S GPS увімкнути" width="544" height="960" /><figcaption id="caption-attachment-6548" class="wp-caption-text">Визначення геоположення</figcaption></figure>

#### Як переглянути інформацію про іншу радіостанцію з GPS?

Увійти в меню, знайти контакт, натиснути &#8220;ViewGPS&#8221;.

Отримаєте геопозицію радіо після декількох секунд очікування. У &#8220;RХ GPSinfo&#8221; ви можете дізнатися детальніше, щодо отриманої GPS-інформації.

<figure id="attachment_6538" aria-describedby="caption-attachment-6538" style="width: 895px" class="wp-caption alignnone"><img loading="lazy" class="wp-image-6538 size-full" title="How does Retevis RT3S Digital radio GPS function works?" src="http://blog.retevis.com/wp-content/uploads/2018/10/Check-RT3S-GPS-information.jpg" alt="Retevis RT3S - увімкнення функції GPS" width="895" height="532" /><figcaption id="caption-attachment-6538" class="wp-caption-text">Як подивитись GPS координати</figcaption></figure>

Унікальна система RT3S відслідковує геопозицію кореспондента, з яким ви спілкуєтесь і покаже вам точно, де він знаходиться.