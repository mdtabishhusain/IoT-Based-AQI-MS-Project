# IoT Based AQI Monitoring System
## Overview
Air pollution is a significant environmental concern affecting humans, animals, crops, and ecosystems. This project aims to design an IoT-based Air Quality Index (AQI) monitoring system using NodeMCU. The system allows remote monitoring of air quality, temperature, and humidity from anywhere using a computer or mobile device. It sends alerts when air quality deteriorates beyond a specified level, aiding in pollution control and environmental management.

## Table of Contents
- Introduction
- Objectives
- Project Components
- Workflow
- Setup and Installation
- Usage
- Results
- Future Work

## Introduction
Air pollution poses serious threats to global environmental health, necessitating effective monitoring and control measures. This IoT-based AQI monitoring system utilizes NodeMCU as the main controller to gather data from sensors detecting harmful gases (CO2, CO, smoke), temperature, and humidity. The system uploads real-time data to ThingSpeak cloud for analysis and provides visual feedback through LED indicators. It enables stakeholders to monitor and respond to air quality issues promptly.

## Objectives
- Develop an IoT-based system to monitor Air Quality Index (AQI).
- Integrate sensors for detecting CO2, CO, smoke, temperature, and humidity.
- Utilize NodeMCU for data aggregation and transmission to ThingSpeak cloud.
- Implement alert mechanisms for notifying users of deteriorating air quality conditions.
## Project Components
1. NodeMCU: Controls and processes data from sensors.
2. Gas Sensors: Detect CO2, CO, smoke levels.
3. Temperature and Humidity Sensor: Monitors environmental conditions.
4. LED Indicators: Display air quality levels locally.
5. ThingSpeak Cloud: Stores and visualizes real-time data.
## Workflow
1. Sensor Data Acquisition: Gas sensors detect pollutants, temperature, and humidity.
2. NodeMCU Processing: NodeMCU collects sensor data and displays AQI via LED indicators.
3. Data Transmission: Data is transmitted to ThingSpeak cloud for remote monitoring and analysis.
4. Alert System: Alerts are triggered when air quality thresholds are exceeded.
5. User Interface: Monitor air quality remotely using a web or mobile interface.
## Setup and Installation
### Prerequisites
- Arduino IDE for programming NodeMCU.
- Basic knowledge of electronics and IoT concepts.
### Steps
1. Set Up NodeMCU: Program NodeMCU using Arduino IDE with provided code.
2. Connect Sensors: Wire gas sensors, temperature, and humidity sensor to NodeMCU.
3. Configure ThingSpeak: Create a ThingSpeak account and set up channels for data logging.
4. Deploy and Monitor: Power on the system and monitor AQI data on ThingSpeak.
## Usage
1. Power On: Ensure NodeMCU and sensors are powered.
2. Monitor Data: View real-time AQI, temperature, and humidity data on ThingSpeak.
3. Receive Alerts: Receive alerts via LED indicators or through the ThingSpeak platform.
## Results
The project successfully creates a scalable IoT-based AQI monitoring system capable of real-time air quality assessment and alerting. It enhances environmental monitoring capabilities and supports efforts towards pollution control and management.

## Future Work
- Expand sensor capabilities to detect additional pollutants.
- Enhance data visualization and analysis features on ThingSpeak.
- Integrate with mobile applications for broader accessibility and control.
