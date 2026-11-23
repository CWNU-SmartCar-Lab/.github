<div align="center">

# 🏎️ CWNU-SmartCar-Lab

**China West Normal University Smart Car Lab · Organization Hub**

<p align="center">
  <a href="https://github.com/CWNU-SmartCar-Lab"><img src="https://img.shields.io/badge/GitHub-CWNU--SmartCar--Lab-181717?style=for-the-badge&logo=github" alt="GitHub Org" /></a>
  <a href="https://gitee.com/CWNU-SmartCar-Lab"><img src="https://img.shields.io/badge/Gitee-Mirror-C71D23?style=for-the-badge&logo=gitee&logoColor=white" alt="Gitee Mirror" /></a>
  <img src="https://img.shields.io/badge/Since-2022-0969DA?style=for-the-badge" alt="Since 2022" />
  <img src="https://img.shields.io/badge/Status-Active-2DA44E?style=for-the-badge" alt="Status Active" />
</p>

**🌐 [简体中文](./README.md) | English**

*Exploring Smart Technology, Racing in the Open-Source World*

<p align="center">
  <img src="../assets/cover.jpg" alt="CWNU-SmartCar-Lab Smart Car Showcase" width="420" />
</p>

[🔬 About the Lab](#about) &nbsp;·&nbsp; [⏱️ Recruitment](#recruitment) &nbsp;·&nbsp; [🗺️ Repositories](#repositories) &nbsp;·&nbsp; [🤝 Contributing](#contributing) &nbsp;·&nbsp; [💌 Message](#message)

</div>

---

## 🔬 About the Lab<a id="about"></a>

Welcome to **CWNU-SmartCar-Lab** (Smart Car Lab, China West Normal University)!

Founded in **2022**, we are a collegiate engineering and robotics competition team dedicated to **intelligent vehicles, embedded systems, and autonomous robotics**. Over the years, our team has earned multiple national and provincial awards in events including the National University Students Intelligent Car Race (including the Outdoor Track National Finals) and the Sichuan University Students Robot Competition.

Here, code meets hardware and theory is put to the test on the real racetrack. Across four core domains, we strive to bridge disciplinary boundaries and cultivate full-stack engineers skilled in both software and hardware:

- **🤖 Autonomous Driving & Embodied AI:** Exploring decision-making, reinforcement learning, and autonomous driving algorithms on mobile robotic platforms.
- **👁️ Computer Vision & SLAM:** Working on image processing, OpenCV perception pipelines, and ROS / ROS 2 LiDAR SLAM navigation.
- **⚙️ Embedded Systems & Control:** Building MCU driver architectures, multi-sensor interfaces, closed-loop motor control, and Linear Active Disturbance Rejection Control (LADRC).
- **🔧 Hardware & Mechanical Design:** Covering schematic design, component selection, PCB layout and routing, board soldering/debugging, and 3D-printed structures.

### 📸 Lab & Competition Highlights

<table>
  <tr>
    <td align="center" width="50%">
      <img src="../assets/IMG_20240724_114912.jpg" alt="19th National University Students Intelligent Car Race Western Division" width="100%" /><br />
      <sub><b>19th Intelligent Car Race · Western Division</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="../assets/IMG_20241208_085226.jpg" alt="19th National University Students Intelligent Car Race Outdoor Track National Finals" width="100%" /><br />
      <sub><b>19th Intelligent Car Race · Outdoor Track National Finals</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="50%">
      <img src="../assets/IMG_20241019_181501.jpg" alt="9th Sichuan University Students Robot Competition 2024" width="100%" /><br />
      <sub><b>9th Sichuan University Students Robot Competition (2024)</b></sub>
    </td>
    <td align="center" width="50%">
      <img src="../assets/mmexport1777296392742.jpg" alt="Late-night pre-race debugging session" width="100%" /><br />
      <sub><b>Late-Night Pre-Race Prep · Track Testing &amp; Debugging</b></sub>
    </td>
  </tr>
</table>

---

## ⏱️ Recruitment & Assessment<a id="recruitment"></a>

Want to join the team and build real robots together? Here are the tracks and milestones for our **Rising Star Program**:

### 🎯 Tracks & Prerequisites

| Track | Core Skills & Expectations |
| :--- | :--- |
| **Embedded&nbsp;Systems** | Master common MCU peripheral drivers, UART and other communication protocols, and build a solid foundation in control theory. |
| **Linux&nbsp;&amp;&nbsp;Vision** | Work comfortably in Linux development environments, understand image processing fundamentals, use OpenCV proficiently, and gain familiarity with ROS / ROS 2. |
| **Hardware&nbsp;&amp;&nbsp;Mechanics** | Master schematic design, IC/component selection, PCB layout and routing, circuit soldering and troubleshooting, and basic 3D printing skills. |

### 📅 Assessment Timeline

| Stage | Annual Schedule | Goals & Evaluation Focus |
| :---: | :---: | :--- |
| **Phase 1**<br /><sub>Initial Screening</sub> | Mid-September | **Foundations:** Assess fundamental concepts and core toolchain proficiency in your chosen track. |
| **Final**<br /><sub>Hands-On Exam</sub> | Late October | **Practical Project:** Evaluate hands-on implementation, debugging, and engineering execution through a complete mini-project. |

> **💡 Tip:** Mindset matters more than where you start! Beyond your current technical background, we value a strong drive to keep learning, the grit to track down tough bugs, and reliable teamwork.

---

## 🗺️ Repository Guide<a id="repositories"></a>

> **🚀 Gitee Mirror (China):** [https://gitee.com/CWNU-SmartCar-Lab](https://gitee.com/CWNU-SmartCar-Lab)
>
> We manage and preserve our core technical assets across both **GitHub** and **Gitee** (mirror for faster access in mainland China), with GitHub serving as our primary hub.

### 🟢 Open Source Projects

*Embracing open source and sharing the tools we build — Stars and Forks are always welcome!*

| Repository | Tags | Description |
| :--- | :---: | :--- |
| 🔗&nbsp;[**Lidar_SLAM_Car-RDKX5-**](https://github.com/CWNU-SmartCar-Lab/Lidar_SLAM_Car-RDKX5-) | `ROS 2` `SLAM` | **LiDAR SLAM Host Software:** Onboard control system for the RDK X5 platform integrating the YDLidar SDK and ROS 2 LiDAR driver for perception and SLAM deployment. |
| 🔗&nbsp;[**Lidar_SLAM_Car-STM32F411-**](https://github.com/CWNU-SmartCar-Lab/Lidar_SLAM_Car-STM32F411-) | `STM32` `PCB` | **LiDAR Car MCU Firmware & Hardware:** STM32F411 chassis firmware and motherboard files featuring closed-loop speed control, LADRC, VOFA+ tuning interface, peripheral drivers, and EasyEDA schematics/PCB. |
| 🔗&nbsp;[**vofa_uart**](https://github.com/CWNU-SmartCar-Lab/vofa_uart) | `VOFA+` `UART` | **Embedded Serial Tuning Library:** Lightweight UART communication framework for VOFA+, supporting JustFloat / Firewater / Rawdata protocols and customizable command-frame parsing with weak-symbol portability. |

### 🔒 Internal Archives

*Core lab technical archives and internal training materials, accessible to organization members only.*

| Repository | Tags | Description |
| :--- | :---: | :--- |
| 🔒&nbsp;[**LADRC_Control**](https://github.com/CWNU-SmartCar-Lab/LADRC_Control) | `Control` `C` | **LADRC Control Library:** C implementation of Tracking Differentiator (TD), Extended State Observer (ESO), and Linear Feedback (LF), paired with practical tuning guides. |
| 🔒&nbsp;[**Smart-Car-Private**](https://github.com/CWNU-SmartCar-Lab/Smart-Car-Private) | `Archive` | **Competition Codebase Archive:** Historical smart car competition codebases, hardware/software designs, and post-mortems organized by year and category. |
| 🔒&nbsp;[**Burning-Formula**](https://github.com/CWNU-SmartCar-Lab/Burning-Formula) | `Archive` `Docs` | **Lab Heritage & Competition Playbook:** Accumulated team management practices, competition preparation notes, and hard-won lessons from past seasons. |
| 🔒&nbsp;[**machine_learning_tutorial**](https://github.com/CWNU-SmartCar-Lab/machine_learning_tutorial) | `PyTorch` `RL` | **Hands-On Machine Learning Course:** A 10-lesson interactive PyTorch tutorial for lab members, progressing from CartPole prediction and control to CNNs, Attention, and PPO reinforcement learning. |

---

## 🤝 Acknowledgements & Contributing<a id="contributing"></a>

The growth of a hardcore engineering lab depends on every member's dedication and the legacy passed down by our seniors:

- **To Our Seniors:** Thank you to every teammate who stayed up late reading waveforms, tuning PID loops, soldering PCBs, and standing by the track.
- **To Open Source:** Thank you to the open-source community for the frameworks and toolchains that let us stand on the shoulders of giants.
- **Internal Workflow:** Organization members should follow the `Feature Branch` workflow, open **Pull Requests** for updates, and complete **Code Review** before merging.
- **Community Contributions:** External developers are welcome to open **Issues** with feedback or submit **Pull Requests** to help improve our public repositories.

---

## 💌 Message to You<a id="message"></a>

> *"Talk is cheap. Show me the code... and let the car run!"*

May you not only write clean, reliable code here, but also meet teammates who share your passion. On the smart car track, never fear bugs or setbacks — stay curious, iterate boldly, and let your code race at full speed in the real world!

---

<div align="center">
  <b>Made with ⚡️ and 💻 by CWNU-SmartCar-Lab</b>
</div>
