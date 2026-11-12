# design-and-development-of-terrain-adaptive-unmanned-ground-vehicle-
A six-wheeled rocker-bogie terrain-adaptive unmanned ground vehicle using ROS 2, Raspberry Pi and ESP32.

# Six-Wheel ROS 2 Robotic Rover

## Project Overview

The Six-Wheel ROS 2 Robotic Rover is a mobile robotic platform developed using a rocker-bogie suspension system. The rover uses six independently driven N20 geared DC motors, controlled through an ESP32 microcontroller and three TB6612FNG motor drivers.

A Raspberry Pi 5 (4GB) serves as the main computing platform, running ROS 2. The rover is designed to receive movement commands from a laptop through Wi-Fi.

The long-term objective is to develop an intelligent rover with AI-based capabilities for autonomous operation and adaptive navigation.

## Project Objectives

- Develop a six-wheel robotic rover using rocker-bogie suspension.
- Implement independent control of all six wheels.
- Integrate ESP32-based motor control.
- Use Raspberry Pi 5 as the main ROS 2 computer.
- Establish wireless communication between the laptop and rover.
- Develop a platform for future AI integration.

## Hardware Components

| Component | Quantity |
|---|---:|
| Raspberry Pi 5 (4GB) | 1 |
| ESP32 Dev Kit | 1 |
| TB6612FNG Motor Driver | 3 |
| N20 Geared DC Motor | 6 |
| Wheels | 6 |
| Rocker-Bogie Suspension | 1 assembly |

## Software and Technologies

- ROS 2
- Python
- ESP32 / Arduino Framework
- Linux
- Wi-Fi Communication
- Future AI Integration

## System Architecture

Laptop
   |
   | Wi-Fi
   |
Raspberry Pi 5 (ROS 2)
   |
   | ESP32 Communication Interface
   |
ESP32 Dev Kit
   |
   +-- TB6612FNG Driver 1
   +-- TB6612FNG Driver 2
   +-- TB6612FNG Driver 3
   |
Six N20 Geared DC Motors

## Mechanical Design

The rover uses a rocker-bogie suspension configuration designed to provide improved wheel contact and mobility over uneven terrain.

## Motor Control

The rover uses six N20 geared DC motors and three TB6612FNG motor drivers.

Each motor is intended to have independent control for flexible movement and testing.

## Current Development Status

- [x] Six-wheel rover architecture defined
- [x] Rocker-bogie suspension selected
- [x] Motor and controller configuration selected
- [ ] Mechanical CAD documentation
- [ ] Motor driver wiring documentation
- [ ] ESP32 motor-control firmware
- [ ] ROS 2 integration
- [ ] Laptop-based wireless teleoperation
- [ ] Testing and validation

## Future Development

- AI-based intelligent control
- Terrain recognition
- Autonomous navigation
- Sensor-based terrain adaptation
- Intelligent obstacle detection

## Project Goal

To develop a modular robotic platform combining mechanical engineering, embedded systems, ROS 2 and future AI technologies.

---

**Project Category:** Robotics / Unmanned Ground Vehicle  
**Controller:** ESP32 Dev Kit  
**Main Computer:** Raspberry Pi 5  
**Framework:** ROS 2
