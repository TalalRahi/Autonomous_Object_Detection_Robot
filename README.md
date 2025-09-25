# Autonomous Object Detection Robot  
**Using Arduino, ESP-32 CAM, Cloud & Telegram Bot**  

🚀 A low-cost autonomous robot that can move on its own, avoid obstacles, and detect sharp objects using sensors and a camera.  
📸 Captured images are analyzed in the cloud, and if the target object is found, a **Telegram alert** is sent to the user.  
🔋 Powered by rechargeable batteries, making it eco-friendly and sustainable.  

---

## 📖 Project Overview  
This project was developed as part of **CSE461: Introduction to Robotics** at BRAC University.
The robot integrates microcontrollers, sensors, cloud services, and messaging to create an autonomous system that can:  

- Move independently and avoid obstacles.  
- Capture images and send them to the cloud for object recognition.  
- Detect a specific object (e.g., scissors).
- Send **real-time alerts** via Telegram bot.  
- Run on rechargeable Li-ion batteries for sustainability.  

---

## ⚡ Features  
- ✅ Autonomous movement & obstacle avoidance.  
- ✅ Object detection using **ESP32-CAM** and cloud-based recognition.  
- ✅ Real-time **Telegram alerts** when the object is detected.  
- ✅ Low-cost & reconfigurable design.  
- ✅ Eco-friendly with rechargeable power.  

---

### Hardware  
- Arduino Nano (Main Controller)  
- ESP32-CAM (Image capture & WiFi communication)  
- L298N Motor Driver  
- 4-Wheel Robot Chassis  
- HC-SR04 Ultrasonic Sensors (x4)  
- 18650 Li-ion Rechargeable Batteries + Charger  
- USB to TTL FTDI  
- Buck Converter  
- On-off switches, jumper wires, zip ties  

---

### Software  
- Arduino IDE  
- ESP32 Camera Library  
- Google Colab (Cloud-based object detection)  
- Ngrok (Tunneling service)  
- Telegram Bot API  

---

## ⚠️ Challenges  
- Powering the ESP32-CAM caused boot issues → fixed with a buck converter.  
- Poor image clarity while moving → solved by pausing for 15s during capture.  

---

## 🌱 Sustainability & Impact  
- Runs on **rechargeable batteries** → reduces electronic waste.  
- Flexible and modular design → reusable parts, lower maintenance.  
- Can be used in **industries, defense, and small-scale monitoring tasks**.  

---

## 🔮 Future Work  
- Add 3D mapping & real-time object detection.  
- Make it outdoor-friendly with protective casing.  
- Improve sensors for better navigation.  
- Integrate **on-device AI** to reduce cloud dependency.  
- Explore solar charging & multi-robot coordination.  

---

## 📚 References  
- [Programming the ESP32-CAM using USB to TTL converter](https://www.youtube.com/watch?v=y3RcDDzeXDM)  
- [How to Make Arduino Obstacle Avoiding Robot](https://www.youtube.com/watch?v=etVX0XkBX4o)  

---

## 📜 License  
This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  
