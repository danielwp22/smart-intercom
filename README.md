# Smart Door Intercom (Raspberry Pi 5 + Arduino + IoT)

A **smart intercom and access control system** built using a **Raspberry Pi 5, Arduino, and Pi Camera**, inspired by [Edouard Renard’s Udemy course](https://www.udemy.com/course/raspberry-pi-and-arduino/).  
The system integrates **computer vision, IoT messaging, and hardware control** to provide remote visitor approval via Telegram.

---

## 📌 Features
- **Visitor Detection**
  - Pi Camera captures a photo when a button is pressed at the door.
  - Photo is automatically sent to the user via **Telegram bot**.

- **Remote Approval**
  - User can reply **“yes” or “no”** directly in Telegram.
  - Response is sent back to the Raspberry Pi.

- **Door Control**
  - Raspberry Pi communicates with an **Arduino over serial**.
  - Arduino drives a servo motor to **unlock the door** on approval.

---

## 🛠️ Tech Stack
- **Languages:** Python, Arduino C++  
- **Frameworks/Tools:** Raspberry Pi OS, Arduino IDE, OpenCV, Telegram Bot API  
- **Hardware:** Raspberry Pi 5, Arduino board, Pi Camera, Servo Motor, Push Button  

---

## 🚀 How It Works
1. **Button Pressed** → Arduino signals Raspberry Pi over serial.  
2. **Pi Camera** takes a snapshot and sends it to Telegram.  
3. **User Responds** in Telegram (“yes” or “no”).  
4. **Raspberry Pi** parses the reply and sends a command back to Arduino.  
5. **Servo Motor** rotates to unlock the door if approved.  

---

## 📷 Picture of setup
![Photo](https://i.imgur.com/1ZyZ3eJ.png)

---

## 📚 Learning Outcomes
- Gained experience integrating **Raspberry Pi and Arduino** in a hybrid IoT project.  
- Practiced **serial communication** between microcontrollers.  
- Implemented **Telegram bot automation** for real-time user interaction.  
- Applied **computer vision and hardware control** in a practical access-control scenario.  

---

## 🔗 References
- [Raspberry Pi and Arduino – Master Programming and IoT (Udemy, Edouard Renard)](https://www.udemy.com/course/raspberry-pi-and-arduino/)  
