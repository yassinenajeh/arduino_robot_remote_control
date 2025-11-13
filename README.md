# arduino_robot_remote_control
Project completed in 2024 – documented here for portfolio purposes.

## Overview
This project was developed as part of the Sciences de l’Ingénieur (Engineering Science) specialization in high school.
In collaboration with a teammate, we designed, built, and programmed a three-wheeled mobile robot that can be controlled remotely through a smartphone application built with *MIT App Inventor*.

The robot receives control signals from the app via Bluetooth and executes movement commands (forward, backward, left, right, stop) through an *Arduino* microcontroller driving DC motors.

## 🧩 Objectives
* Design a functional and controllable mobile robot prototype
* Model the mechanical structure in *SolidWorks*
* Build a custom Android control interface using *MIT App Inventor*
* Strengthen teamwork and project management skills

## 🛠️ Components & Tools

| Category                 | Tools / Components            |
| ------------------------ | ----------------------------- |
| **Microcontroller**      | Arduino Uno                   |
| **Motors & Drivers**     | DC motors, L298N motor driver |
| **Communication**        | Bluetooth module HC-05        |
| **App Development**      | MIT App Inventor (Android)    |
| **3D Design**            | SolidWorks                    |
| **Power Supply**         | 9V battery pack               |
| **Programming Language** | C++ (Arduino IDE)             |

## 🧠 How It Works

1. The mobile app connects to the Bluetooth module (HC-05) integrated into the robot.
2. The user sends directional commands via buttons in the app.
3. *Arduino* receives the signals and controls the DC motors accordingly.
4. The robot moves in real time following the user’s commands.

## 📱 App Interface (MIT App Inventor)

The app was designed with a simple and intuitive interface including:
4 directional buttons (↑ ↓ ← →)
Connection status indicator
Emergency stop button on the application

<img width="137" height="255" alt="image" src="https://github.com/user-attachments/assets/691bf920-41d4-48c5-9ca2-9e3f72322d8a" />
<img width="560" height="176" alt="image" src="https://github.com/user-attachments/assets/eaa04782-5202-4943-a986-ed52ae4d78b8" />

## 🧰 Mechanical Design (SolidWorks)

The robot chassis was fully modeled in SolidWorks to test balance, weight distribution, and motor placement before physical assembly.

## 💾 Arduino Code Example

## 👥 Team & Collaboration

This project was developed in collaboration with a classmate.
I was mainly responsible for:
- Designing the app interface
- Programming Arduino and integrating Bluetooth communication
- 3D design
- Testing and debugging control responses

My partner contributed to:
- Mechanical assembly
- Electrical wiring and chassis modeling

## 📊 Results
* Fully functional mobile robot controllable via smartphone app
* Stable wireless connection and responsive controls

## 🔍 Key Learnings
* Basics of embedded systems and hardware-software communication
* Design thinking and mechanical modeling
* Importance of testing and debugging
* Team coordination in an engineering project

## 🏁 Next Steps
* Add obstacle avoidance sensors (ultrasonic)
* Explore automation and AI-based navigation
