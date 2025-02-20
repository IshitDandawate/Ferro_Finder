# Ferro_Finder

Iron collector Bot for Metaverse using unity and hardware 
This repository contains the code and project files for a Ferro Finder Robot, a small mobile robot designed to detect and locate ferrous (iron-containing) metal objects.  The project utilizes an Arduino microcontroller for hardware control and Unity for visualization and potentially simulation/control interface development.

# Overview

The Ferro Finder Robot uses a sensor (e.g., inductive proximity sensor, magnetometer) to detect the presence of ferrous metals.  The Arduino code processes the sensor data and controls the robot's motors to navigate towards the detected metal object. This repository provides the Arduino code (.ino file) required to operate the robot's hardware.

# Hardware

Microcontroller: ESP32
Sensor: Ultrasonic sensor 
Motors: DC Motors
Motor Driver: L298N Motor Driver
Power Supply: 12V Battery
Chassis: Wooden Plank

Arduino IDE: The Arduino code is written in C++ and should be compiled and uploaded using the Arduino IDE.
Unity: Unity is used to visualize the robot's sensor readings and potentially create a simulated environment for testing and development.

meta_over_wifi.ino: The Arduino sketch containing the code for controlling the robot's hardware, including sensor reading, motor control, and logic for finding ferrous metals..
