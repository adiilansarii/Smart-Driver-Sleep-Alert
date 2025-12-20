# Smart Driver Drowsiness Detection & Safety System 🚗👓

This project is a **hardware-based driver safety system** designed to detect **driver drowsiness using eye-blink inactivity** and prevent accidents by **triggering an alarm and automatically stopping the vehicle motor**.

The system focuses on **real-time detection, low-latency response, and wireless control**, making it suitable for safety-critical applications.

---

## 🎯 Problem Statement

Driver fatigue is one of the major causes of road accidents.  
Delayed human reaction during drowsiness can lead to severe consequences.

This system detects prolonged eye closure and **responds automatically within seconds**, without relying on driver intervention.

---

## ⚙️ System Overview

- Continuously monitors eye-blink activity using an IR sensor  
- Detects drowsiness after **3 seconds of eye inactivity**  
- Sends wireless alert signals using RF communication  
- Triggers an alarm and **cuts off the motor power automatically**  

---

## 🧩 Components Used

> 📌 Add clear images of each component inside a `screenshots/` or `images/` folder.

### Hardware Components
<!-- Add components image here -->
![Components](./screenshots/components.png)

- Arduino Nano  
- IR Eye-Blink Sensor  
- 433 MHz RF Transmitter & Receiver  
- HT12E / HT12D Encoder–Decoder  
- 5V Relay Module  
- DC Motor  
- Buzzer / Alarm  
- 9V Power Supply  

---

## 🏗️ Working Principle

1. IR eye-blink sensor continuously tracks eye movement  
2. If eyes remain closed for **≥ 3 seconds**, drowsiness is detected  
3. RF module transmits a wireless signal to the receiver unit  
4. Alarm is activated immediately  
5. Relay cuts off motor power to stop the vehicle  

---

## 📸 Project Demonstration

### Eye-Blink Detection Setup (Glasses)
<!-- Add image of glasses with eye sensor here -->
![Eye Sensor Glasses](./screenshots/eye-glasses.png)

### Final Vehicle Safety Model
<!-- Add image of final car setup here -->
![Final Car Setup](./screenshots/car-setup.png)

---

## ⏱️ Performance Metrics

- Drowsiness detection delay: **~3 seconds**  
- Wireless response latency: **< 100 ms**  
- Continuous stable operation during testing  
- Reliable motor cutoff using relay-based control  

---

## 🔌 Circuit Design

- IR sensor connected to Arduino input pins  
- RF transmitter connected to encoder (HT12E)  
- RF receiver connected to decoder (HT12D)  
- Relay controlled via Arduino output  
- Motor power routed through relay for safety cutoff  

---

## 🚧 Future Improvements

- Camera-based eye tracking for higher accuracy  
- Adjustable drowsiness threshold  
- GSM-based alert to emergency contacts  
- Integration with vehicle dashboard system  

---

## 👨‍💻 Author

**Adil Ansari**  
B.Tech (ECE), Netaji Subhas University of Technology  

---

⭐ A practical hardware solution aimed at reducing accidents caused by driver fatigue.
