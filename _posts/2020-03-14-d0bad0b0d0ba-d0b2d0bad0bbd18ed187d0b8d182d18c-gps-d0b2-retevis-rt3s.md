---
title: Как включить GPS в Retevis RT3S?
date: 2020-03-14T05:25:00+00:00
author: Retevis Україна
<!--permalink: '/ru/%d0%ba%d0%b0%d0%ba-%d0%b2%d0%ba%d0%bb%d1%8e%d1%87%d0%b8%d1%82%d1%8c-gps-%d0%b2-retevis-rt3s/'-->
image: /wp-content/uploads/2020/03/Check-RT3S-GPS-information.jpg
published: true
---
GPS глобальная система позиционирования &#8211; это спутниковая навигационная система, используемая для определения наземного положения объекта. DMR рация Retevis RT3S с функцией GPS может определять вашу позицию с помощью спутника и получать GPS-информацию от других радиостанций. Но знаете ли вы, как в RT3S GPS работает эта функция?

<img loading="lazy" class="aligncenter wp-image-400 size-large" src="https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--578x1024.jpg" alt="GPS RT3S включение" width="578" height="1024" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--578x1024.jpg 578w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--169x300.jpg 169w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--768x1360.jpg 768w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--867x1536.jpg 867w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS--600x1063.jpg 600w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS-.jpg 1080w" sizes="(max-width: 578px) 100vw, 578px" /> 

## Что вам нужно?

  1. Купить радиостанцию ​​Retevis RT3S в [авторизованном магазине Retevis](http://54.93.109.229/ru/shop/retevis-rt3s-gps/).
  2. Скачать програмное обеспечения для RT3S с [ресурсного центра](http://www.retevis.com/resources-center) на официальном сайте.
  3. Купить [кабель программирования](https://retevis.com.ua/shop/кабель-для-програмування-dmr/).

## Как запрограммировать RT3S GPS?

  1. Во-первых, откройте программное обеспечение и в пункте &#8220;menu item&#8221; поставьте галочку &#8220;GPS&#8221;.

<img loading="lazy" class="alignnone wp-image-577 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS-1.jpg" alt="Как включить GPS в RT3S" width="822" height="386" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS-1.jpg 822w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS-1-300x141.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS-1-768x361.jpg 768w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-GPS-1-600x282.jpg 600w" sizes="(max-width: 822px) 100vw, 822px" /> 

2. Создайте один канал, который нужно использовать с функцией GPS. Важно поставить галочки напротив &#8220;отправить данные GPS&#8221; и &#8220;получать данные GPS&#8221; и выбрать одну систему GPS.

<img loading="lazy" class="aligncenter wp-image-6532 size-full" title="How does Retevis RT3S Digital radio GPS function works?" src="http://blog.retevis.com/wp-content/uploads/2018/10/R33S-GPS-2.png" alt="Retevis rt3s включение GPS" width="926" height="505" /> 

3. Созданная система GPS:

<img loading="lazy" class="alignnone wp-image-580 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-3.png" alt="Retevis RT3S как включить GPS" width="471" height="349" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-3.png 471w, https://retevis.com.ua/wp-content/uploads/2020/03/RT3S-3-300x222.png 300w" sizes="(max-width: 471px) 100vw, 471px" /> 

## Как проверить работает ли GPS в RT3S?

Выйти на улицу, подождать несколько минут, пока значок GPS активируется. Открыть меню, найти GPS / BeyDou информацию.

## Как посмотреть информацию о другой рации ​​с GPS

Войти в меню, найти контакт, нажать &#8220;ViewGPS&#8221;.

Получите геопозицию радио после нескольких секунд ожидания. В &#8220;RХ GPSinfo&#8221; вы можете узнать подробнее об полученной GPS-информации.

<figure id="attachment_6538" aria-describedby="caption-attachment-6538" style="width: 895px" class="wp-caption alignnone"><img loading="lazy" class="wp-image-6538 size-full" title="How does Retevis RT3S Digital radio GPS function works?" src="http://blog.retevis.com/wp-content/uploads/2018/10/Check-RT3S-GPS-information.jpg" alt="Retevis RT3S - увімкнення функції GPS" width="895" height="532" /><figcaption id="caption-attachment-6538" class="wp-caption-text">Как посмотреть GPS координаты</figcaption></figure>

Уникальная система RT3S отслеживает геопозицию корреспондента, с которым вы общаетесь и покажет вам точно, где он находится, даже когда его не видно и не слышно.