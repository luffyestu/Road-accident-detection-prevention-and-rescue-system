# 🚨R Accident Detection, Prevention, and Rescue System

A smart embedded system that detects vehicle collisions, prevents accidents using proximity alerts, and initiates emergency rescue by sending real-time GPS coordinates via SMS.

---

## 📌 Project Overview

This project is designed to enhance **road safety** using embedded technology. It combines accident detection, prevention, and automated rescue triggering in a single low-cost solution. It is especially useful for vehicles in remote or high-risk zones.

---

## ⚙️ Features

- **Accident Detection**  
  Detects sudden impact using vibration and accelerometer sensors.

- **Collision Prevention**  
  Uses ultrasonic sensors to measure distance from obstacles and alert the driver if they're too close.

- **Rescue System**  
  Automatically sends GPS coordinates via SMS to pre-defined emergency contacts when an accident is detected.

- **Driver Alert System**  
  Buzzer and LCD warnings for unsafe driving conditions (e.g., over-speeding, object detection).

---

## 🔩 Hardware Components

| Component             | Description                        |
|----------------------|------------------------------------|
| Arduino UNO          | Microcontroller                    |
| Ultrasonic Sensor    | Obstacle detection                 |
| Accelerometer        | Detect sudden impact               |
| Vibration Sensor     | Detects collision or shake         |
| GSM Module (SIM800L) | Sends SMS with accident data       |
| GPS Module (Neo-6M)  | Fetches real-time location         |
| Buzzer + LCD         | Alerts and display warnings        |
| Power Supply         | 9V Battery or USB Power            |

---

## 🛠️ Software and Tools

- Embedded C / Arduino IDE
- Serial Monitor for testing
- Proteus (optional for simulation)
- Fritzing (for circuit design)

---

## 📍 Working Principle

1. Sensors continuously monitor the vehicle for abnormal motion or close obstacles.
2. If a sudden impact is detected:
   - Location is fetched via GPS.
   - SMS is sent to emergency contacts using GSM.
   - Buzzer alerts are activated.
3. The driver receives real-time alerts during near-collision scenarios to prevent accidents.

---

## 🧠 Applications

- Smart vehicles and public transport safety
- Long-distance travel safety system
- Emergency response systems for remote areas
- School buses and logistics vehicles

---

## 📸 Screenshots / Media (Optional)

> Add pictures of your circuit, output screenshots, or simulation results here

---

## 🚀 Getting Started

### 🔧 How to Run

1. Upload the Arduino code to your microcontroller.
2. Power the system using USB or battery.
3. Connect GPS and GSM modules as per circuit diagram.
4. Adjust sensor sensitivity if needed.
5. Test by simulating a collision and observing the rescue alert.

---

---

## 👨‍💻 Author

**Athullya Kumar**  
Varkala, Kerala, India  
📧 athullyakumae@gmail.com  


---

## 📄 License

This project is open-source and available under the MIT License.
