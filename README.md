# DucuClock
## Dependencies
* DuduUtils
* ArduinoJson 7.0.4
* OneButton 2.5.0
* ArduinoZlib
* TaskScheduler 3.7.0
* TFT_eSPI 2.5.43

## Modifications
* User User_Setup.h provided by author, which actually choose correct pin and tft driver
* Fix esp32c3 core panic through changine TFT_eSPI_ESP32_C3.h spi port #define SPI_PORT 2
