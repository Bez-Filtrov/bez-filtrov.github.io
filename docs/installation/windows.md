---
layout: default
title: Для Windows 10/11
parent: Установка
---

## Установка на Windows

Для Windows в качестве основного клиента мы рекомендуем использовать [AnyPortal](https://github.com/AnyPortal/AnyPortal) - надежный и простой в настройке клиент для Xray.

AnyPortal - Это . Он написан с использованием открытого исходного кода, что дает уверенность в его безопасности.

{: .note }
> Некоторые операционные системы могут выдавать предупреждения о том, что программа получена из неизвестного источника. Это связано с тем, что приложение не прошло платную проверку и не размещено в официальных магазинах — Play Market или App Store.
>
> Однако это не означает, что программа опасна. Исходный код клиента открыт и доступен для изучения на GitHub — крупнейшей платформе для разработчиков. Это позволяет любому человеку убедиться в том, что программа делает именно то, что заявлено, и не содержит вредоносных элементов. Прозрачность кода — лучшая гарантия безопасности.

1. Скачайте и установите по [ссылке](https://github.com/AnyPortal/AnyPortal/releases/latest) `.exe` файл, дважды щелкнув по нему.

   ![win1]({{ site.baseurl }}/images/installation/windows/1.png){: width="100%"}

   ![win2]({{ site.baseurl }}/images/installation/windows/2.png){: width="100%"}

   ![win3]({{ site.baseurl }}/images/installation/windows/3.png){: width="100%"}

   ![win4]({{ site.baseurl }}/images/installation/windows/4.png){: width="100%"}

   ![win5]({{ site.baseurl }}/images/installation/windows/5.png){: width="100%"}

   ![win6]({{ site.baseurl }}/images/installation/windows/6.png){: width="100%"}

   ![win7]({{ site.baseurl }}/images/installation/windows/7.png){: width="100%"}

   ![win8]({{ site.baseurl }}/images/installation/windows/8.png){: width="100%"}

   ![win9]({{ site.baseurl }}/images/installation/windows/9.png){: width="100%"}
2. Откройте приложение после установки.

### 2. Настройка подключения

На текущий момент клиент поддерживает только ручной способ настройки.

#### Ручная настройка

В первую очередь необходимо установить ядро Xray:

1. Перейдите в настройки программы.

   ![win10]({{ site.baseurl }}/images/installation/windows/10.png){: width="100%"}
2. Перейдите в «**Ресурсы**».

   ![win11]({{ site.baseurl }}/images/installation/windows/11.png){: width="100%"}
3. Нажмите «**︙**» в правом верхнем углу и выберете «**Добавить ресурс**».

   ![win12]({{ site.baseurl }}/images/installation/windows/12.png){: width="100%"}
4. Заполните данные в точности как указано ниже и нажмите «**Сохранить и обновить**»:
   *   Тип ресурса: remote
   *   URL: `github://XTLS/Xray-core/Xray-windows-64.zip/xray.exe`.

   ![win13]({{ site.baseurl }}/images/installation/windows/13.png){: width="100%"}
5. Перейдите снова в «**Настройки**» и перейдите в «**Ядра**».

   ![win14]({{ site.baseurl }}/images/installation/windows/14.png){: width="100%"}
6. Нажмите «**︙**» в правом верхнем углу и выберете «**Добавить ядро**».

   ![win15]({{ site.baseurl }}/images/installation/windows/15.png){: width="100%"}
7. Заполните данные в точности как указано ниже и нажмите «**Сохранить и обновить**»:
   *   Тип ядра: Xray
   *   Исполняемый файл ядра: ранее созданный ресурс.

   ![win16]({{ site.baseurl }}/images/installation/windows/16.png){: width="100%"}
8. Перейдите снова в «**Настройки**» и перейдите в «**Переопределение профиля**».

   ![win17]({{ site.baseurl }}/images/installation/windows/17.png){: width="100%"}

9. Найдите пункт «**Внедрить HTTP-входящее соединение**» и включите.

   ![win18]({{ site.baseurl }}/images/installation/windows/18.png){: width="100%"}

Пол дела сделано, отлично ! Теперь добавим профиль с вашим доступом:

1. Скопируйте ссылку подписки для IOS из нашего [Telegram бота](https://t.me/bez_filtrov_vpn_bot).  
   *(Раздел «Мое подключение» -> «Соединение <ID>»)*.
2. Перейдите в AnyPortal в раздел «**Профили**».
3. Нажмите «**︙**» в правом верхнем углу и выберете «**Добавить группу профилей**».

   ![win19]({{ site.baseurl }}/images/installation/windows/19.png){: width="100%"}
4. Вставьте ссылку, которую скопировали в пункте 1 в качестве значения URL и нажмите «**Сохранить и обновить**»

   ![win20]({{ site.baseurl }}/images/installation/windows/20.png){: width="100%"}
5. Сделайте ваш профиль активным, включите VPN вместе с `Системным прокси`.

   ![win21]({{ site.baseurl }}/images/installation/windows/21.png){: width="100%"}
