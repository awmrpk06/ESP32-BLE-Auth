# ESP32-BLE-Auth
Esp32 ble with auth in client
Server will send authenticate message, call a key, here i send the word "auth". 
The client side will read that key, if it is "auth" it will stay connected otherwise it will disconnect.


Required Lib : standard ESP32 lib, you can find it here https://www.arduino.cc/reference/en/libraries/esp32-ble-arduino/
