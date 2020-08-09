# ESP32-dBmeter-with-MQTT
This dB level meter sends the result by MQTT

## Thanks to Ivan Kostoski for the base of this project##
https://github.com/ikostoski/esp32-i2s-slm

## Parts used in this project ##
Board: DOIT ESP32 DEVKIT V1 <a href="https://www.banggood.com/ESP32-Development-Board-WiFiBluetooth-Ultra-Low-Power-Consumption-Dual-Cores-ESP-32-ESP-32S-Board-p-1109512.html?p=VQ141018240205201801">Available at Banggood</a>

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

## How to start ##

1. Use Visual Basic Studio
2. add PlatformIO
3. start a new project
4. Choose a name
5. Platform DOIT ESP32 DEVKIT 1
6. When project is made copy files to src folder
7. Copy the platformio.ini file to \  (to have proper libraries installed)
8. Changes lines 20 to 25 in main.cpp according your network and MQTT
9. Compile and upload.


## Project Photo
#### Display type: The set up
![Overview](/dBmeterESP32.jpg?raw=true "Included assets")

![In MQTT Explorer](/dBlevel_in_MQTT.png?raw=true "Included assets")

![In Serial Monitor](/Serial_monitor.png?raw=true "Included assets")

## MIT License

Copyright (c) 2020 SpoturDeal | Carl

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
