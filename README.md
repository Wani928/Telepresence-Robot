# Telepresence Robot for People with Quadriplegia

An affordable telepresence robot designed to improve independence and social participation for people with quadriplegia (PWQ).

Built for less than $350 using cost-effective components and a fully integrated hardware–software architecture.

---

## Overview

This system enables real-time remote navigation and audiovisual interaction through four integrated subsystems:

- Control Input (Chin Joystick)
- User Interface (Mobile Apps)
- Robot Platform
- Communication Architecture

---

## Robot Subsystem

- ESP32 (WiFi + Bluetooth)
- L298N motor driver
- TT DC motors
- HC-SR04 ultrasonic sensors (object avoidance)
- 18650 Li-Ion battery pack
- Battery level + motor current monitoring
- Custom 3D-printed chassis (3 mechanical iterations)

Features:
- PWM-based motor control  
- Obstacle detection  
- Real-time system feedback  
- Stability-focused mechanical design  

---

## Control Input (Chin Joystick)

Custom-designed input device tailored for users with limited limb mobility.

- ESP32-based controller  
- Custom PCB (KiCad)  
- Battery monitoring  
- Bluetooth communication  
- Adjustable mechanical clamp  

---

## Mobile Applications

Developed using MIT App Inventor.

- User App (remote control)
- Robot App (mounted device)

Capabilities:
- Send movement commands
- Display system status
- Enable audiovisual interaction
- Manage communication between subsystems

Source `.aia` and compiled `.apk` files included.

---

## Communication Architecture

Hybrid low-latency design:

- Bluetooth Low Energy (BLE) for short-range control
- WiFi (TCP/UDP) for remote operation
- Target latency ≤ 100 ms



