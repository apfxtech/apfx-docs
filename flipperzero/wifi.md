# 1 ESP8266

> [!WARNING]
> К сожалению esp8266 не поддерживаеться новыми официальными прошивками.

Для подключения esp8266 к Flipper Zero используете следующую схему:
![image](https://github.com/SequoiaSan/FlipperZero-Wifi-ESP8266-Deauther-Module/blob/FlipperZero-Module-v2/FlipperZeroModule/rep_images/Schematics_1.jpg?raw=true)

Качаем Arduino IDE или Arduino IDEv2.

Устанавливаем, открываем.

Заходим File – Preferences – Additional Board Manager 

Устанавливаем следующую ссылку:

https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json

Ждум скачивания json пакета.

Заходим Tools – Board – Board manager, ищем deauther и устанавливаем Deauther ESP8266 Boards

Заходим Tools – Board – Deauther ESP8266 Boards – “ваша плата” в нашем случае NODEMCU

Подключаем модуль

Заходим Tools – выбираем номер нашего порта.

Скачиваем [код](https://github.com/SequoiaSan/FlipperZero-Wifi-ESP8266-Deauther-Module) из GitHub репозитория.

Распаковываем. Заходим в папку esp8266_deauther

Открываем файл esp8266_deauther.ino

Нажимаем Upload сверху слева.

# 2 ESP32

> [!NOTE]
> У esp32 больше функционала, чем у esp8266б также приложение для esp32 доступно в официальном приложении.
