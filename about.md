# VoxDrive 🚗🎤

### Voice Controlled IoT Robotic Car using MQTT

## Overview

**VoxDrive** is a voice-controlled robotic car that can be operated
using spoken commands through a web interface. The system uses **speech
recognition in the browser** to detect commands and sends them to the
car using the **MQTT protocol** over the internet.

The car receives these commands through a microcontroller connected to
WiFi and performs actions such as moving forward, backward, turning
left, turning right, stopping, or performing a dance sequence.

VoxDrive demonstrates how **voice interfaces, IoT communication, and
robotics** can be combined to create an intuitive and interactive
control system.

------------------------------------------------------------------------

## Key Features

-   🎤 Voice Command Control using Web Speech API
-   🌐 MQTT Communication for real-time command transmission
-   🚗 Wireless Car Movement Control
-   🛑 Emergency Stop Button
-   💃 Dance Mode (random movement sequence)
-   📱 Mobile-Friendly Web Interface
-   ⚡ Real-time Command Execution

------------------------------------------------------------------------

## Voice Commands

  Voice Command   Action
  --------------- ----------------------------------
  forward         Move the car forward
  backward        Move the car backward
  left            Turn left
  right           Turn right
  stop            Stop the car
  dance           Perform random movement sequence

------------------------------------------------------------------------

## System Architecture

User Voice\
↓\
Web Browser (Speech Recognition)\
↓\
Web Page sends MQTT command\
↓\
MQTT Broker (HiveMQ)\
↓\
WiFi Microcontroller (ESP8266 / NodeMCU)\
↓\
Motor Driver\
↓\
Robotic Car Movement

------------------------------------------------------------------------

## Technologies Used

-   HTML / CSS / JavaScript
-   Web Speech API
-   MQTT Protocol
-   HiveMQ MQTT Broker
-   ESP8266 / NodeMCU
-   Motor Driver (L298N / L293D)
-   WiFi Communication

------------------------------------------------------------------------

## MQTT Configuration

Topic: car/control

Example Message: forward

------------------------------------------------------------------------

## Applications

-   Voice controlled robotics
-   IoT automation systems
-   Educational robotics projects
-   Human-machine interaction research
-   Smart mobility demonstrations

------------------------------------------------------------------------

## Future Improvements

-   Wake word detection (e.g., "Hey VoxDrive")
-   AI voice assistant integration
-   Obstacle detection with ultrasonic sensors
-   Autonomous navigation mode
-   Mobile app integration

------------------------------------------------------------------------

## Project Name

**VoxDrive -- A Voice Controlled IoT Robotic Car**

------------------------------------------------------------------------

## Author

Muhammed Afkar M A\
Ahban Ahmed\
Vishakh C\
Gopika V S\
\
\
\
Electronics Engineering\
Government Polytechnic College K

asaragod
