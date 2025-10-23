# 🛫 Model of the Boeing MCAS System
### 🚀 Best Creative Project — ECE-3155 Electronics Laboratory, University of Houston  
**Project Lead & Programmer:** *Len Johns Shaji*  
**Instructor:** Dr. John C. Wolfe  
**Date:** December 9, 2023
## 🎬 Demonstration Video

Check out our project in action on YouTube:  
[![Boeing MCAS System Video](https://img.youtube.com/vi/hT2mqvJtXzM/0.jpg)](https://youtube.com/shorts/hT2mqvJtXzM?si=KA-6GnaE8OkaQ1om)

---

## 📘 Overview

This project models the **Maneuvering Characteristics Augmentation System (MCAS)** used in the Boeing 737 MAX aircraft.  
Our objective was to design and prototype a **functional replica** of the MCAS system that could dynamically stabilize a model aircraft using real-time sensor data.

Originally conceived as a wind tunnel test system, the project evolved into a fully functional **servo control system with an Arduino-based feedback loop**, integrating gyroscope and accelerometer data from the **MPU-6050 (GY-521)** sensor.

> 🧠 This project showcases a complete cycle of **hardware design, microcontroller programming, system integration, and iterative troubleshooting** — culminating in the *Best Creative Project* award.

---

## ⚙️ System Components

### Hardware:
- **Arduino Mega 2560**
- **GY-521 (MPU-6050)** Accelerometer & Gyroscope
- **Two Servo Motors** for tail stabilizers
- **555 Timer Servo Controller Circuit**
- **LCD Displays** for pitch/roll and system status
- **LED Indicators & Passive Buzzer**

### Software:
- Programmed using **Arduino IDE (C/C++)**
- Real-time sensor calibration and filtering
- LED visualization for pitch-up/pitch-down
- Servo control logic for tail wing stabilization
- Safety logic with automatic system disengagement when AOA limits exceeded

---

## 🧩 My Contributions

As **Project Lead and Programmer**, I was responsible for:
- Writing and debugging the **Arduino code** integrating all system components
- Designing the **servo control logic** based on sensor feedback
- Implementing **LCD and LED display control**
- Overseeing **project architecture**, testing, and demonstration
- Coordinating the team workflow and final presentation

---

## 🔬 Key Features

- **Real-Time Flight Simulation:** Calculates and adjusts for pitch and roll.
- **Failsafe Mechanism:** Automatically deactivates MCAS when unsafe conditions are detected.
- **User Feedback Interface:** LCD displays, LEDs, and buzzer alerts.
- **PWM Signal Control:** Custom-built 555 timer circuit for servo precision.
- **Adaptive Design:** Shifted from a full wind tunnel model to an integrated servo feedback system.

---

## 📄 Documentation

For complete technical details, including circuit schematics, test results, and design theory, refer to the full report:  
📘 [Formal Report - Boeing MCAS System (PDF)](Formal%20Report%20_%20Boeing%20MCAS%20System.pdf)

---

## 🛠️ Code

The Arduino source file used for this project:  
📂 [`Boeing_MCAS_System.ino`](Boeing_MCAS_System.ino)

---

## 🏆 Recognition

This project was recognized as the **Best Creative Project** for ECE-3155 Electronics Laboratory (Fall 2023) for its **innovative design, problem-solving, and teamwork**.

---

## 🙏 Acknowledgements

- **Dr. John C. Wolfe** — Course Instructor  
- **IEEE - University of Houston**  
- **3D Lab Print** and **Joop Brokking** for open-source references  
- **Team Members:**  
  - Michael Iheagwara – Circuit Designer  
  - Len Johns Shaji – Programmer & 3D Designer *(Lead)*  
  - Ethan Tran – Assembler  
  - Muskaan Trivedi – Circuit Designer  
  - Anh Nguyen – Circuit Tester  

---

### 🧠 Keywords
`Arduino` `MCAS` `Electronics Project` `Servo Control` `MPU-6050` `555 Timer` `Flight Stability` `University of Houston`

---
