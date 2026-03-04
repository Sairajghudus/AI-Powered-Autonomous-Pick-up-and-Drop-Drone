# AI Powered Autonomous Pickup and Drop Drone

An intelligent autonomous drone system capable of detecting, picking up, and delivering objects using computer vision and onboard processing. The system integrates a **Pixhawk flight controller** for flight navigation and a **Raspberry Pi Zero** for AI-based AprilTag detection, enabling precise pickup and drop operations.

---

## 📌 Project Overview

This project demonstrates an **AI-powered autonomous aerial system** designed to identify objects using **AprilTag markers**, align with the target location, and perform automated pickup and drop operations using a **gripper mechanism**.

The drone uses computer vision running on a **Raspberry Pi Zero** to detect AprilTags and estimate their position relative to the drone. Based on this information, the drone navigates precisely to the pickup location, activates the gripper to grasp the payload, and then transports it to the drop zone.

The **Pixhawk flight controller** manages stabilization, waypoint navigation, and communication with the onboard computer.

---

## 🚀 Features

- Autonomous drone navigation
- AprilTag based object detection
- Real-time computer vision processing
- Automated pickup and drop mechanism
- Integration of flight control and AI processing
- Precision landing and alignment

---

## 🧠 System Architecture

Drone System Components:

- **Pixhawk Flight Controller**
  - Handles flight stabilization and navigation
  - Executes waypoint control and autopilot features

- **Raspberry Pi Zero**
  - Runs computer vision algorithms
  - Detects AprilTags using camera input
  - Sends target position data to flight controller

- **Camera Module**
  - Captures real-time video feed
  - Used for AprilTag detection

- **Gripper Mechanism**
  - Mechanical system used for object pickup and release
  - Controlled through onboard electronics

---

## ⚙️ Hardware Components

- Pixhawk Flight Controller  
- Raspberry Pi Zero  
- Camera Module (Pi Camera)  
- Drone Frame (Quadcopter)  
- Brushless Motors & ESCs  
- Li-Po Battery  
- Gripper Mechanism   

---

## 🔄 Working Principle

1. The drone takes off using Pixhawk autopilot.
2. Raspberry Pi captures camera frames continuously.
3. AprilTags are detected using computer vision algorithms.
4. The drone calculates the relative position of the tag.
5. The drone aligns itself with the pickup point.
6. The gripper mechanism picks up the object.
7. The drone navigates to the drop zone.
8. The gripper releases the object.


## 📊 Applications

- Autonomous delivery systems  
- Warehouse logistics automation  
- Search and rescue supply delivery  
- Smart inventory transport  
- Industrial automation


## 🔮 Future Improvements

- Obstacle avoidance using LiDAR or depth cameras  
- AI-based object recognition instead of markers  
- Improved payload capacity  
- GPS-denied navigation using SLAM  
- Multi-drone coordination
