# 🤖 Multipurpose Obstacle Avoiding Robot

A smart autonomous obstacle avoiding robot developed using Arduino Uno, ultrasonic sensor, servo motor, motor shield, and DC motors for intelligent robotic navigation and automation applications.

The robot can automatically detect obstacles, scan surroundings, and choose the safest direction for movement without human intervention.

---

# 🚀 Features

✅ Automatic obstacle detection  
✅ Autonomous navigation  
✅ Left/right environmental scanning  
✅ Smart direction selection  
✅ Smooth motor speed control  
✅ Collision avoidance system  
✅ Real-time distance sensing  
✅ Multipurpose robotic applications  

---

# 🛠 Components Used

| Component | Quantity | Purpose |
|---|---|---|
| Arduino Uno | 1 | Main controller |
| HC-SR04 Ultrasonic Sensor | 1 | Distance measurement |
| Servo Motor (SG90) | 1 | Sensor rotation/scanning |
| L293D Motor Shield | 1 | Motor control |
| DC Motors | 4 | Robot movement |
| Wheels | 4 | Mobility |
| Robot Chassis | 1 | Robot body/frame |
| Battery Pack (7.4V/9V-12V) | 1 | Power supply |
| Jumper Wires | Multiple | Connections |

---

# 🔍 Working Principle

The robot continuously measures the front distance using the ultrasonic sensor.

When an obstacle is detected:
1. Robot stops
2. Moves backward
3. Servo scans left and right
4. Distances are compared
5. Robot turns toward the safer direction
6. Movement continues automatically

---

# ⚙️ Technologies Used

- Embedded Systems
- Arduino Programming
- Sensor Interfacing
- Robotics
- Autonomous Navigation
- Motor Control

---

# 📡 Hardware Architecture

```text
Ultrasonic Sensor
        ↓
   Arduino Uno
        ↓
  Motor Shield
        ↓
    DC Motors
        ↓
 Robot Movement
```

---

# 🔌 Pin Configuration

| Device | Arduino Pin |
|---|---|
| Ultrasonic TRIG | A0 |
| Ultrasonic ECHO | A1 |
| Servo Motor | D10 |
| Motor Shield | Motor Ports |

---

# 🧠 Functionalities

## Obstacle Detection
Uses ultrasonic waves to measure object distance.

## Autonomous Navigation
Automatically changes direction when obstacles are detected.

## Smart Scanning
Servo motor rotates sensor left and right for better environmental analysis.

## Smooth Movement
Gradual speed control reduces jerking and improves movement stability.

---

# 🌍 Applications

- Smart Robotics
- Surveillance Robots
- Military Prototype Robots
- Rescue Robots
- Educational Robotics
- Automation Systems


---
