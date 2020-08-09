# ESP32-dBmeter-with-MQTT
This dB level meter sends the result by MQTT

## Thanks to Ivan Kostoski for the base of this project##
https://github.com/ikostoski/esp32-i2s-slm

## Parts used in this project ##
Board: DOIT ESP32 DEVKIT V1, 80Mhz, 4MB(32Mhz),921600 None op COM3 <a href="https://www.banggood.com/ESP32-Development-Board-WiFiBluetooth-Ultra-Low-Power-Consumption-Dual-Cores-ESP-32-ESP-32S-Board-p-1109512.html?p=VQ141018240205201801">Available at Banggood</a>

Microphone: MH-ET LIVE Omnidirectional Microphone Module I2S Interface INMP441 MEMS High Precision Low Power Ultra small volume for ESP32 <a href="https://nl.aliexpress.com/item/4000045517597.html?spm=a2g0s.9042311.0.0.27424c4d2aH1EK">Available at Aliexpress</a>

## Wiring ##

|From|To|
|---|---|
|**ESP Module**|**INMP441**|
|3V3| -> VDD|
|GND| -> GND|
|D18| -> WS|
|D19| -> SD|
|D23| -> SCK|
|GND| -> L/R|























3
