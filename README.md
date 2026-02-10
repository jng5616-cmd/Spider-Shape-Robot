# Project ARACHNE 🕷️
### Bio-Inspired Modular Hexapod for Search and Rescue (SAR)

Status: In progress

**Project ARACHNE** is an open-source robotics project developed by a team of Year 2 Mechatronics students. Our goal is to build a highly mobile, 18-DOF hexapod robot designed to navigate disaster zones where wheeled robots fail.

---

## 🚀 The Vision
In Search and Rescue (SAR) missions, terrain is unpredictable. ARACHNE uses **Inverse Kinematics (IK)** and a bio-inspired 6-legged design to maintain stability on rubble, climb small obstacles, and eventually serve as a node in a decentralized robot rescue network.

## 🛠️ Key Features (Roadmap)
- **18-DOF Locomotion:** 3-DOF per leg for full XYZ movement.
- **Inverse Kinematics Engine:** Real-time coordinate-based leg control.
- **Modular Design:** 3D-printed parts designed for quick field repairs.
- **Autonomous Navigation:** Obstacle avoidance using Ultrasonic/LiDAR.
- **Swarm Potential:** Designed to be lightweight and low-cost for multi-robot deployment.

## 💻 Tech Stack
**Hardware:** ESP32 (Main Controller), PCA9685 (PWM Driver), MG996R Servos.
**Software:** C++/Arduino or Python.
**Mechanical:** Fusion 360 (CAD), 3D Printed PLA/ABS.
**Algorithms:** Inverse Kinematics (Trigonometric Model), Tripod Gait Logic.

## 📂 Project Structure
```text
├── CAD/              # STL and Step files for 3D printing
├── Firmware/         # Arduino/ESP32 source code
├── Docs/             # Technical reports and Math calculations
├── Circuit/          # Wiring diagrams and Schematics
└── Assets/           # Project images and videos
