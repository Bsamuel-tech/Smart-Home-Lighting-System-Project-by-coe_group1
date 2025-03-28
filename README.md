# Smart Home Lighting System - CoE _ GROUP 1

An Arduino-based automated lighting system with motion detection, ambient light sensing, and voice control.

# 📌 Overview
This project implements a Smart Home Lighting System that automatically controls room lights using PIR motion sensors and a photoresistor for ambient light detection. 
It features multiple control modes (automatic, manual, and voice commands) and provides real-time feedback via an LCD display and Serial Monitor.

Developed in Wokwi for simulation, this system is ideal for home automation, energy efficiency, and embedded systems learning.

# ✨ Features
Motion-Activated Lighting → Lights turn on only when motion is detected and ambient light is low.

### Three Control Modes:

Automatic Mode (default) – Smart sensor-based control.

Manual Mode – Override using physical buttons.

Voice Control Mode – Send commands via Serial Monitor.

LCD & Serial Feedback – Displays system status and sensor data.

EEPROM Storage – Remembers light sensitivity settings.

Pause/Resume Function – Temporarily disable automation.

# 🛠️ Hardware Components
Microcontroller: Arduino Uno R3

# Sensors:

3× PIR Motion Sensors (Living Room, Kitchen, Bedroom)

1× Photoresistor (Ambient Light Detection)

### Outputs:

3× LEDs (Room Lights)

16×2 I2C LCD Display

### Inputs:

2× Pushbuttons (Manual ON/OFF)

(See bom.csv for full Bill of Materials.)

# 💻 Software & Libraries
Arduino IDE

## Libraries Used:

Wire.h (I2C communication)

LiquidCrystal_I2C.h (LCD control)

EEPROM.h (storing settings)

# 📂 Project Structure
## Smart-Home-Lighting-System/  
├── code/  
│   └── SmartHomeLighting.ino  # Main Arduino code  
├── docs/  
│   ├── bom.csv               # Bill of Materials  
│   ├── schematic.pdf, design.jpg        # Circuit diagram  
│   └── Documentation & Powerpoint presentation # Full project specs  
└── README.md  
# 🚀 Setup & Usage
## 1. Tinkercad Simulation
Open the project in Tinkercad (link IS available below ).


Test using motion, light changes, and Serial commands.

## 2. Real Hardware Setup
Connect components as per the schematic.

Upload SmartHomeLighting.ino to Arduino.

Open Serial Monitor (9600 baud) for voice commands.

## 3. Available Voice Commands
### Command	Action
1	Turn ON all lights
2	Turn OFF all lights
3-5	Turn ON specific room (Living/Kitchen/Bedroom)
6-8	Turn OFF specific room
9	Switch to Automatic Mode
10	Show system status
11	Pause system
12	Resume system
13 Set light threshold (0-1023)

# 📎 Links
## Wokwi Simulation: https://wokwi.com/projects/426111984307473409

## Video Demo: https://youtu.be/zBfDvsBahwk
