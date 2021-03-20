# ESPNOW-MPU6050
In this project, using the one-way scenario of ESP-NOW protocol, we will send the values of MPU6050 module including x, y, z to the destination board. In other words, with a remote ESP board, we send information to another board by moving the acceleration and gyro sensors in space.

## What it DO!
In the MPU6050 sensor data transmission project, we have used two Wi-Fi boards for data analysis and communication with the ESP NOW protocol, which is one of the tasks of analyzing the values obtained from the mpu6050 module and according to the data structure specified in the program code Has a second board or receiver. Next, we have the receiver board, which we have used ESP8266 in this project, and this chip has the task of coordinating with the first board in the scenario, ie the sender board, and also according to the pre-defined structure, the values are received, analyzed and serialized. Displays the monitor.

### Items needed
-ESP32
-Wemos
-MPU6050

### Required libraries
-esp_now
-WiFi

## Conclusion
In this project, using the ESP-NOW protocol, we received and analyzed the values of an MPU6050 module at the desired destination, which in this scenario was an ESP32, and then sent it to the destination wirelessly, ie Wemos backboard with ESP8266 chip, and in serial We showed the monitor.


 Full Tutorial at http://cifertech.net/
