# Ultrasonic Obstacle Detection System using Arduino

This project is a simple, cost-effective distance measurement and obstacle detection system using an **HC-SR04 ultrasonic sensor** and **Arduino UNO**. When an object is detected within a predefined range, a **buzzer** is activated and an **LED** lights up as an alert mechanism.

> 🎓 **This project was created as part of a college micro-project to demonstrate real-time obstacle detection using embedded systems.**

---

## 🔧 Components Used

- Arduino UNO  
- HC-SR04 Ultrasonic Sensor  
- Piezo Buzzer  
- LED  
- Breadboard & Jumper Wires  
- USB Cable for programming

---

## ⚙️ How It Works

1. The ultrasonic sensor continuously measures the distance to the nearest object.
2. The Arduino calculates the distance using the time taken for the echo signal to return.
3. If the distance is less than the defined threshold (e.g., 10 cm), the buzzer and LED are activated.
4. If no object is detected within the range, the system stays silent and the LED is off.

---

## 📂 Project Structure

