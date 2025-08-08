<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&height=200&section=header&text=F1TheBeast&fontSize=90&animation=fadeIn&fontAlignY=38&desc=AILAB%20Summer%20Internship%202025&descAlignY=65&descAlign=62)

### 🏎️ **Building F1Tenth Autonomous Driving Machine** 🏎️

**Racing towards autonomous excellence with cutting-edge algorithms**

</div>

---

<div align="center">

## **Our Team**

</div>

### **Leadership**
- **Jisang Yun** - Team Leader & Perception Lead
  - EKF Odometry & Particle Filter Localization (C++)
  - Competition Winner & Technical Visionary

### **Perception Team**
- **Jisang Yun** - Team Leader
  - EKF Odometry & Particle Filter Localization implementation
- **Subin Park** - SLAM Engineer  
  - EKF-SLAM implementation & mapping systems

### **Planning Team**
- **Yongwoo Kwon** - Global Planning Lead
  - Global trajectory planning & path optimization
- **Jonghun Ahn** - Local Planning Engineer
  - Local path planning & obstacle avoidance

### **Control Team**
- **Yunsang Jeong** - Control Engineer
  - Stanley controller & PID control systems

<div align="center">

## **Project Overview**

</div>

We are developing an autonomous F1Tenth racing car as part of the **AILAB Summer Internship 2025** program. Our team focuses on three core areas:

<div align="center">

| **Perception** | **Planning** | **Control** |
|:---:|:---:|:---:|
| Processing sensor data and environment understanding | Path planning and decision making algorithms | Vehicle control and actuation systems |
| EKF Odometry, Particle Filter, SLAM | Global & Local trajectory planning | Stanley controller, PID systems |

</div>

<div align="center">

## **Repository Architecture**

</div>

### **Main Repository Structure**
```
ultimate_f1thebeast_ws/
├── f1thebeast_ws/              # Main workspace for online execution
├── ekf_slam/                   # Custom EKF-SLAM implementation
├── teleop-tools/               # Keyboard teleoperation tools
└── basecode_follow_the_gap/    # Beginner-friendly base code
```

<div align="center">

### **Technology Stack**

<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white">
<img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white">
<img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black">

</div>

### **Key Repositories**
Our organization maintains **16 active repositories** covering various aspects of autonomous driving:

| **Category** | **Repositories** | **Description** |
|:---:|:---:|:---|
| **Core Systems** | `ekf_slam`, `particle_filter_localization` | EKF-SLAM mapping, Monte Carlo localization (C++) |
| **Interfaces** | `teleop-tools`, `basecode_follow_the_gap` | Manual driving interface, Educational base code |
| **Planning & Control** | Global planning, Local planning, Control systems | Trajectory planning, Stanley & PID implementations |
| **Workspace** | `f1thebeast_ws` | Production workspace, Launch configurations |

<div align="center">

## **Getting Started**

</div>

### **Prerequisites**
- **ROS2** (Humble/Iron recommended)
- **Ubuntu 22.04 LTS**
- **F1Tenth hardware platform**

### **Quick Setup**

<div align="center">

| **Step** | **Command** | **Description** |
|:---:|:---|:---|
| **1** | `git clone --recursive <ultimate_f1thebeast_ws_url>` | Clone ultimate repository |
| **2** | `git submodule update --init --recursive` | Initialize submodules |
| **3** | `cd f1thebeast_ws && colcon build` | Build workspace |
| **4** | `source install/setup.bash` | Source environment |

</div>

### **Usage Guidelines**

<div align="center">

| **User Level** | **Starting Point** | **Focus Areas** |
|:---:|:---:|:---|
| **Beginners** | `basecode_follow_the_gap` | Understanding F1Tenth ROS2 topics and workflow |
| **Developers** | `f1thebeast_ws` | Custom algorithm implementation and testing |
| **Competition** | `f1thebeast_ws` | Fully integrated systems deployment |

</div>

**Development Workflow:**
- Use `teleop-tools` for manual driving and system familiarization
- Test localization with `ekf_slam` and `particle_filter_localization`
- Ensure all submodules are up-to-date before competition runs

---

<div align="center">

**F1TheBeast - Racing towards autonomous excellence**

*AILAB Summer Internship 2025*

</div>
