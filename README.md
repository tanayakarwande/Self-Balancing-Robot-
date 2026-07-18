# Self-Balancing-Robot
ESP32-based self-balancing robot using MPU6050 and PID control for real-time stability.

# Self-Balancing Robot using ESP32
This project was developed as a college mini project to demonstrate real-time control systems using an ESP32 microcontroller. The robot maintains its balance using data from the MPU6050 IMU sensor and a PID control algorithm.

## Overview
This project is a two-wheel self-balancing robot developed using the ESP32 microcontroller and the MPU6050 IMU sensor. The robot maintains its balance in real time using a PID control algorithm that continuously adjusts the motor speed based on the robot's tilt angle.

---

## Features
- Real-time self-balancing using PID control
- ESP32-based embedded control system
- MPU6050 accelerometer and gyroscope integration
- L298N motor driver for precise motor control
- Continuous sensor feedback for stable balancing
- Fast processing and efficient control using ESP32

---

## Hardware Used
- ESP32 Development Board
- MPU6050 IMU Sensor
- L298N Motor Driver
- 2 × DC Geared Motors
- Robot Chassis
- Wheels
- Lithium-ion Battery Pack

---

## Software & Technologies
- Arduino IDE
- Embedded C/C++
- ESP32
- PID Control Algorithm
- I2C Communication

---

## Working Principle
The MPU6050 continuously measures the robot's tilt angle using its accelerometer and gyroscope. The ESP32 processes this sensor data in real time and calculates the error from the desired upright position. A PID controller computes the required motor speed and direction, and the L298N motor driver drives the motors accordingly to keep the robot balanced.

---

## Project Images
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/b77222d8-1030-4a58-beb0-18a0fc8d8a92" />
<img width="400" height="400" alt="image" src="https://github.com/user-attachments/assets/2525ccf6-e772-4794-92b7-81179b916fd2" />

---

## Demo Video
C:\Users\user5\Downloads\WhatsApp Video 2026-07-18 at 11.52.37 PM.mp4
---

## Future Improvements
- Bluetooth or Wi-Fi control using ESP32
- Mobile application for remote monitoring
- Obstacle detection and avoidance
- Automatic PID parameter tuning

---

## Author
Tanaya Karwande
