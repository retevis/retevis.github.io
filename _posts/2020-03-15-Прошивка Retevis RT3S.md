
---
title: Прошивка Retevis RT3S
permalink: '/ru/%d0%bf%d1%80%d0%be%d1%88%d0%b8%d0%b2%d0%ba%d0%b0-retevis-rt3s/'
theaser: /wp-content/uploads/2020/03/06d074dc4c6c400dbfa19bb3dfb18cc1.jpg
categories:
  - DMR рации
tag:
  - RT3S
---
## Как правильно обновить прошивку [Retevis RT3S](https://retevis.com.ua/shop/retevis-rt3s/)
### Скачайте и установите прошивку RT3S.
Загрузите прошивку по этой ссылке: <http://www.retevis.com/resources-center>.

![enter image description here](/assets/image/rt3s_firmware.jpg)

После загрузки запустите файл с расширением .exe для того чтобы установить программу для обновления прошивки.

![enter image description here](/assets/image/rt3s_update_firmware.jpg)

Откройте файл, который вы обнаружите. Прошивок есть 4 вида:
  * RT3S(CSV)-V17.11
  * RT3S(CSV-GPS)-P17.11
  * RT3S(GPS-REC)-S17.11
  * RT3S(REC)-D17.11

Retevis RT3S имеет две аппаратные версии: [GPS](https://retevis.com.ua/shop/retevis-rt3s-dmr/) и [Non GPS](https://retevis.com.ua/shop/retevis-rt3s/).

Если ваша рация &#8211; это версия GPS, вам нужно обновить программное обеспечение для GPS. В противном случае после обновления радиостанции будет отображаться белый экран, &#8220;снег на экране&#8221; или другие проблемы. Поэтому если вы хотите обновить прошивку RT3S, сначала убедитесь, что вы выбрали правильную версию.

После того, как мы выяснили версию GPS, теперь давайте разберемся, что означает CSV и REC.

RT3S поддерживает функцию записи (record) или импорт 120 000 контактов. Необходимо выбрать что-то одно: RT3S не может поддерживать их одновременно. Вот почему есть две разные версии прошивки. Если мы считаем, что контакты важны для нас, мы можем обновить программное обеспечение CSV. Если мы считаем, что запись переговоров важна, мы можем обновить программное обеспечение REC.

> О том как использовать функцию диктофона (Record) читайте в [нашей статье](https://retevis.com.ua/rt3s-%d1%8f%d0%ba-%d0%b7%d0%b0%d0%bf%d0%b8%d1%81%d0%b0%d1%82%d0%b8-%d0%bf%d0%b5%d1%80%d0%b5%d0%b3%d0%be%d0%b2%d0%be%d1%80%d0%b8/).

#### Шаг 1. Ваша рация должна быть подключена к компьютеру 

<span style="font-weight: 600;">c помощью</span>** **<a style="font-weight: bold;" href="https://retevis.com.ua/shop/%d0%ba%d0%b0%d0%b1%d0%b5%d0%bb%d1%8c-%d0%b4%d0%bb%d1%8f-%d0%bf%d1%80%d0%be%d0%b3%d1%80%d0%b0%d0%bc%d1%83%d0%b2%d0%b0%d0%bd%d0%bd%d1%8f-dmr/">кабеля для программирования</a><a style="font-weight: bold;" href="https://retevis.com.ua/shop/%d0%ba%d0%b0%d0%b1%d0%b5%d0%bb%d1%8c-%d0%b4%d0%bb%d1%8f-%d0%bf%d1%80%d0%be%d0%b3%d1%80%d0%b0%d0%bc%d1%83%d0%b2%d0%b0%d0%bd%d0%bd%d1%8f-dmr/"> Retevis RT3S</a>**.**

<figure id="attachment_285" aria-describedby="caption-attachment-285" style="width: 300px" class="wp-caption aligncenter"><img loading="lazy" class="size-medium wp-image-285" src="https://ae01.alicdn.com/kf/HTB1jSnfNwHqK1RjSZFkq6x.WFXav/Special-RETEVIS-USB-Programming-Cable-For-Retevis-RT3-RT8-RT3S-RT52-For-TYT-MD-380-MD.jpg_350x350.jpg" alt="Special RETEVIS USB Programming Cable For Retevis RT3 RT8 RT3S RT52 For TYT MD-380 MD-390 MD 380 DMR Radio Walkie Talkie J9110P" width="300" height="300" /><figcaption id="caption-attachment-285" class="wp-caption-text">Кабель для программирования Retevis RT3S</figcaption></figure>

#### Шаг 2. Ваша рация должна быть в режиме DFU

Нажмите PTT и кнопку вверх, одновременно включите радио. Вы увидите, что светодиод мигает красным и зеленым. Это означает, что RT3S находится в режиме DFU.

Примечание: Если RT3S не находится в режиме DFU до обновления, вы не сможете выполнить обновление успешно. Или приведет к белому / снежному экрану.

<img loading="lazy" class="size-medium wp-image-625 aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106-300x300.jpg" alt="Режим DFU Retevis RT3S" width="300" height="300" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106-300x300.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106-150x150.jpg 150w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106-100x100.jpg 100w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106.jpg 600w" sizes="(max-width: 300px) 100vw, 300px" /> 

#### Шаг 3: Откройте программу RT3S Firmware upgrade

<img loading="lazy" class="size-full wp-image-626 aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301444892971429203851.jpg" alt="" width="127" height="127" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301444892971429203851.jpg 127w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301444892971429203851-100x100.jpg 100w" sizes="(max-width: 127px) 100vw, 127px" /> 

#### Шаг 4: Кликните &#8220;Open file upgrade&#8221;, и выберите новый файл с прошивкой в формате .bin.

<img loading="lazy" class="aligncenter wp-image-627 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301454166667365505625.jpg" alt="Прошивка Retevis RT3S" width="562" height="551" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301454166667365505625.jpg 562w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301454166667365505625-300x294.jpg 300w" sizes="(max-width: 562px) 100vw, 562px" /> 

#### Шаг 5: Нажмите &#8220;Download file of upgrade&#8221;, после чего начнется обновление

<img loading="lazy" class="aligncenter wp-image-628 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301456327980826303154.jpg" alt="Оновлення прошивки RT3S" width="560" height="554" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301456327980826303154.jpg 560w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301456327980826303154-300x297.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301456327980826303154-100x100.jpg 100w" sizes="(max-width: 560px) 100vw, 560px" /> 

#### Шаг 6: Проверка

После того как все пройдет успешно, отключите RT3S от компьютера. Перезагрузите RT3S. Тепер вы можете проверить вашу версию прошивки.

Если у вас есть вопросы &#8211; пишите в комментариях
