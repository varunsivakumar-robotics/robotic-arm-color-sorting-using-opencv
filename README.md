# Computer Vision Controlled Robotic Arm for Colour Sorting

A computer vision-based robotic arm that detects coloured objects using OpenCV and automatically sorts them using an ESP32-controlled robotic arm.

---

## Project Overview

This project combines computer vision, embedded systems, and robotics to automate colour-based object sorting.

A smartphone camera captures live video.

OpenCV processes each frame to identify coloured objects.

The detected colour is transmitted to an ESP32 via serial communication.

The ESP32 controls servo motors to move the robotic arm and place the object into the appropriate location.

---

## Features

- Real-time colour detection
- OpenCV image processing
- HSV colour segmentation
- Serial communication between computer and ESP32
- Servo motor control
- Automated object sorting
- Hardware-software integration

---

## Hardware Used

- ESP32 Development Board
- SG90 Servo Motors
- Robotic Arm
- Smartphone Camera
- USB Serial Communication
- External Power Supply

---

## Software Stack

- Python
- OpenCV
- PySerial
- Arduino IDE
- ESP32

---

## System Architecture

Smartphone Camera

↓

OpenCV Image Processing

↓

Colour Detection

↓

Serial Communication

↓

ESP32

↓

Servo Motor Control

↓

Robotic Arm

↓

Colour Sorting

---

## Working Principle

1. Capture live video.
2. Convert image to HSV colour space.
3. Detect predefined colours.
4. Determine object position.
5. Send colour information to ESP32.
6. ESP32 executes corresponding servo sequence.
7. Robotic arm places object into the correct location.

---

## Results

Successfully demonstrated

- Stable colour detection
- Accurate serial communication
- Reliable servo control
- Automated colour sorting

---

## Future Improvements

- Object detection using YOLO
- Shape recognition
- Conveyor belt automation
- ROS2 integration
- Raspberry Pi implementation
- AI-based object classification

---

## Author

Varun Sivakumar

B.Tech Robotics and Automation Engineering

REVA University
