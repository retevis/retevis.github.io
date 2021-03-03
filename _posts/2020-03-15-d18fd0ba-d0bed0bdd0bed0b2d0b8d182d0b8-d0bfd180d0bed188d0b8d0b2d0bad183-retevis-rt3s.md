---
id: 502
title: Як оновити прошивку Retevis RT3S
date: 2020-03-15T15:30:11+00:00
author: Retevis Україна
layout: post
guid: http://54.93.109.229/?p=502
permalink: '/%d1%8f%d0%ba-%d0%be%d0%bd%d0%be%d0%b2%d0%b8%d1%82%d0%b8-%d0%bf%d1%80%d0%be%d1%88%d0%b8%d0%b2%d0%ba%d1%83-retevis-rt3s/'
ap_mark:
  - Это пост был добавлен через AftParser
ap_link:
  - https://blog.retevis.com/index.php/how-to-properly-upgrade-rt3s-firmware/
image: /wp-content/uploads/2020/03/06d074dc4c6c400dbfa19bb3dfb18cc1.jpg
categories:
  - Цифрові рації
---
## Як правильно оновити прошивку [Retevis RT3S](https://retevis.com.ua/shop/retevis-rt3s/)



### Завантажте та встановіть прошивку [RT3S](https://retevis.com.ua/shop/retevis-rt3s/).

Завантажте прошивку [RT3S](https://retevis.com.ua/shop/retevis-rt3s-dmr/) звідси <http://www.retevis.com/resources-center>.

<img loading="lazy" class="aligncenter wp-image-622 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301281590997744645293.jpg" alt="RT3S оновити прошивку" width="600" height="165" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301281590997744645293.jpg 600w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301281590997744645293-300x83.jpg 300w" sizes="(max-width: 600px) 100vw, 600px" /> 

Після завантаження натисніть файл з розширенням .exe для того щоб встановити програму для оновлення прошивки.

<img loading="lazy" class="aligncenter wp-image-624 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301368669341423226265-1.jpg" alt="Оновлення прошивки Retevis RT3S" width="596" height="267" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301368669341423226265-1.jpg 596w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301368669341423226265-1-300x134.jpg 300w" sizes="(max-width: 596px) 100vw, 596px" /> 

Відкрийте файл, який ви знайдете. Прошивок є 4 види:

  * RT3S(CSV)-V17.11
  * RT3S(CSV-GPS)-P17.11
  * RT3S(GPS-REC)-S17.11
  * RT3S(REC)-D17.11

RT3S має дві апаратні версії: [GPS](https://retevis.com.ua/shop/retevis-rt3s-dmr/) та [Non GPS](https://retevis.com.ua/shop/retevis-rt3s/). Якщо ваша рація &#8211; це версія GPS, вам потрібно оновити програмне забезпечення GPS. В іншому випадку після оновлення радіостанції відображатиметься білий екран, &#8220;сніг на екрані&#8221; або інші проблеми. Тож якщо ви хочете оновити прошивку RT3S, спочатку переконайтесь, що ви обрали правильну версію.

Після того, як ми з&#8217;ясували версію GPS, тепер давайте розберемось, що означає CSV та REC.

RT3S підтримує функцію запису (record) або імпорт 120 000 контактів. Необхідно вибрати щось одне: RT3S не може підтримувати їх одночасно. Ось чому є дві різні версії прошивки. Якщо ми вважаємо, що контакти важливі для нас, ми можемо оновити програмне забезпечення CSV. Якщо ми вважаємо, що запис переговорів важливий, ми можемо оновити програмне забезпечення REC.

> Про те, як використовувати функцію запису читайте у [нашій статті](https://retevis.com.ua/rt3s-%d1%8f%d0%ba-%d0%b7%d0%b0%d0%bf%d0%b8%d1%81%d0%b0%d1%82%d0%b8-%d0%bf%d0%b5%d1%80%d0%b5%d0%b3%d0%be%d0%b2%d0%be%d1%80%d0%b8/).

**Крок 1. Ваша рація повинна бути під&#8217;єднана до комп&#8217;ютера за допомого [кабелю для програмування Ретевіс RT3S](https://retevis.com.ua/shop/%d0%ba%d0%b0%d0%b1%d0%b5%d0%bb%d1%8c-%d0%b4%d0%bb%d1%8f-%d0%bf%d1%80%d0%be%d0%b3%d1%80%d0%b0%d0%bc%d1%83%d0%b2%d0%b0%d0%bd%d0%bd%d1%8f-dmr/).**

<figure id="attachment_285" aria-describedby="caption-attachment-285" style="width: 300px" class="wp-caption aligncenter"><img loading="lazy" class="size-medium wp-image-285" src="https://ae01.alicdn.com/kf/HTB1jSnfNwHqK1RjSZFkq6x.WFXav/Special-RETEVIS-USB-Programming-Cable-For-Retevis-RT3-RT8-RT3S-RT52-For-TYT-MD-380-MD.jpg_350x350.jpg" alt="Special RETEVIS USB Programming Cable For Retevis RT3 RT8 RT3S RT52 For TYT MD-380 MD-390 MD 380 DMR Radio Walkie Talkie J9110P" width="300" height="300" /><figcaption id="caption-attachment-285" class="wp-caption-text">Кабель для програмування Retevis RT3S</figcaption></figure>

**Крок 2. Ваша рація повинна бути у режимі DFU.**

Натисніть і утримуйте кнопку PTT та бічну кнопку 1, щоб одночасно увімкнути радіо.

Зауважте, що бічна клавіша &#8211; це клавіша &#8220;PTT&#8221;. Тоді ви побачите як рація мигне червоним та зеленим світлом по черзі.

<img loading="lazy" class="size-medium wp-image-625 aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106-300x300.jpg" alt="Режим DFU Retevis RT3S" width="300" height="300" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106-300x300.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106-150x150.jpg 150w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106-100x100.jpg 100w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301442956275967817106.jpg 600w" sizes="(max-width: 300px) 100vw, 300px" /> 

Крок 3: Відкрийте програм RT3S Firmware upgrade.

<img loading="lazy" class="size-full wp-image-626 aligncenter" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301444892971429203851.jpg" alt="" width="127" height="127" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301444892971429203851.jpg 127w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301444892971429203851-100x100.jpg 100w" sizes="(max-width: 127px) 100vw, 127px" /> Крок 4: Клікніть &#8220;Open file upgrade&#8221;, та виберіть новий файл з прошивкою у форматі .bin.

<img loading="lazy" class="aligncenter wp-image-627 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301454166667365505625.jpg" alt="Прошивка Retevis RT3S" width="562" height="551" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301454166667365505625.jpg 562w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301454166667365505625-300x294.jpg 300w" sizes="(max-width: 562px) 100vw, 562px" /> 

Крок 6: Натисніть &#8220;Download file of upgrade&#8221;, після чого почнеться оновлення.

<img loading="lazy" class="aligncenter wp-image-628 size-full" src="https://retevis.com.ua/wp-content/uploads/2020/03/6369301456327980826303154.jpg" alt="Оновлення прошивки RT3S" width="560" height="554" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/6369301456327980826303154.jpg 560w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301456327980826303154-300x297.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/6369301456327980826303154-100x100.jpg 100w" sizes="(max-width: 560px) 100vw, 560px" /> 

<div>
  <div>
    <p>
      Крок 6: Після того, як все пройде успішно, від&#8217;єднайте RT3S та комп&#8217;ютер. Перезавантажте RT3S. Тепер ви можете перевірити поточну версію прошивки.
    </p>
    
    <p>
      Якщо у вас є інші питання, не соромтесь писати у коментарях.
    </p>
  </div>
</div>