# 🚗 Smart Parking System using ESP32, Ultrasonic Sensor and Servo Motor

## 📌 Project Overview

This project automates parking gate operations using distance sensing and motor control. The system detects the presence of a vehicle using an ultrasonic sensor and automatically opens or closes the gate using a servo motor. Real-time status information is displayed on an OLED screen.

## 🔧 Components Used

- ESP32 Development Board
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- SSD1306 OLED Display
- Jumper Wires
- Breadboard

## ⚙️ Working Principle

The ultrasonic sensor continuously measures the distance between the sensor and nearby objects.

- When a vehicle approaches within a specified range, the ESP32 detects its presence.
- The ESP32 generates a PWM signal to control the servo motor.
- The gate opens automatically for the vehicle.
- The OLED display shows the current parking gate status.
- Once the vehicle passes, the gate closes automatically.

## 📚 Technical Concepts Applied

- ESP32 Programming
- Ultrasonic Sensor Interfacing
- Distance Measurement
- PWM Signal Generation
- Servo Motor Control
- I2C Communication
- OLED Display Integration
- Embedded Automation

## 🎯 Key Learning Outcomes

- Sensor and actuator interfacing
- Real-time distance measurement
- PWM-based motor control
- Embedded system design and implementation
- Automation logic development
- Simulation and testing using Wokwi

## 🌍 Applications

- Smart Parking Systems
- Automatic Entry Gates
- Toll Booth Automation
- Industrial Access Control
- Smart City Infrastructure

## 📂 Project Files

- ESP32 Source Code
- Circuit Diagram
- Working Demonstration Video

## 🚀 Future Improvements

- Vehicle counting system
- Cloud monitoring using IoT
- Mobile app integration
- RFID-based vehicle authentication
