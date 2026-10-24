# Hi, I'm Venkatesh 👋

**M.Sc. AI & Robotics student at Hochschule Hof, Germany**. I build robots in simulation and connect them to real hardware.
Currently: **NVIDIA Isaac Sim · ROS 2 · embedded systems (ESP32)** · open to **Werkstudent** roles in robotics & simulation.

---

### 🚀 Featured project: ESP32 × ROS 2 × NVIDIA Isaac Sim

<a href="https://github.com/Vvp999/esp32-isaac-sim-teleop">
  <img src="https://raw.githubusercontent.com/Vvp999/esp32-isaac-sim-teleop/main/media/demo.gif" width="240" align="right" alt="ESP32 joystick driving a robot in Isaac Sim">
</a>

**[esp32-isaac-sim-teleop](https://github.com/Vvp999/esp32-isaac-sim-teleop)**: a hardware-in-the-loop setup where a physical joystick on an ESP32 drives a simulated Jetbot in **Isaac Sim 6.2** over **ROS 2 Jazzy**, while an LCD "robot face" reacts to how you drive.

- ESP32 firmware (C++): calibrated 50 Hz joystick sampling + custom serial protocol
- Python `rclpy` bridge → `/cmd_vel` with fail-safe stop
- Isaac Sim OmniGraph: ROS 2 subscriber → differential controller → wheel joints
- Next: robot-arm teleoperation, RViz odometry, synthetic-data YOLO (sim-to-real)

<br clear="right"/>

### 🤖 Other projects

| Project | What it does | Tech |
|---|---|---|
| **TurtleBot3 indoor service robot** | Autonomous mapping, navigation and obstacle avoidance in Gazebo | ROS 2, Nav2, SLAM, Gazebo |
| **Drone-based precision agriculture** | Detects crop diseases with a CNN and GPS-tags affected areas | Python, TensorFlow, OpenCV |
| **Smart room assistant (YOLO)** | Object detection for a smart-room assistant | Python, YOLO, OpenCV |

### 🛠️ Tech stack

**Robotics:** ROS 2 (Nav2, rclpy), NVIDIA Isaac Sim / Omniverse, Gazebo, TurtleBot3
**AI / Vision:** Python, TensorFlow, OpenCV, YOLO
**Embedded:** ESP32, Arduino / C++, Raspberry Pi, I²C, serial
**Tools:** Git, Linux, MATLAB, C++

### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/YOUR-LINKEDIN-ID) · ✉️ YOUR-EMAIL
