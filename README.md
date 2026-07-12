# 🔋 Battery Health Monitoring System (BHMS)

Welcome to the BHMS project! This system is designed to monitor the critical parameters of a battery to ensure safety and longevity.

## 📸 System Overview

*(Please place your system picture here, name it `system_picture.png` and it will appear below)*
![BHMS System](system_picture.png)

## 🛠️ Components Used
- **Voltage Sensor**: Measures the real-time battery voltage.
- **Current Sensor**: Monitors the charge and discharge current.
- **Temperature Sensor**: Ensures the battery is operating within safe thermal limits.
- **Microcontroller**: Processes the sensor data.

## 🧮 Calculations
This project calculates two primary metrics using formulas inspired by community discussions and social media:
1. **SOC (State of Charge)**: Estimates how much battery capacity is remaining.
2. **SCD**: Evaluates the battery's condition based on the applied formula.

## 💻 Code Structure
- `bhms.ino`: The main microcontroller firmware file containing the setup and loop functions to read sensor data and apply the SOC/SCD formulas.

## 🚀 How to Use
1. Wire the sensors to your microcontroller's analog pins.
2. Open `bhms.ino` in your Arduino IDE.
3. Upload the code to your board.
4. Open the Serial Monitor at `9600` baud rate to see real-time battery data.
