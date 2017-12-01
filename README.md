# ESP8266_WifiManager_Alexa_UPnP
Sketch is improved version of arduino-esp8266-alexa-wemo-switch project.

arduino-esp8266-alexa-wemo-switch:
https://github.com/kakopappa/arduino-esp8266-alexa-wemo-switch/blob/master/sinric.ino

Wifi manager:
https://github.com/tzapu/WiFiManager

To connect esp8266 to your WiFi network:
1. Upload sketch to ESP8266
2. Power on ESP 8266. Module will start as access point first.
3. Search for WiFi network name "SmartSocketAccessPoint".
4. Connect to WifiNetwork name "SmartSocketAccessPoint" with password "secure_password".
5. Open browser and goto URL http://192.168.4.1/
6. Connect to your home WiFi network.
7. ESP 8266 module should connect to WiFi network and be accessable for Alexa Home Smart home devices discovery.
Tell Alexa "Alexa, discover new devices" or go directly to Alexa app for smart home devices discovery. 
It should find "smart socket" device.
8. If device "smart socket" is not found -> power off/power on ESP8266 module.
