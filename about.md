# 🚗 Dual Mode Smart Car using ESP8266

## 📌 Project Title
**Dual Mode IoT-Based Smart Car using ESP8266**

---

## 📖 Introduction
This project is a smart robotic car controlled using two different communication modes:  
**ESP-NOW** for local wireless control and **MQTT (Internet of Things)** for remote control through the internet.

The system allows the user to switch between offline and online control modes using a hardware button.

---

## 🎯 Objective
- To design a smart car with dual communication modes  
- To enable both local and internet-based control  
- To improve safety using automatic stop (fail-safe) system  
- To demonstrate IoT and wireless communication concepts

---

## ⚙️ Features
- ✅ ESP-NOW based remote control (No Internet required)
- ✅ MQTT based web control (Internet control)
- ✅ Mode switching using push button
- ✅ LED indication for control mode
- ✅ Speed control using PWM
- ✅ Fail-safe auto stop system
- ✅ Stable long-time operation

---

## 🧩 Components Used
- ESP8266 NodeMCU (2 units: Car + Remote)
- L298N / L293D Motor Driver
- DC Gear Motors (100 RPM)
- Castor Wheel
- Rechargeable Battery
- Push Buttons (Tactile Switches)
- LEDs with Resistors
- Breadboard & Connecting Wires
- Buck Converter (Optional)

---

## 🔌 System Architecture

### 1️⃣ ESP-NOW Mode
- Used for short-range wireless control
- Does not require internet
- Fast response
- Used with physical remote

### 2️⃣ MQTT Mode
- Used for internet-based control
- Controlled using web page
- Uses public MQTT broker
- Works from anywhere

---

## 🔁 Mode Switching
A push button is used to change modes:

| Button State | Mode     | LED Status |
|-------------|----------|------------|
| Not Pressed | ESP-NOW  | OFF        |
| Pressed     | MQTT     | ON         |

---

## 🛡️ Safety System
A watchdog timer is used in the car.

If no command is received within a short time:
- Motors automatically stop
- Prevents runaway vehicle

---

## 💻 Software Used
- Arduino IDE
- ESP8266 Board Package
- PubSubClient Library
- ESP-NOW Library
- HTML + JavaScript (Web Controller)

---

## 🌐 Web Control
A web-based controller is used in MQTT mode.
It provides:
- Direction buttons
- Speed control slider
- Connection status

---

## 📊 Applications
- Robotics learning
- IoT demonstrations
- Smart vehicle research
- College exhibitions
- Automation projects

---

## 🏁 Conclusion
This project demonstrates the integration of wireless communication and IoT technology using ESP8266.

By supporting both ESP-NOW and MQTT, the system provides reliable and flexible control options.

The project helps in understanding real-time communication, embedded systems, and robotics.

---

## 👨‍💻 Developed By
**Muhammed Afkar M A**

Diploma in Electronics Engineering  
Government Polytechnic College, Kasaragod
