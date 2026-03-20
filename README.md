# ESP32-drone
ESP32-based quadcopter drone with MPU6050, built using hardware integration and preconfigured firmware, with mobile app control.
ESP32-Based Quadcopter Drone

##Overview

A compact quadcopter drone built using ESP32 and MPU6050 by integrating hardware components and configuring flight control using prebuilt firmware.

My Contributions

- Assembled drone frame and mounted components
- Connected ESC, motors, MPU6050, and ESP32
- Performed soldering and wiring
- Flashed firmware using ESP Launchpad
- Tuned roll, pitch, and trim using mobile app
- Tested and achieved stable flight

Components

- ESP32 / ESP32-S3
- MPU6050
- Coreless DC Motors
- ESC
- Li-Po Battery
- Frame

Features

- App-based control
- Roll and pitch trim adjustment
- Angle control
- Indoor stable flight

Working Principle

MPU6050 provides orientation data to ESP32, which processes it using firmware and controls motor speed via ESCs.

Setup

- Flashed firmware using ESP Launchpad
- Connected components based on reference wiring
- Controlled using ESP32 drone app

External Resources

- Firmware
- App
- Wiring reference

Challenges

- Initial instability during flight
- Sensor calibration issues
- Power distribution problems

Future Improvements

- Add FPV camera
- Improve stability with PID tuning
- Develop custom firmware
