# 🚦 Smart Traffic Light System with Pedestrian Countdown (Arduino Simulation)

A **smart traffic light system** built with **Arduino Uno** and simulated using **Wokwi**.  
This project demonstrates how **embedded systems** can control traffic lights and allow pedestrians to cross safely using a button-triggered countdown.

---

## 🔹 Features

- Automatic **traffic light cycle** (Green → Yellow → Red)  
- **Pedestrian crossing button** triggers the countdown  
- **Visual countdown** using pedestrian LED (blinks 5 times for a 5-second crossing)  
- Fully simulated in **Wokwi**, no physical hardware required  
- Clean, easy-to-read **Arduino C++ code**  

---

## 🔹 Tools & Technologies

- **Hardware Simulation:** [Wokwi Arduino Simulator](https://wokwi.com/)  
- **Microcontroller:** Arduino Uno  
- **Programming Language:** C++ (Arduino)  
- **Components:**  
  - Red, Yellow, Green LEDs (traffic lights)  
  - Green LED for pedestrian crossing  
  - Push button  
  - 220Ω resistors  

---

## 🔹 Circuit Diagram

![Traffic Light Circuit Diagram](your_image_here.png)  
*(Replace with a screenshot from Wokwi simulation)*

- All LEDs connected to Arduino digital pins with 220Ω resistors  
- Pedestrian button connected to **Pin 2** (with INPUT_PULLUP)  
- Pedestrian LED connected to **Pin 10**  
- GND shared across all LEDs

---

## 🔹 How It Works

1. **Normal Traffic:** Green light ON → cars go  
2. **Button Pressed:** Pedestrian requests crossing  
3. Yellow light ON for 2 seconds → prepare to stop  
4. Red light ON → cars stop, pedestrian LED blinks **5 times** (5-second countdown)  
5. System resets → Green light ON

---
