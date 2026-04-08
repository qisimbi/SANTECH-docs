Today we worked on IoT-Based Temperature and Humidity Monitoring and Control System using ESP32. 
This project is an IoT system that measures temperature and humidity using a sensor, sends the data to a computer server over Wi-Fi, and allows remote control of devices like LEDs and fans. Here are the main components:

- ESP32: Main microcontroller with Wi-Fi
- DHT11 sensor: Measures temperature and humidity
- LCD (I2C) : Displays data locally
- LEDs: Represent controlled devices
- Fans (via relay): Real output devices
- Server (PHP + database) :Stores and sends control data

How it works step by step:

1. The ESP32 connects to Wi-Fi
2. The DHT11 sensor reads:
Temperature
Humidity
3. The ESP32 sends this data to a server using HTTP
4. The server stores the data in a database
5. The ESP32 also requests control commands from the server

6. The server responds with values like:
1,0,1,0
7. Based on this:
LEDs turn ON/OFF
Fans turn ON/OFF
8. The LCD displays real-time data and device status

* Wi-Fi allows remote monitoring and control, making the system accessible from anywhere on the same network.

![](../images/week%202%20images/Screenshot%202026-04-08%20232353.png)

