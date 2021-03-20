---
title: 'Retevis RT3S: Програмування рації. Вступ'
date: 2020-03-23T22:00:00+00:00
author: Retevis Україна
permalink: '/retevis-rt3s-%d0%bf%d1%80%d0%be%d0%b3%d1%80%d0%b0%d0%bc%d1%83%d0%b2%d0%b0%d0%bd%d0%bd%d1%8f-%d1%80%d0%b0%d1%86%d1%96%d1%97-%d0%b2%d1%81%d1%82%d1%83%d0%bf/'
image: /wp-content/uploads/2020/03/software-3-RT3S.png
categories:
  - Цифрові рації
tags:
  - RT3S
---
Цифрова DMR-радіостанція Retevis RT3S має безліч функцій. Щоб отримати доступ до усіх налаштувань вам потрібно використовувати програмне забеспечення. Программа називається CPS. Також програмування рації не слід плутати з прошивкою. Як прошивати рацію RT3S я розповідаю у [іншій статті](/%d1%8f%d0%ba-%d0%be%d0%bd%d0%be%d0%b2%d0%b8%d1%82%d0%b8-%d0%bf%d1%80%d0%be%d1%88%d0%b8%d0%b2%d0%ba%d1%83-retevis-rt3s/).

Якщо ви не знаєте як програмувати радіостанцію, або ви новачок - ця стаття для вас.

Нижче приклад як запрограмувати рацію RT3S за допомогою комп'ютера.

## Де завантажити програмне забезпечення?

Перейдіть на офіційний ресурсний центр за посиланням: <http://www.retevis.com/resources-center>. Знайдіть вашу модель RT3S та клікніть "завантажити". Після завантаження та встановлення запустіть програму CPS для вашої моделі рації.

![RT3S: Як виглядає програма CPS](/wp-content/uploads/2020/03/software-1-RT3S.jpg)
*RT3S: Як виглядає програма CPS*

## Меню

### Basic information
У цьому розділі ви дізнаєтесь діапазон вашої радіостанції, версію вашого програмного забезпечення.

### General Setting
Цей пункт меню відповідає а такі налаштування як: Radio ID, Radio Name, Albert Tone, та інші функції та скріншоті нижче. 

![RT3S меню програми](/wp-content/uploads/2020/03/software-3-RT3S-1.png)
*Розділ "General settings" у програмному забезпеченні*

### Menu Item
Якщо ви оберете цей пункт, ви перейдете у розділ налаштування меню вашої рації.

![RT3S програма](/wp-content/uploads/2020/03/software-4-rt.png)
*Розділ "Menu item" програми*
        
### Buttons Definitions
RT3S має 2 функціональні бокові кнопки поряд з тангентою ("PTT"). Ви маєте змогу визначити, за яку функцію відповідатиме кожна з кнопок.

![RT3S Soft](/wp-content/uploads/2020/03/software-5-RT3S.png)
*Пункт "Buttons Definitions" у програмному зеюезпеченні Retevis RT3S*
            
### Text message
Ви можете налаштувати пресети текстових повідомлень. Вони будуть збережені як "Quick Text”.

![RT3S Soft](/wp-content/uploads/2020/03/software-16.png)

*Розділ "Text message" в меню програми*

### Privacy setting
RT3S має два типи шифрування. Базовий "Basic" на 4 bit та "Enhanced" на 32 bit.

![RT3S розділ шифрування](/wp-content/uploads/2020/03/software-15.jpg)
*Два типи шифрування у рації Retevis RT3S. Розділ "Privacy setting"*

### Digit Emergency System
Користувачі можуть налаштувати екстренний дзвінок на базову станцію або на інші радіостанції, а позивні рацій, які видають сигнал тривоги, відображаються на пристроях з дисплеєм.

![RT3S Software](/wp-content/uploads/2020/03/software-14-1.jpg)
*Налаштування функції екстренного виклику "Digit Emergency System" в меню програми*

### Digital Contact
Ви можете завантажити до 10,000 контактів у цьому розділі. Натисніть "Import", щоб завантажити ваш csv-файл з контактами.

![RT3S програмне забезпечення](/wp-content/uploads/2020/03/software-12.jpg)
*Розділ "Digital Contact" у меню програмування RT3S*

### Digital RX Group Call
Ви можете додати 250 списків груп (Group lists) тут. Зробіть ваші групові виклики простішими та швидшими!

![Retevis RT3S CPS інтерфейс](/wp-content/uploads/2020/03/software-11.jpg)
*Налаштування групових викликів у розділі "Digital RX Group Call" CPS*

### Zone information
У вас є можливість додати 250 зон каналів. Розподіліть канали за зонами. Зробіть пошук необхідного каналу легшим!

![RT3S program](/wp-content/uploads/2020/03/software-9.jpg)
*Створення зон*

### Scan list
Ви маєте змогу додати 250 списків сканування (Scan lists) тут. Більше можливостей для ваших потреб сканування! 

![Розділ Scan list в меню CPS](/wp-content/uploads/2020/03/software-8.jpg)
*Розділ "Scan list" в меню CPS*

### Channel Information
Можливість додати 3000 каналів у цьому розділі. Ви можете налаштувати TX-частоту та RX-частоту, channel mode (analog/digital) та інше. Завантажуйте інформацію про ваші канали!

![Налаштування каналів Retevis RT3S](/wp-content/uploads/2020/03/software-7.jpg)
*Налаштування каналів у розділі "Channel Information"*
                                           
### TMF Signaling
Має 4 системи, 32 Encodes та 8 Decodes.

![TMF Signaling](/wp-content/uploads/2020/03/software-6.jpg)
*Розділ "TMF Signaling" в меню*
                                                
### VFO mode
RT3S має режим VFO. Ви можете встановлювати частоту вашої рації з клавіатури, коли ви знаходитесь в режимі VFO.

![VFO Retevis RT3S](/wp-content/uploads/2020/03/VFOMODE-RT3S.jpg)
*Налаштування пункту "VFO mode" в CPS для Retevis RT3S*
                                         
### GPS System
Для рацій з GPS. Ви можете налаштувати 16 systems.

![VFO Retevis RT3S](/wp-content/uploads/2020/03/software-17.png)

*Розділ "GPS System"*

Якщо у вас залишились запитання щодо програмування рації RT3S, будь ласка, залишайте їх в коментарях.
