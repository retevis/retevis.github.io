---
title: 'Retevis RT3S: Настройка рации. Введение'
date: 2021-03-04T22:00:00+00:00
permalink: '/ru/retevis-rt3s-%d0%bd%d0%b0%d1%81%d1%82%d1%80%d0%be%d0%b9%d0%ba%d0%b0/'
image: /wp-content/uploads/2020/03/software-3-RT3S.png
description: 'Инструкция: ➤ Как настроить рацию Retevis RT3S. ➤ Где скачать программу. ➤ Как выбрать версию. ➤ Какие есть настройки.'
categories:
  - DMR рации
tags:
  - RT3S
---
Цифровая DMR-радиостанция Retevis RT3S имеет множество функций. Чтобы получить доступ ко всем настройкам вам нужно использовать программное обеспечение. Программа называется CPS. Также программирования рации не следует путать с прошивкой. Как прошивать рацию RT3S я рассказываю в [другой статье](https://retevis.com.ua/ru/%d0%bf%d1%80%d0%be%d1%88%d0%b8%d0%b2%d0%ba%d0%b0-retevis-rt3s/).

Если вы не знаете как программировать радиостанцию, или вы новичок - эта статья для вас.

Ниже пример как запрограммировать рацию RT3S с помощью компьютера.

## Где скачать программное обеспечение?

Перейдите на официальный ресурсный центр по ссылке: <http://www.retevis.com/resources-center>. Найдите вашу модель RT3S и кликните "загрузить". После загрузки и установки запустите программу CPS для вашей модели рации.

![RT3S программа](/wp-content/uploads/2020/03/software-1-RT3S.jpg)
*RT3S: Как выглядит программа CPS*

## Меню

### Basic information 
В этом разделе вы узнаете диапазон вашей радиостанции, версию вашего программного обеспечения.

### General Setting
Этот пункт меню отвечает за такие настройки как: Radio ID, Radio Name, Albert Tone, и другие функции на скриншоте ниже. 

![RT3S меню программы](/wp-content/uploads/2020/03/software-3-RT3S-1.png)
*Раздел "General settings" в программном обеспечении*

### Item
При выборе этого пункта, вы перейдете в раздел настройки меню вашей рации.

![RT3S програма](/wp-content/uploads/2020/03/software-4-rt.png)
*Раздел "Menu item" программы*

### Buttons Definitions
RT3S имеет 2 функциональные боковые кнопки по бокам от тангенты ("PTT"). Вы можете определить, за какую функцию будет отвечать каждая из кнопок. 

![RT3S Soft](/wp-content/uploads/2020/03/software-5-RT3S.png)
*Пункт "Buttons Definitions" в программном обеспечении Retevis RT3S*
           
### Text message
Вы можете настроить пресеты текстовых сообщений. Они будут сохранены как "Quick Text".

![RT3S soft settings](http://blog.retevis.com/wp-content/uploads/2018/06/software-16.png)

*Раздел "Text message" в меню программы*
                
### Privacy setting
RT3S имеет два типа шифрования. Базовый "Basic" на 4 bit и "Enhanced" на 32 bit.

![RT3S раздел шифрования](/wp-content/uploads/2020/03/software-15.jpg)
*Два типа шифрования в рации Retevis RT3S. Раздел "Privacy setting"*
 
### Digit Emergency System
Пользователи могут настроить экстренный вызов на базовую станцию или на другие радиостанции. Кроме того, позывные раций, которые выдают сигнал тревоги отображаются на устройствах с дисплеем. 

![RT3S Software](/wp-content/uploads/2020/03/software-14-1.jpg)
*Настройка функции экстренного вызова "Digit Emergency System" в меню программы*
                    
### Digital Contact
Вы можете загрузить до 10,000 контактов в этом разделе. Нажмите "Import", чтобы загрузить ваш csv-файл с контактами.

![RT3S Software Digital Contact](/wp-content/uploads/2020/03/software-12.jpg)
*Раздел "Digital Contact" в меню программирования RT3S*
                      
### Digital RX Group Call
Вы можете добавить здесь 250 списков групп (Group lists). Сделайте ваши групповые вызовы проще и быстрее!

![RT3S Software Digital RX Group Call](/wp-content/uploads/2020/03/software-12.jpg)
*Настройка групповых вызовов в разделе "Digital RX Group Call" в RT3S*

### Zone information
У вас есть возможность добавить 250 зон каналов. Распределите каналы по зонам. Сделайте поиск необходимого канала легче!

![RT3S запрограммировать](/wp-content/uploads/2020/03/software-9.jpg)
*Создание зон каналов в программном обеспечении CPS*
      
### Scan list
Вы можете добавить 250 списков сканирования (scan lists) здесь. Больше возможностей для ваших нужд сканирования! 

![RT3S запрограммировать Scan list](/wp-content/uploads/2020/03/software-8.jpg)
*Раздел "Scan list" в меню CPS*
                                       
### Channel Information
Возможность добавить 3000 каналов в этом разделе. Можно настроить TX-частоту и RX-частоту, channel mode (analog / digital) и прочее. Загружайте информацию о ваших каналах тут.

![RT3S Channel Information](/wp-content/uploads/2020/03/software-7.jpg)
*Настройка каналов в разделе "Channel Information"*
                                          
### TMF Signaling
Имеет 4 системы, 32 Encodes и 8 Decodes.

![RT3S TMF Signaling](/wp-content/uploads/2020/03/software-6.jpg)
*Раздел "TMF Signaling" в меню*

### VFO mode
RT3S имеет функцию режим VFO. Когда вы находитесь в режиме VFO, вы можете устанавливать частоту вашей рации с клавиатуры.
                                                    <figure id="attachment_859" aria-describedby="caption-attachment-859" style="width: 981px" class="wp-caption alignnone"><img loading="lazy" class="wp-image-859 size-full" title="VFO Retevis RT3S" src="https://retevis.com.ua/wp-content/uploads/2020/03/VFOMODE-RT3S.jpg" alt="VFO Retevis RT3S" width="981" height="720" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/VFOMODE-RT3S.jpg 981w, https://retevis.com.ua/wp-content/uploads/2020/03/VFOMODE-RT3S-300x220.jpg 300w, https://retevis.com.ua/wp-content/uploads/2020/03/VFOMODE-RT3S-768x564.jpg 768w, https://retevis.com.ua/wp-content/uploads/2020/03/VFOMODE-RT3S-600x440.jpg 600w" sizes="(max-width: 981px) 100vw, 981px" /><figcaption id="caption-attachment-859" class="wp-caption-text">_Настройка пункта &#8220;VFO mode&#8221; в CPS для Retevis RT3S_</figcaption></figure></li> 
                                                    
                                                      * <span style="font-size: inherit;"><span style="font-size: inherit;"><strong>GPS System</strong>: Для раций с GPS. Вы можете настроить 16 systems.</span></span> 
                                                        <figure id="attachment_861" aria-describedby="caption-attachment-861" style="width: 442px" class="wp-caption alignnone"><img loading="lazy" class="wp-image-861 size-full" title="GPS System" src="https://retevis.com.ua/wp-content/uploads/2020/03/software-17.png" alt="GPS System" width="442" height="291" srcset="https://retevis.com.ua/wp-content/uploads/2020/03/software-17.png 442w, https://retevis.com.ua/wp-content/uploads/2020/03/software-17-300x198.png 300w" sizes="(max-width: 442px) 100vw, 442px" /><figcaption id="caption-attachment-861" class="wp-caption-text">_Раздел &#8220;GPS System&#8221;_</figcaption></figure></li> </ol> 
                                                        
                                                        Если у вас есть вопросы поводу программирования рации RT3S, пожалуйста, оставляйте ваши вопросы в комментариях.