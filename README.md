# 🤖 Arduino HC-05 Bluetooth Controlled Robot

🔧 Developed using **Arduino (UNO/Nano)** and **Embedded C (Arduino IDE)**  
📱 Controlled wirelessly via **HC-05 Bluetooth Module** and Android app

---

## 📚 Table of Contents

- [📌 Project Overview](#-project-overview)
- [🎯 Features](#-features)
- [🧰 Tools & Technologies](#-tools--technologies)
- [📁 File Structure](#-file-structure)
- [🔧 Hardware Setup](#-hardware-setup)
- [🚀 How to Run the Project](#-how-to-run-the-project)
- [📈 Output & Demo](#-output--demo)
- [🧠 Circuit Design](#-circuit-design)
- [🙋‍♂️ Developer Info](#-developer-info)
- [🏷️ Tags](#-tags)

---

## 📌 Project Overview

This project demonstrates a **Bluetooth-controlled robotic vehicle** using an
**Arduino microcontroller**. The robot receives commands from a **mobile
Bluetooth application** and moves accordingly.

🎯 Purpose of the project:
- Learn Bluetooth-based wireless communication
- Understand motor driver interfacing
- Implement real-time embedded control logic

📹 A real working demo video is included in this repository.

---

## 🎯 Features

✨ Wireless Bluetooth control  
📱 Android mobile app interface  
⚙️ Forward, backward, left & right motion  
🔁 Real-time response  
🔋 Battery powered  
📹 Real working prototype (video proof)

---

## 🧰 Tools & Technologies

| Tool / Component | Usage |
|------------------|------|
| Arduino UNO / Nano | Main controller |
| HC-05 Bluetooth Module | Wireless communication |
| L298N Motor Driver | Motor control |
| Arduino IDE | Programming |
| Git & GitHub | Version control |
| Markdown | Documentation |

---

## 📁 File Structure

Arduino-Bluetooth-Controlled-Robot/
├── code/
│ └── arduino_bluetooth_robot.ino
├── circuit/
│ └── connection_diagram.png
├── demo/
│ └── working_video.mp4
└── README.md


---

## 🔧 Hardware Setup

### 🔌 Components Used
- Arduino UNO / Nano  
- HC-05 Bluetooth Module  
- L298N Motor Driver  
- DC Motors  
- Battery Pack  
- Robot Chassis & Wheels  

### 🔗 Connection Summary
- HC-05 TX → Arduino RX  
- HC-05 RX → Arduino TX (via voltage divider)  
- L298N IN pins → Arduino digital pins  
- ENA & ENB → PWM pins  

*(Refer to circuit diagram in the `circuit/` folder)*

---

## 🚀 How to Run the Project

### 🛠️ Step-by-Step Instructions

1. Open **Arduino IDE**
2. Load `arduino_bluetooth_robot.ino`
3. Select correct **Board** and **COM Port**
4. Upload the code to Arduino
5. Power the robot
6. Pair HC-05 with mobile (default PIN: `1234`)
7. Send commands from Bluetooth app

### 📲 Control Commands

| Command | Action |
|--------|--------|
| F | Forward |
| B | Backward |
| L | Left |
| R | Right |
| S | Stop |

---

## 📈 Output & Demo

### 🤖 Robot Behavior
- Responds instantly to Bluetooth commands
- Moves smoothly in all directions

📹 Demo video available in:

---
## 🎥 Project Demo Video

▶️ Watch the working demo here:  
https://github.com/krishisharma301/Arduino-Bluetooth-Controlled-Robot/blob/main/demo/Workingvideo.mp4


## 🙋‍♂️ Developer Info

👤 **Krushna Sharma**  
🎓 Robotics & Automation Engineering Student  
🔗 GitHub: https://github.com/krishisharma301  
🔗 LinkedIn: https://linkedin.com/in/www.linkedin.com/in/krushna-sharma-612575324

---

## 🏷️ Tags

`#Arduino` `#BluetoothRobot` `#EmbeddedSystems` `#Robotics`  
`#HC05` `#L298N` `#EngineeringProject` `#Internship`
