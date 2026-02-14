---
layout: default
title: Для MacOS
parent: Установка
---

## Установка на MacOS

Для MacOS в качестве основного клиента мы рекомендуем использовать Streisand. Это надежный и простой в настройке клиент.

### 1. Скачивание приложения

1. Перейдите в AppStore и скачайте приложение по [ссылке](https://apps.apple.com/tr/app/streisand/id6450534064).

   ![macos1]({{ site.baseurl }}/images/installation/macos1/1.png){: width="50%"}
2. Откройте приложение после установки.

### 2. Настройка подключения

Мы предлагаем два способа настройки: автоматический (в один клик) и ручной.

#### Способ 1: Автоматическая настройка (Рекомендуется)

<div id="auto-setup-container" style="display: none; padding: 20px; background-color: #f0f7fd; border-left: 5px solid #0088cc; margin-bottom: 20px;">
   <strong>🚀 Быстрая настройка:</strong>
   <p class="mb-2">Мы определили ваш ключ доступа. Нажмите кнопку ниже, чтобы автоматически добавить сервер в приложение:</p>
   
   <a id="deep-link-btn" href="#" class="btn btn-primary fs-4">Добавить в Streisand</a>
   <p class="fs-2 mt-2 text-grey-dk-000">После нажатия подтвердите открытие в приложении Streisand.</p>
</div>

<script>
document.addEventListener("DOMContentLoaded", function() {
   const SCHEMA_PREFIX = "streisand://import/"; 
   const PARAM_NAME = 'link';
   
   const urlParams = new URLSearchParams(window.location.search);
   const subscriptionUrl = urlParams.get(PARAM_NAME);
    
   if (subscriptionUrl) {
      const finalLink = SCHEMA_PREFIX + subscriptionUrl; 

      const container = document.getElementById('auto-setup-container');
      const btn = document.getElementById('deep-link-btn');
        
      btn.href = finalLink;
      container.style.display = 'block';
   }
});
</script>

<div style="background-color: #fff8c5; border-left: 5px solid #e3b341; padding: 15px; border-radius: 4px; color: #4a4a4a; margin: 20px 0;" markdown="1">
   Если автоматическая кнопка выше не появилась, перейдите в [Telegram бот](https://t.me/bez_filtrov_vpn_bot).
   <small>Раздел «Мое подключение» -> «Соединение ID»</small>.
</div>

#### Способ 2: Ручная настройка

1. Скопируйте ссылку подписки для IOS из нашего [Telegram бота](https://t.me/bez_filtrov_vpn_bot).  
   *(Раздел «Мое подключение» -> «Соединение <ID>»)*.
2. В приложении Streisand нажмите «**+**» в правом верхнем углу.

   ![macos2]({{ site.baseurl }}/images/installation/macos/2.png){: width="50%"}
3. В появившемся меню выберите «**Настроить вручную**»

   ![macos3]({{ site.baseurl }}/images/installation/macos/3.png){: width="50%"}
4. Заполните данные в точности как указано ниже:
   *   Тип: Subscription
   *   Имя: BezFiltrovVPN
   *   URL: *(Вставьте ссылку, которую скопировали в пункте 1)*
   *   Автообновление: Каждый час.

   ![macos4]({{ site.baseurl }}/images/installation/macos/4.png){: width="50%"}
5. Нажмите «**Сохранить**» в правом верхнем углу.
6. Вернитесь на главную, выберите добавленное подключение и нажмите переключатель сверху для соединения.

   ![macos5]({{ site.baseurl }}/images/installation/macos/5.png){: width="50%"}