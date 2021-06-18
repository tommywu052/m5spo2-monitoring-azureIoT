# M5spo2-monitoring-azureIoT
![alt text](imgs\361701.jpg "Title")

> Pre-requisite : 
- 1.Hardware :*M5StickCplus and HeartRate Sensors
- 2.Software : Arduino with M5 Hat Library (Reference:https://github.com/m5stack/M5StickC-Plus/blob/master/examples/Hat/HEART_RATE_MAX30102/HEART_RATE_MAX30102.ino )
- 3.Cloud : Azure Subscription and Azure IoT Central
### 1. Update firmware via Arduino
> * Open HEART_RATE_MAX30102.ino with Arduino or VS Code Plugin
> * Update Line 61 with your Azure IoT Central Device connection String.<br>
>   Update Line 63/64 with your own SSID/PWD
![alt text](imgs\2021-06-18_234614.jpg "Title")
> * Make Sure you have installed the required library- Azure IoT & Esp32MQTTClient
![alt text](imgs\2021-06-19_000425.jpg "Title")

> * Compile & Upload your firmware to M5StickCPlus

### 2. Create Template from Azure IoT Central using this - https://apps.azureiotcentral.com/build/new/d1ee8786-325c-4670-b9e1-bc823d077a5e 
![alt text](imgs\2021-06-18_235555.jpg "Title")


### 3. Change Your Wifi SSID/Pwd to "iot"/"12345678" 
(Optional if you have changed your SSID/PWD)
### 4. Power On M5StickC Plus (On the left side)
![alt text](imgs\361700.jpg "Title")
### 5. Go your IoT Central and Monitoring your Health by customizing your dashboard - 
![alt text](imgs\messageImage_1624008880562.jpeg "Title")
### 6. You can have multiple devices for concurrent monitoring
![alt text](imgs\367096.jpg "Title")