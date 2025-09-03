# 🚗 Obstacle Avoidance Using LIDAR (A2M12)

This project demonstrates an autonomous obstacle avoidance system using the **RPLIDAR A2M12** sensor. Our mobile robot continuously scans its environment up to a range of **12 meters**, detecting obstacles in real-time with high accuracy. Using this data, the robot navigates autonomously by following predefined waypoints (waypoint navigation) while dynamically avoiding obstacles detected on its path.

---

## 🔧 Hardware & Software Used

* **LIDAR Sensor:** RPLIDAR A2M12 (360° scanning, 12-meter range)
* **Software:** ROS2 (Robot Operating System), Rviz visualization tool
* **Programming Languages:** Python / C++
* **Platform:** Linux (Recommended: Ubuntu 20.04)

---

## 📸 Media & Visuals

### 1️⃣ LIDAR Data Visualization in RViz

The image below shows real-time LIDAR data visualized in RViz. You can see how the environment is mapped using 360° laser scans, providing detailed obstacle detection around the robot:

<p align="center">
  <img width="500" height="400" src="https://github.com/user-attachments/assets/ec29c0f5-37df-4510-910d-3d595c0aa04b" alt="LIDAR Rviz Visualization" />
</p>

---

### 2️⃣ Obstacle Avoidance in Action

Watch our robot operating in **guided mode**, where it follows predefined waypoints (WPs) while continuously scanning for obstacles. Upon detecting an obstacle within its path, the robot dynamically recalculates its trajectory to avoid collisions, demonstrating real-time obstacle avoidance using the LIDAR sensor's data.

<p align="center">
  <a href="https://github.com/user-attachments/assets/ed6155cc-a795-47cf-8023-a5143c509781">
    🎥 Watch the Obstacle Avoidance Video
  </a>
</p>

---

### 3️⃣ Our Robot Platform

Here’s a photo of the robot used in this project, equipped with the RPLIDAR A2M12 sensor and necessary computing hardware to perform autonomous navigation and obstacle avoidance:

<p align="center">
  <img width="500" height="400" src="https://github.com/user-attachments/assets/0261b159-366f-4a95-b76e-e86b9b0f8177" alt="Our Robot Platform" />
</p>

