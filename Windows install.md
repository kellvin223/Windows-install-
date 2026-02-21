## Создание загрузочной флешки:

1. Заходим на сайт. Выбераем Download Windows 11 Disk Image (ISO) for x64 devices:

https://www.microsoft.com/en-us/software-download/windows11

2. Cкачиваем xml файл с конфигурацие установки autounattend.xml (прикреплен в репо).

3. Устанавливаем AnyBur. Внутри AnyBurn нажимаем Edit image, выбераем наш образ и добавляем в него наш файл:

https://www.anyburn.com/download.php

4. Скачиваем Rufus. Выбераем флешку не меньше 8гб, выбераем наш образ и запускаем:

https://rufus.ie/ru/

---
## Установка Windows с загрузочной флешки:
Перезапускаем ПК, спамим F12 (кнопку для открытия BOOT MENU), там выбераем нашу флешку и запускаем, в настройках выбераем диск на который установится винда. Необходимо удалить все системные разделы. Для полной очисткки удаляем все разделы.

---
## Установка и активация Office, Windows и WinRar
Образ Office - https://massgrave.dev/genuine-installation-media

WinRar - https://www.win-rar.com/start.html?&L=4

Чтобы активировать Windows и Office необходимо вставить команду в PowerShell:
```irm https://massgrave.dev/get | iex```

Там выбрать метод 3 и активировать все.

Очистка Windows, первая кнопка - https://disk.yandex.ru/d/2Hdq1LSedY97gg 

---
## Установка приложений и драйверов

Приложения:
- Firefox - https://www.firefox.com/ru/?utm_campaign=SET_DEFAULT_BROWSER
- Discord - https://discord.com/download
- Telegram - https://desktop.telegram.org/?setln=ru
- Steam - https://store.steampowered.com/?l=russian
- Happ - https://github.com/Happ-proxy
- 

---
## Доп настройки
Доп материалы - https://gitlab.com/-/snippets/3746553

Панель задач - Правой по панели задач > Параметры панели задач > Поведение панели задач > Выравнивание панели задач

Экран - Параметры > Система > Питание > Время ожидания до спящего режима 
