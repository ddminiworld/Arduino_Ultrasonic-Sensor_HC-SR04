# 📏 Arduino Ultrasonic Distance Measurement

This project demonstrates how to interface an **Ultrasonic Sensor (HC-SR04)** with an Arduino to measure distance in real time.

It uses trigger and echo signals to calculate the distance of an object from the sensor and displays the result via Serial Monitor.

---

## 🚀 Features

- 📡 Real-time distance measurement
- ⚡ Fast and accurate readings
- 🔌 Simple wiring and setup
- 💻 Serial Monitor output

---

## 🧰 Components Required

- Arduino Uno (or compatible board)
- HC-SR04 Ultrasonic Sensor
- Jumper wires
- Breadboard (optional)

---

## 🔌 Circuit Connections

| Ultrasonic Sensor | Arduino |
|------------------|--------|
| VCC              | 5V     |
| GND              | GND    |
| TRIG             | D3     |
| ECHO             | D2     |

---

## 🧠 Working Principle

The ultrasonic sensor emits a sound wave and waits for it to reflect back.

Distance is calculated using the formula:

Distance = (Time × Speed of Sound) / 2

Where speed of sound = 0.0343 cm/µs

---

##🔌 Circuit Diagram

<img width="949" height="491" alt="image" src="https://github.com/user-attachments/assets/893c9183-fb97-4982-bea1-76b9f75850a0" />
