<!-- Logo -->
<p align="center">
  <img src="ShobdoBondhu_Logo.png" alt="ShobdoBondhu Logo" width="500"/>
</p>

<!-- Title Banner -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%A4%96%20ShobdoBondhu&fontSize=36&width=1200&height=150&color=0:36BCF7,100:0f2027"/>
</p>

<h3 align="center">
  <b style="color:purple;">🤖 Voice-Controlled & Obstacle-Avoiding Robot</b>
</h3>

<h3 align="center">
  <b>📱 Mobile-Integrated Arduino Robot for Smart Navigation</b>
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Arduino-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Language-C%2B%2B-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/Mobile%20Control-Bluetooth-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Components-Ultrasonic%20%7C%20Servo%20%7C%20Motors-yellow?style=for-the-badge">
  <img src="https://img.shields.io/badge/Status-Functional-success?style=for-the-badge">
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Overview Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%93%8C%20Overview&fontSize=32&width=1200&height=130&color=0:9D50BB,100:6E48AA" width="100%">

**ShobdoBondhu (শব্দবন্ধু)** is a **voice-controlled and obstacle-avoiding Arduino robot** that combines **mobile-based voice commands** (both English & Bangla) with **autonomous navigation**.

It listens to verbal instructions via a smartphone app, interprets them through a Bluetooth module, and navigates safely using an ultrasonic sensor mounted on a servo motor. If an obstacle is detected, it intelligently scans its surroundings and chooses a clear path.

**Key Highlights:**
- Supports **English and Bangla voice commands**  
  Example commands:  
  - English: `*Left#`, `*Right#`, `*Forward#`, `*Backward#`  
  - Bangla: `*বামে#` (Left), `*ডানে#` (Right), `*সামনে#` (Forward), `*পিছনে#` (Backward)  
- Combines voice command recognition with obstacle avoidance
- Demonstrates Arduino robotics, Bluetooth communication, and sensor integration
- Designed for real-world testing, fun demonstrations, and learning robotics principles

**Keywords:** Arduino robot, voice control, Bangla commands, obstacle avoidance, mobile integration, ultrasonic navigation

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Objectives -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%8E%AF%20Objectives&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

- 🎯 Design and assemble a voice-controlled mobile-integrated robot  
- 🔄 Enable autonomous obstacle detection and navigation  
- 🤖 Demonstrate Arduino-based robotics integration  
- 📊 Build a demo-ready, deployable robot for education or hobby use  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- Components & Cost -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%92%B0%20Components%20and%20Cost&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

<div align="center">

| Component | Quantity | Cost (BDT) |
|-----------|---------|------------|
| Arduino UNO | 1 | 760 |
| Motor Shield (LS293L) | 1 | 200 |
| Bluetooth Module (HC-05) | 1 | 260 |
| 4D Car Set | 1 | 750 |
| Ultrasonic Sensor | 1 | 100 |
| Servo Motor | 1 | 130 |
| Jumper Wires | 10 | 25 |
| Battery Case | 1 | 35 |
| **Total Cost** |  | **2,260/=** |

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Features -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%9C%A8%20Key%20Features&fontSize=32&width=1200&height=130&color=0:FC5C7D,100:FF416C" width="100%">

- 🔊 Voice Command Control via Smartphone App (English & Bangla)  
- 🚦 Obstacle Detection & Autonomous Navigation  
- 🔄 Real-time Path Scanning using Ultrasonic Sensor  
- 🛠 Arduino UNO + Motor Shield + Servo Integration  
- 📡 Bluetooth Communication for Command Transmission  
- ⚡ Easy Assembly and Customization  
- 🏃 Demonstrates Movement, Turn, Stop, and Path Selection  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">

<!-- System Implementation -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=System%20Implementation&fontSize=32&width=1200&height=130&color=0:6A82FB,100:FC5C7D" width="100%">

### 📷 Robot Setup & Screens
The ShobdoBondhu robot setup integrates Arduino UNO, Motor Shield, Bluetooth, Servo, and Ultrasonic Sensor for voice-controlled movement and obstacle avoidance.

**Circuit Components:**
- Arduino UNO
- Motor Shield (LS293L)
- Bluetooth Module (HC-05)
- Ultrasonic Sensor on Servo Motor
- 4D Car Chassis
- Battery & Wiring

**Voice Commands Supported:**
- **English:** *Left#, *Right#, *Forward#, *Backward#  
- **Bangla (বাংলা):** *বাম#, *ডান#, *সামনের#, *পিছনের#  

**Obstacle Detection:**
- Continuously scans ahead using ultrasonic sensor
- Stops if obstacle detected
- Rotates servo to scan left and right
- Selects a clear path to continue

**Assembly Notes:**
- 4D car chassis as base
- Arduino + Motor Shield mounted on chassis
- Sensors fixed for optimal coverage
- Bluetooth module connected for mobile commands

<div align="center">
<img src="Images/robot_front.jpg" width="300" />
<img src="Images/robot_top.png" width="300" />
<p><b>ShobdoBondhu Robot in Action</b></p>
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Project Structure -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%93%82%20Project%20Structure&fontSize=32&width=1200&height=130&color=0:36BCF7,100:0f2027" width="100%">

```bash
ShobdoBondhu/
│── Arduino_Code/
│ ├── VoiceControl.ino
│ ├── ObstacleAvoidance.ino
│── Mobile_App/
│ ├── VoiceCommandApp/
│── Circuit_Diagram/
│── README.md
│── Images/
│── Documentation/
```

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Setup & Usage -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%9A%80%20Setup%20&%20Usage&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

**Steps to Run:**  
1. Assemble the 4D car chassis with Arduino UNO and Motor Shield  
2. Mount the Ultrasonic Sensor on a servo motor  
3. Upload the `VoiceControl.ino` and `ObstacleAvoidance.ino` sketches to Arduino  
4. Connect the Bluetooth module (HC-05) to Arduino pins  
5. Install the Voice Command App on a smartphone  
6. Pair the app with the Bluetooth module and send commands (English or Bangla, e.g., `*বামে#`)  
7. Test obstacle avoidance and movement  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">


<!-- Future Work -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%94%AE%20Future%20Enhancements&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">

- 📡 Advanced voice recognition with multiple languages  
- 🤖 AI-based obstacle mapping & autonomous path optimization  
- 💬 Smartphone app enhancements (GUI, feedback)  
- 🔋 Battery monitoring & efficiency improvements  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">



<!-- Conclusion -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%9C%85%20Conclusion&fontSize=32&width=1200&height=130&color=0:6A82FB,100:FC5C7D" width="100%">

**ShobdoBondhu** is a complete, deployable Arduino robot demonstrating **voice-controlled navigation and obstacle avoidance** in **English and Bangla**.  

It serves as a **learning platform, hobby project, or prototype for real-world robotics applications** while being modular and extendable for future improvements.
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">



<!-- Author -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%F0%9F%91%A8%E2%80%8D%F0%9F%92%BB%20Author&fontSize=32&width=1200&height=130&color=0:00F260,100:0575E6" width="100%">

### A. K. M. Masudur Rahman (Gaurab)   
🎓 Department of Computer Science and Engineering (CSE)  
🏫 Bangladesh Army University of Science and Technology (BAUST), Saidpur  
📧 Email: akmmasudurrahmangaurab@gmail.com  

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">



<!-- Support -->
<img src="https://capsule-render.vercel.app/api?type=waving&text=%E2%AD%90%20Support&fontSize=32&width=1200&height=130&color=0:FF416C,100:FF4B2B" width="100%">
If you like this project, consider giving it a ⭐ on GitHub!
<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif" width="100%">
