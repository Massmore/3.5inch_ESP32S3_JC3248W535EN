# This is a platformio based build of the JC3248W535EN DEMO_LVGL Package

I had downloaded the zip file from the manufacturer, but had a really hard time getting it to build in VSCode/PlatformIO so I thought I would share my build to help others get started with the board.

Under the covers, this build leverages ESP-IDF 5.3 and LVGL 8.3.  I found that it would not build on Arduino ESP32, as the display code required ESP-IDF (5.3.0) in order to complile.  And Arduino ESP32 is currently ESP-IDF 4.x

For this board from 
https://shopee.co.th/%E0%B9%82%E0%B8%A1%E0%B8%94%E0%B8%B9%E0%B8%A5%E0%B8%AB%E0%B8%99%E0%B9%89%E0%B8%B2%E0%B8%88%E0%B8%AD-ESP32-S3-3.5inch-%E0%B8%9E%E0%B8%A3%E0%B9%89%E0%B8%AD%E0%B8%A1%E0%B9%80%E0%B8%84%E0%B8%AA-JC4832W535-Capacitive-Touch-Display-320%C3%97480-LVGL-i.5641091.20377180498