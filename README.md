# CS7675: Master's Research

## Research Apprentice @ PARCS Lab, under Prof. Zhi Tan

## Overview
Working on **Stretch3 AI**, implementing state-of-the-art RL methods such as **Diffusion Policy, VQ-BeT, Pi_0**, and **Deep Perception** (closed-loop and open-loop). The focus is on **robot teleoperation, policy learning, and perception models**.

---

## Weekly Progress

### 🗓️ **Jan 06, 2025** – Getting Started with Stretch3
- Familiarized with **Stretch3’s ROS2 interface** (testing/debugging tools).
- Implemented:
  - **Keyboard teleoperation**
  - **Perception (point-cloud from 2D images)**
  - **Depth-map generation (gripper camera & sensors)**


### 🗓️ **Jan 13, 2025** – Installing & Testing `stretch_ai`
- Debugged **StretchAI** installation (NVIDIA drivers, CUDA, dependencies).
- Set up **StretchAI on GPU and robot**.
- Verified **deep perception models** (face/object detection).
- Started working on **`ai_pickup` (language-directed pick & place feature).**


### 🗓️ **Jan 20, 2025** – Understanding `stretch_ai`
- Implemented **custom pickup functions** for **identifying and navigating to a Red Button**.
- Explored how **StretchAI agent** generates robot instructions from natural language.
- Began debugging **button press navigation errors**.


### 🗓️ **Jan 27, 2025** – Pressing the Red Button
- Addressed **object detection issues** with **Detic + CLIP**.
- Investigated **grasping methods**:
  - **AnyGrasp (IP protected)**
  - **Opensource alternatives: GraspNet, Graspness**


### 🗓️ **Feb 03, 2025** – Open-Loop vs. Closed-Loop Policies
- Developed **two methods** for pressing the Red Button:
  - **Open-loop approach:** Fixed execution steps.
  - **Closed-loop approach:** Uses **Detic + CLIP** for adaptive behavior.
- Started working on **Dexterous Teleop Kit** for **training RL policies**.


### 🗓️ **Feb 10, 2025** – Dex Teleop & Diffusion Policy
- Built **Dexterous Teleop Kit** for RL policy training.


### 🗓️ **Feb 17, 2025** – Understanding Diffusion Policy
- Studied the **Diffusion Policy** paper.
- Finished **building teleop kit**.
- Started analyzing **Diffusion Policy** code:
  - Available for **LeRobot**, but not for **Stretch3**.
  - Began **adapting LeRobot’s implementation** for Stretch3.


### 🗓️ **Feb 24, 2025** – Noising-Denoising Process in Diffusion Policy
- Set up **Dex-teleop** on PC & robot.
- Migrated from **Docker** to **Mamba virtual environment**.
- Understood **Diffusion Policy’s noising-denoising process**.
- Began **robot teleoperation data collection**.


### 🗓️ **Mar 03, 2025** – VQ-BeT & Camera Calibration
- **Calibrated Logitech-Webcam-C930e** for **Dex Teleop**.
- Finished studying **Diffusion Policy** (presented findings to Prof. Zhi).
- Started implementing **Diffusion Policy for Stretch3**.
- **Collected human demonstration data** for "Press Button" task.


### 🗓️ **Mar 09, 2025** – Training Stretch3 on Diffusion Policy
- **Collecting 30+ teleop demonstrations** for policy training.
- Implementing **Diffusion Policy adaptation** for Stretch3 based on **LeRobot’s implementation**.

---

## 🔬 Research Focus Areas
- **Diffusion Policy:** Implementing & training **visuomotor policies**.
- **VQ-BeT:** Exploring state-of-the-art RL methods.
- **Dexterous Teleoperation:** Data collection & policy training.
- **Deep Perception:** Improving robot awareness in both **open-loop and closed-loop systems**.

---

This research aims to advance **robot manipulation and learning** by integrating cutting-edge **reinforcement learning techniques** with **natural language-driven control**.
