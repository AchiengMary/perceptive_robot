# Perceptive Robotics in Resource-Constrained Settings

This project explores deep learning-based perception for low-cost robots using lightweight models on edge devices like Raspberry Pi and ESP32.

## Goals
- Object detection and gesture recognition with MobileNet, Tiny YOLO
- On-device inference on Raspberry Pi
- Sensor and motor control via ESP32
- ROS 2 simulation and deployment

## Structure
- `models/`: Trained models and conversion tools
- `robot/`: Perception and control scripts
- `hardware/`: ESP32 firmware and schematics
- `notebooks/`: Model training and evaluation

## Hardware Used
- ESP32-CAM
- Raspberry Pi 4 
- Pi Camera
- IR/Ultrasonic sensors

## Quick Start
```bash
git clone https://github.com/AchiengMary/perceptive-robot.git
cd perceptive-robotics
bash setup.sh
