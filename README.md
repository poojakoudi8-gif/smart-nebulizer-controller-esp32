# Smart Nebulizer Controller Using ESP32

## Project Overview

The Smart Nebulizer Controller is an academic mini project developed using ESP32 for monitoring and displaying important parameters during nebulization.

The system uses sensors to collect required readings and displays the information on an OLED display. The project demonstrates ESP32-based sensor interfacing, real-time monitoring, and basic IoT concepts.

## Objectives

- To develop a smart monitoring system for a nebulizer.
- To interface sensors with an ESP32 microcontroller.
- To monitor temperature and humidity.
- To monitor airflow-related parameters.
- To display sensor readings on an OLED display.
- To understand real-time sensor interfacing using ESP32.

## Components Used

- ESP32 Development Board
- DHT11 Temperature and Humidity Sensor
- OLED Display
- Flow Sensor
- Ultrasonic Sensor
- Breadboard
- Connecting Wires
- Power Supply

## Technologies Used

- ESP32
- Embedded Systems
- Sensor Interfacing
- Arduino IDE
- C/C++
- Basic IoT Concepts

## Working Principle

1. The ESP32 acts as the main controller.
2. The connected sensors collect the required parameters.
3. The ESP32 processes the sensor readings.
4. The readings are displayed on the OLED display.
5. The system provides real-time monitoring of the connected parameters.

## Block Diagram

   text  
       +----------------------+
       |       Sensors        |
       | DHT11 / Flow Sensor  |
       |   / Ultrasonic       |
       +----------+-----------+
                  |
                  v
       +----------------------+
       |        ESP32         |
       |      Controller      |
       +----------+-----------+
                  |
                  v
       +----------------------+
       |    OLED Display      |
       |   Sensor Readings    | 
       +----------------------+
 