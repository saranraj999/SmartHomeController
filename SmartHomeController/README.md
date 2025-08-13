# Smart Home Controller (Java + MQTT)

This is a single-file Java project for controlling IoT devices using MQTT.

## Features
- ON/OFF control for devices
- Real-time status updates
- Simple web dashboard
- Schedules

## Run Instructions
1. Install Mosquitto MQTT broker
2. Download Paho MQTT client jar into libs/
3. Compile:
    javac -cp libs/org.eclipse.paho.client.mqttv3-1.2.5.jar SmartHomeController.java
4. Run:
    java -cp .:libs/org.eclipse.paho.client.mqttv3-1.2.5.jar SmartHomeController
