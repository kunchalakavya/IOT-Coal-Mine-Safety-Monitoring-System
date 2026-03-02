🚀 Coal Mine Safety Monitoring System (IoT Based)
📌 Project Overview

The Coal Mine Monitoring System is an IoT-based safety solution designed to continuously monitor environmental conditions inside coal mines.

The system measures:

🌡 Temperature

💧 Humidity

🌫 Air Quality (Gas Levels)

🚧 Collision Detection

Sensor data is transmitted in real-time to the cloud using ThingSpeak for remote monitoring and analysis.

🎯 Objective

To develop a low-cost, real-time monitoring system that enhances worker safety in hazardous underground coal mining environments.

🛠 Hardware Components

ESP8266 (NodeMCU)

DHT11 Temperature & Humidity Sensor

MQ Air Quality Sensor

IR Collision Sensor

16x2 LCD Display (I2C)

Buzzer

WiFi Connectivity

☁ Cloud Platform

Sensor data is uploaded to:

ThingSpeak Cloud Platform

Features:

Real-time data visualization

Historical data storage

Remote monitoring

Graph plotting for environmental analysis

🔁 System Workflow

Sensors collect environmental data.

ESP8266 processes readings.

Data displayed on LCD locally.

If collision detected → Buzzer alert triggered.

Data uploaded to cloud every cycle.

Remote monitoring via ThingSpeak dashboard.

⚠ Safety Features

🚨 Collision Detection Alert

🔊 Buzzer Warning System

📡 Remote Monitoring

📊 Continuous Environmental Tracking

🧠 Technical Highlights

Embedded C Programming

IoT Cloud Integration

Real-Time Monitoring

HTTP GET API Communication

WiFi Networking

LCD I2C Interface

📷 Future Improvements

Add methane gas-specific sensor

SMS alert system

Mobile application dashboard

AI-based hazard prediction model

Integration with underground worker tracking system

👩‍💻 Developed By

Kunchala Kavya
B.Tech – Computer Science (AIML)<img width="3840" height="2160" alt="image" src="https://github.com/user-attachments/assets/8ff905a7-edf0-4afc-9693-3235a2c24cda" />
