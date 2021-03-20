---
title: 'RT3S: Як здійснити приватний виклик DMR (private call)'
date: 2020-03-15T14:54:08+00:00
author: Retevis Україна
permalink: /private-call-on-retevis-rt3s-dmr/
image: /wp-content/uploads/2020/03/Знімок-екрана-2020-03-15-о-17.16.11.png
categories:
  - Цифрові рації
---
Retevis RT3S - дводіапазонна радіостанція DMR. Вона підтримує групові та приватні дзвінки. Ця стаття допоможе вам з'ясувати, як здійснювати приватний виклик на Retevis RT3S.

## Private Calls (приватні виклики)

Приватний виклик (Private Call) &#8211; це дзвінок на певний ідентифікатор DMR (DMR ID). Комунікація є приватною. Повідомлення доступне для всіх, хто слухає потік DMR або зі станцією DMR з ідентичним програмованим ідентифікатором DMR. Під час використання станції Retevis RT3S у вас є 3 способи здійснення приватного дзвінка на RT3S.

### Перший метод (Private ID)
Першим методом ви можете вручну набрати приватний ідентифікатор **(Private ID)**, вибравши в меню Контакт **(Contact)**, вибрати Ручний набір (**Manual Dial)** і переключитися між груповим **(Group)** або приватним ідентифікатором **(Private ID)**

![RT3S налаштування контактів](/wp-content/uploads/2020/03/Private-call-on-RT3S-Cherry-169x300.jpg)

### Другий метод (Privat Call)
Ви можете створити приватний канал у програмному забезпеченні.

![RT3S privat call. Створити приватний канал](/wp-content/uploads/2020/03/Retevis-RT3S-Private-call-on-software-1.jpg)

Перш за все вам потрібно вказати ваш&nbsp;**radio ID**&nbsp; та створити новий&nbsp;**new private call contact**.

![Retevis RT3s Privat Call](/wp-content/uploads/2020/03/Private-call-set-on-Retevis-RT3S-Cherry-169x300.jpg)
![RT3S privat call (приватний виклик)](/wp-content/uploads/2020/03/private-call-number-on-Retevis-RT3S-169x300.jpg)

Потім встановіть інформацію про канал, частоту, виберіть приватний контакт, таймслот (time slot), color code, всю основну конфігурацію.

![Ретевис RT3S (приватный вызов)](/wp-content/uploads/2020/03/retevis-rt3s-private-call-channel-setting.jpg)

Наступний крок, я думаю, найважливіший - додайте цей канал у зону, інакше ви не можете знайти цей канал у радіостанції.

![RT3S вибрати зону](/wp-content/uploads/2020/03/retevis-rt3s-zone-setting.jpg)

Усі налаштування закінчені. Запишіть налаштування на радіо. Увімкніть цей канал і натисніть PTT. Тепер ви передасте сигнал на приватний ідентифікатор.

### Третій спосіб (Program Radio)
Додайте новий цифровий канал на радіо. Для цього потрібно поставити галочку (Program Radio) в програмному забезпеченні.

![RT3S увімкнути Program radio](/wp-content/uploads/2020/03/retevis-rt3s-program-radio-setting.jpg)

Якщо у вас виникли питання - пишіть їх у коментарях.
