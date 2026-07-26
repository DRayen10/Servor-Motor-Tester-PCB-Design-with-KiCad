# 🔧 Servo Motor Tester PCB Design (KiCad)

## 📌 Overview

This project presents a custom-designed **Servo Motor Tester PCB** developed using KiCad. The board generates precise PWM signals to control and test standard servo motors without requiring a microcontroller-based development board.

It is a compact, standalone solution ideal for testing, calibration, and educational purposes in embedded systems and robotics.

---

## ⚙️ Features

* ✅ Standalone servo control (no external MCU required)
* ✅ Adjustable PWM signal for angle control
* ✅ Compact and optimized PCB layout
* ✅ Easy-to-use interface with potentiometer control
* ✅ Standard 3-pin servo output (VCC, GND, Signal)

---

## 🧠 How It Works

The circuit generates a PWM signal (typically 50Hz) where the duty cycle controls the servo position:

* ~1 ms pulse → 0°
* ~1.5 ms pulse → 90°
* ~2 ms pulse → 180°

A potentiometer allows real-time adjustment of the pulse width, enabling smooth servo positioning.

---

## 🔌 Hardware Components

* PWM generator (e.g., NE555 Timer or equivalent)
* Potentiometer (for duty cycle control)
* Resistors and capacitors (timing circuit)
* Servo motor connector (3-pin header)
* Power supply (5V)

---

## 🖥️ PCB Design

* Designed using **KiCad**
* Includes:

  * Schematic design
  * PCB layout
  * 3D visualization
* Optimized routing for signal stability and compact size

---

## 📁 Repository Structure

```
/Hardware
  /KiCad_Files
  /Gerbers
/Schematics
/Images
README.md
```

---

## 📸 Preview

Include:

* Schematic screenshot
* PCB layout
* 3D render

---

## 🚀 Applications

* Servo motor testing & calibration
* Robotics prototyping
* Educational demonstrations
* Embedded systems learning

---

## 🛠️ Tools Used

* KiCad (PCB Design)
* Basic electronic components

---

## 📬 Author

**Rayen Dellai**
Embedded Systems & IoT Engineer

---

## ⭐ Contribution

Feel free to fork this project, suggest improvements, or use it in your own designs!

---
