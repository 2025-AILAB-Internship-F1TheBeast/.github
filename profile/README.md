# F1TheBeast 🏎️

**AILAB Summer Internship 2025**

Building F1Tenth Autonomous Driving Machine

## Team Members

### Leadership
- **Jisang Yun** - Team Leader & Perception Lead
  - EKF Odometry & Particle Filter Localization (C++)

### Perception Team
- **Jisang Yun** - Team Leader
  - EKF Odometry & Particle Filter Localization implementation
- **Subin Park** - SLAM Engineer
  - EKF-SLAM implementation & mapping systems

### Planning Team
- **Yongwoo Kwon** - Global Planning Lead
  - Global trajectory planning & path optimization
- **Jonghun Ahn** - Local Planning Engineer
  - Local path planning & obstacle avoidance

### Control Team
- **Yunsang Jeong** - Control Engineer
  - Stanley controller & PID control systems

## Project Overview

We are developing an autonomous F1Tenth racing car as part of the AILAB Summer Internship 2025 program. Our team focuses on three core areas:

- **Perception**: Processing sensor data and environment understanding
- **Planning**: Path planning and decision making algorithms
- **Control**: Vehicle control and actuation systems

## Repository Architecture

### Main Repository Structure
- **`ultimate_f1thebeast_ws`** - Ultimate repository containing all submodules
  - **`f1thebeast_ws`** - Main workspace for online execution
  - **`ekf_slam`** - Custom EKF-SLAM implementation
  - **`teleop-tools`** - Keyboard teleoperation tools for manual driving
  - **`basecode_follow_the_gap`** - Beginner-friendly repository for understanding F1Tenth ROS2 topics and workflow

### Key Repositories
Our organization maintains 16 active repositories covering various aspects of autonomous driving:

**Core Systems:**
- `ekf_slam` - EKF-SLAM mapping and localization
- `particle_filter_localization` - Monte Carlo localization (C++)
- `teleop-tools` - Manual driving interface
- `basecode_follow_the_gap` - Educational base code

**Planning & Control:**
- Global trajectory planning algorithms
- Local path planning systems
- Stanley & PID control implementations
- Lattice planning algorithms

**Workspace Setup:**
- `f1thebeast_ws` - Production workspace
- Base workspace configurations
- Launch files and parameter configurations

## Getting Started

### Prerequisites
- ROS2 (Humble/Iron recommended)
- Ubuntu 22.04 LTS
- F1Tenth hardware platform

### Quick Setup
1. Clone the ultimate repository:
   ```bash
   git clone --recursive <ultimate_f1thebeast_ws_url>
   cd ultimate_f1thebeast_ws
   ```

2. Initialize submodules:
   ```bash
   git submodule update --init --recursive
   ```

3. Build the workspace:
   ```bash
   cd f1thebeast_ws
   colcon build
   source install/setup.bash
   ```

### Usage Guidelines

**For Beginners:**
- Start with `basecode_follow_the_gap` to understand F1Tenth ROS2 topic flow
- Practice with `teleop-tools` for manual driving and system familiarization

**For Development:**
- Use `f1thebeast_ws` for main system execution
- Implement custom algorithms in respective specialized repositories
- Test localization with `ekf_slam` and `particle_filter_localization`

**For Competition:**
- Deploy from `f1thebeast_ws` with fully integrated systems
- Ensure all submodules are up-to-date before competition runs

---

*F1TheBeast - Racing towards autonomous excellence* 🚗💨