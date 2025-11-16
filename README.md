# 🤖 Line Follower with Power Monitoring

### 📌 Overview
This project combines a **line-following robot** with **power monitoring capabilities** using an Arduino.  
It uses IR sensors to follow a black line, an ultrasonic sensor for obstacle detection, and an LCD to display **voltage, current, and power consumption** in real time.

### ⚙️ Features
- Line following using dual IR sensors  
- Obstacle detection using ultrasonic sensor  
- Motor control with PWM speed regulation  
- Real-time voltage and current monitoring  
- LCD display showing voltage (V), current (A), and calculated power (W)

### 🛠️ Components
- Arduino UNO  
- IR Sensors (Left & Right)  
- Ultrasonic Sensor (HC-SR04 or compatible)  
- L298N Motor Driver  
- DC Motors + Wheels  
- ACS712 Current Sensor  
- Voltage Divider Circuit  
- 16x2 I2C LCD Display  
- Jumper wires  
- 9–12V Battery

### 📂 Files
- `src/LineFollower.ino` → Arduino sketch
- `images/images.txt` → images  
- `.gitignore` → ignored files configuration  
- `.gitattributes` → repository attributes  
- `README.md` → project documentation  

### 🚀 How It Works
- IR sensors detect the black line and adjust motor direction accordingly.  
- Ultrasonic sensor prevents collisions by checking distance ahead.  
- Voltage and current are measured using analog inputs and ACS712 sensor.  
- LCD displays voltage, current, and calculated power in watts.  
- Serial monitor also logs readings for debugging.

### 📚 Required Libraries
- `LiquidCrystal_I2C`  
- `Ultrasonic`  

### 🙌 Acknowledgment
Developed as part of my **Mechatronics Engineering coursework**, integrating robotics, sensor fusion, and embedded power diagnostics.
