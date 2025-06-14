# 🔐 Thief Detection System Using Arduino Uno

A simple and effective **intrusion detection system** using an Arduino Uno. It uses a digital sensor (like a magnetic contact sensor or IR module) to detect unauthorized access and activates a **buzzer**, **red LED**, and sends a message via **Serial Monitor**.



## 📸 Features

* 🚨 Detects unauthorized intrusion
* 🔴 Red LED + Buzzer for alert
* ✅ Green LED when all is safe
* 📟 Real-time status updates over Serial Monitor



## 🛠️ Hardware Used

| Component                 | Description                 |
| ------------------------- | --------------------------- |
| Arduino Uno               | Microcontroller             |
| Digital Sensor            | IR sensor / Magnetic switch |
| Red LED                   | Alert indication            |
| Green LED                 | Normal state indicator      |
| Buzzer                    | Alarm for intrusion         |
| Resistors                 | For LEDs (typically 220Ω)   |
| Breadboard + Jumper wires | For connections             |



## ⚡ Circuit Diagram

*(Add a diagram or Fritzing screenshot if available)*

### Pin Configuration

| Arduino Pin | Connected To  |
| ----------- | ------------- |
|  D2         | Sensor output |
|  D4         | Red LED       |
|  D5         | Green LED     |
|  D6        | Buzzer        |


## 🔧 How It Works

1. **Sensor detects intrusion (e.g., door opens)** → Input goes **HIGH**
2. Arduino turns on **Red LED** and **Buzzer**, turns off Green LED
3. Serial Monitor shows `"Thief Detected!"`
4. When sensor is **LOW**, system reverts to safe state


## ✅ Future Improvements

* Add SMS alert using GSM module
* Integrate with mobile app (via Bluetooth or Wi-Fi)
* Add LCD display for status
* Battery backup for offline use

## 📦 License

This project is for educational use. Modify and expand freely!


