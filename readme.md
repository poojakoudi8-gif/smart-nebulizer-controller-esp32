Smart Nebulizer Controller Using ESP32

📌 Project Overview

The Smart Nebulizer Controller is an ESP32-based healthcare electronics project designed to monitor and control important parameters during nebulization.

The system uses sensors and an OLED display to provide useful information during operation. The project demonstrates the use of Embedded Systems, Sensor Interfacing, and IoT concepts.

🎯 Objectives

- To develop a smart and user-friendly nebulizer monitoring system.
- To interface different sensors with an ESP32.
- To monitor environmental and operating parameters.
- To display the measured information on an OLED display.
- To demonstrate practical applications of embedded systems in healthcare.

🛠️ Components Used

- ESP32 Development Board
- DHT11 Temperature and Humidity Sensor
- OLED Display
- Flow Sensor
- Ultrasonic Sensor
- Connecting Wires
- Breadboard
- Power Supply

⚙️ Working Principle

The ESP32 acts as the main controller of the system.

1. The DHT11 sensor measures temperature and humidity.
2. The flow sensor is used to monitor the flow during nebulizer operation.
3. The ultrasonic sensor is used for distance/level sensing.
4. The ESP32 receives the sensor data.
5. The collected information is processed by the ESP32.
6. The results are displayed on the OLED display.

🔧 System Architecture

          ┌─────────────────┐
          │   DHT11 Sensor  │
          └────────┬────────┘
                   │
          ┌────────▼────────┐
          │                 │
          │      ESP32      │
          │   Controller    │
          │                 │
          └───┬─────────┬───┘
              │         │
       ┌──────▼───┐ ┌──▼──────────┐
       │   OLED   │ │ Flow Sensor │
       │  Display │ └─────────────┘
       └──────────┘
              │
       ┌──────▼──────────┐
       │ Ultrasonic      │
       │ Sensor          │
       └─────────────────┘

💻 Technologies Used

- Embedded C / Arduino Programming
- ESP32
- Sensor Interfacing
- OLED Display Interfacing
- IoT Concepts
- Basic Healthcare Electronics

🚀 Features

- ESP32-based controller
- Real-time sensor monitoring
- OLED-based information display
- Multiple sensor interfacing
- Compact embedded-system design
- Healthcare-oriented application

📚 Learning Outcomes

Through this project, we learned:

- ESP32 programming
- Sensor interfacing
- Reading sensor data
- OLED display interfacing
- Embedded-system programming
- Basic IoT concepts
- Hardware testing and troubleshooting

🔮 Future Scope

The system can be further improved by adding:

- Mobile application connectivity
- Cloud-based data monitoring
- Patient monitoring features
- Automatic nebulization control
- Data logging
- Remote monitoring
- Additional safety and alert features

👩‍💻 Project Type

Mini Project – Electronics and Communication Engineering

📄 Project Documentation
Detailed project information is available in:
PROJECT_DOCUMENTATION.md