# Smart-Agricultural-Monitoring-System
ESP8266(NodeMcu) + DHT11 + Soil Moisture Sensor

> [!WARNING]
> This code is for hobbyists for learning purposes. Not recommended for production use!!

## Overview

This project implements a Smart Agricultural Monitoring System using NodeMCU, DHT11 sensor, and Soil Moisture sensor. It sends sensor data (temperature, humidity, and soil moisture) to Anedya's server via MQTT for monitoring and analysis.

## Versions

### v1-mqtt (Version 1 - MQTT)

This version of the code allows users to monitor sensor data only. It includes functionality to:
- Read temperature, humidity, and soil moisture data from physical sensors.
- Connect to a WiFi network securely.
- Transmit data to Anedya's server using MQTT.
- Handle basic error conditions and connection retries.

### v2-mqtt-alerts (Version 2 - MQTT with Email Alerts)
> [!WARNING]
> Version 2 is under process 

In Version 2, email alerts have been added for proactive monitoring. Updates include:
- Integration with email alerts to notify users of critical sensor readings.
- Enhanced error handling and reliability improvements.
