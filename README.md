# 🌾 Smart Farm Monitor for Agricultural Production and the Environment

[![Build Status](https://img.shields.io/badge/Status-Completed-success)](#)
[![Hardware](https://img.shields.io/badge/Hardware-Arduino-blue)](#)
[![Software](https://img.shields.io/badge/Software-C%2B%2B%20%7C%20C%23-purple)](#)
[![Institution](https://img.shields.io/badge/Institution-NTU%20Iraq-gold)](#)

---

## 📖 Overview
A comprehensive, intelligent robotic system aimed at revolutionizing agricultural applications by integrating Internet of Things (IoT) technologies and autonomous systems. This robot is designed to be the watchful eye and the working hand in the field; it automatically takes care of plants, meticulously monitors environmental factors, and detects potential risks such as fires early on, ensuring sustainable agricultural production and a safe environment for crops.

## ✨ Key Features
- **🌡️ Comprehensive Environmental Monitoring:** High capability to measure soil moisture levels, air quality, carbon dioxide ($CO_2$) ratio, in addition to atmospheric temperature and humidity.
- **💧 Smart & Autonomous Irrigation:** Automatic activation of the built-in water pump as soon as soil moisture drops below the required threshold, with automatic shut-off when sufficient.
- **🗺️ Autonomous Navigation & Hybrid Control:** An advanced navigation system relying on GPS and a digital compass for precise path correction. It supports remote control via a smartphone app (Bluetooth) or a wireless central control unit (Zigbee) with a coverage range of up to 1000 meters in open areas.
- **🎯 Precision Pest Control:** Utilizing targeted laser technology to aim at and eliminate weeds that compete with crops.
- **📊 Cloud Data Management (IoT):** Real-time data streaming via a Wi-Fi module to a secure database, displayed through a custom interactive platform that gives agricultural engineers a comprehensive analytical view.
- **🛡️ Obstacle Avoidance & Response:** A perimeter sensing system using ultrasonic waves to ensure safe navigation and avoid collisions with obstacles in the field.
- **☀️ Clean & Renewable Energy:** High energy efficiency supported by rechargeable lithium batteries via built-in solar panels to ensure continuous operation.

## 🛠️ Hardware Components
The physical structure of the robot is designed with a durable metal frame that withstands agricultural terrain, supported by an arsenal of the latest sensors and control units:
- **Central Processing Units:** Arduino Mega 2560 & Arduino Uno
- **Communication & Network Modules:** Wi-Fi Module (ESP8266), Bluetooth (HC-05), and Long-Range Communication Module Digi XBee S2C (Zigbee)
- **Navigation & Guidance Systems:** U-Blox Neo 6M GPS Module, HMC5883L Digital Compass
- **Precision Environmental Sensors:**
  - **MQ135:** For air quality analysis and gas detection (CO2, Ammonia, Smoke)
  - **DHT11:** For temperature and humidity
  - **Soil Moisture Sensor**
  - **Water Level Sensor**
- **Motion Systems & Motors:** L298N Dual H-Bridge Motor Driver, DC Motors with wheels, Servo Motor
- **Vision & Obstacle Avoidance:** HC-SR04 Ultrasonic Sensor
- **Power System:** Amorphous Solar Panel (40W 12V), 18650 Lithium Battery Pack with an advanced Battery Management System (BMS)

## 💻 Software Architecture
The robust hardware harmonizes with a solid software architecture to ensure stable and responsive performance:
- **Arduino IDE:** To code complex operational processes for microcontrollers in `C++`.
- **Visual Studio (C#):** To develop the central display and analysis platform (Windows GUI) for receiving and archiving field data into Excel files.
- **MIT App Inventor:** To develop an integrated and smooth Android application, enabling the user to manually guide the robot and monitor its coordinates via the smartphone screen.
- **X-CTU:** To program and configure the wireless communication networks for the Zigbee modules.

## ⚙️ How it Works
1. **Path Planning:** Start and destination coordinates (Waypoints) are set for the robot to move autonomously based on GPS and compass readings.
2. **Sensing & Analysis:** During its journey, environmental sensors continuously scan the field environment (air, soil, gases).
3. **Action & Reaction:** Whenever the system senses dryness in the soil, it activates the irrigation pump. If it detects weeds, it activates the laser system.
4. **Documentation & Reporting:** Readings are periodically transmitted (via Wi-Fi) to a central computer to accurately document the farm's condition without any human intervention.

## 🎓 Credits
This project was completed as part of the requirements for obtaining a Bachelor's degree in Computer Techniques Engineering.
- **Developed & Prepared by:** Polian Amir Poulis (along with Abdullah Ezzat Abd, Yatron Dawod Malko, Rita Elias Yono, Siva Adil Patros)
- **Scientific Supervision:** Mr. Abdullah M.A. Hamdoon
- **Academic Institution:** Northern Technical University (NTU) - Computer Techniques Engineering Department, Mosul, Iraq.
- **Academic Year:** 2022-2023
