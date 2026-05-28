# PERFUME-INDUSTRIES-PRESSURE-COMPILANCE-MONITORING-SYSTEM-
The system monitors pressure, classifies it into low, medium, and high levels. Pressure data is logged continuously and shared with the government authority. Alerts ensure safety and legal compliance.

# Smart Pressure Safety System for Industries

An IoT-based industrial pressure monitoring and safety system developed using ESP8266 NodeMCU, BMP180 Pressure Sensor, 16x2 I2C LCD, and Relay Module.

The system continuously monitors pressure levels, classifies them into LOW, MEDIUM, and HIGH conditions, and automatically generates safety alerts and IoT-based compliance reports for industrial monitoring applications.

---

# Project Overview

Industrial environments such as perfume manufacturing, chemical processing, and pressure-based production systems require continuous monitoring to maintain safe operating conditions.

This project provides:
- Real-time pressure monitoring
- Automatic pressure classification
- LCD status display
- Relay-based machine control
- IoT web monitoring
- Automatic compliance reporting

The proposed system improves industrial safety and reduces the risk of pressure-related accidents.

---

# Features

- Real-time pressure monitoring using BMP180
- LOW / MEDIUM / HIGH pressure classification
- 16x2 LCD display output
- Automatic relay control during abnormal conditions
- IoT-based monitoring through ESP8266 WiFi
- Automatic industrial safety report generation
- Continuous pressure data logging
- Simple and low-cost implementation

---

# Components Used

| S.No | Component |
|------|-----------|
| 1 | ESP8266 NodeMCU |
| 2 | BMP180 Pressure Sensor |
| 3 | 16x2 I2C LCD Display |
| 4 | Relay Module |
| 5 | Jumper Wires |
| 6 | Power Supply |

---

# Working Principle

1. BMP180 sensor continuously measures pressure.
2. ESP8266 reads pressure values.
3. The system classifies pressure into:
   - LOW
   - MEDIUM
   - HIGH
4. LCD displays pressure and system status.
5. During continuous HIGH pressure:
   - Alerts are generated
   - Relay controls the machine
   - IoT compliance report is generated
6. Data is displayed through a web interface.

---

# Block Diagram

![Block Diagram](Images/Block_diagram.jpg.jpg)

# Circuit Diagram

![Circuit Diagram](Images/circuit_diagram.jpg.jpeg)

---

# Project Images

## LCD Output

![LCD Output](Images/web_output2.jpg.jpg)

## Web Monitoring Output

![Web Output](Images/web_output1.jpg.jpg)

---

# Software Used

- Arduino IDE
- Embedded C
- ESP8266 WiFi Library
- Adafruit BMP180 Library
- LiquidCrystal I2C Library

---

# Technologies Used

- Embedded Systems
- IoT
- ESP8266 WiFi
- Sensor Interfacing
- Web Monitoring

---

# Applications

- Perfume Industries
- Chemical Industries
- Industrial Automation
- Pressure Monitoring Systems
- Safety Compliance Monitoring

---

# Output

The system successfully:
- Monitors industrial pressure
- Displays pressure status on LCD
- Detects abnormal pressure conditions
- Generates automatic alerts
- Sends IoT-based monitoring reports
- Controls industrial loads using relay

---

# Future Enhancements

- Cloud database integration
- Mobile application monitoring
- AI-based predictive analysis
- Government dashboard integration
- Advanced industrial pressure sensors

---

# Literature Survey References

1. R. Kumar and S. Priya,
   “Design and Development of IoT-Based Industrial Pressure Monitoring System,”
   International Journal of Engineering Research & Technology (IJERT),
   vol. 12, no. 5, pp. 102–106, 2023.

2. M. Sharma and P. Singh,
   “Smart Pressure Monitoring and Control System Using Embedded Technology,”
   International Journal of Advanced Research in Electronics and Communication Engineering,
   vol. 11, no. 3, pp. 45–50, 2022.

3. A. Verma and K. Reddy,
   “IoT-Based Safety Monitoring System for Industrial Applications,”
   IEEE International Conference on Smart Systems and Inventive Technology,
   pp. 210–215, 2024.

4. L. Joseph and N. Patel,
   “Real-Time Industrial Monitoring with Automated Reporting System,”
   International Journal of Innovative Technology and Exploring Engineering (IJITEE),
   vol. 14, no. 1, pp. 67–72, 2025.

---

# Repository Structure

├── Code
│   └── pressure_monitoring.ino
├── Images
│   ├── circuit_diagram.jpg
│   ├── hardware_setup.jpg
│   ├── lcd_output.jpg
│   └── web_output.jpg
├── PPT
├── Report
└── README.md

---

# Authors

Developed as an academic design project by ECE students.

---

# License

This project is licensed under the MIT License.

---

# Conclusion

The Smart Pressure Safety System for Industries demonstrates an efficient and low-cost industrial monitoring solution using IoT and embedded systems. The project improves industrial safety through continuous monitoring, automatic control, and compliance reporting.
