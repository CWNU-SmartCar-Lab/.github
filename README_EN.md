<div align="center">

# 🏎️ CWNU-SmartCar-Lab Organization Navigation

[![GitHub Org](https://img.shields.io/badge/GitHub-CWNU_SmartCar_Lab-181717?style=for-the-badge&logo=github)](#)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Active-success.svg?style=for-the-badge)](#)

**🌐 [English](./README_EN.md) | [简体中文](./README.md)**

*Exploring Smart Tech, Racing in the Open Source World*

<img src="https://via.placeholder.com/800x250/1e1e2e/89b4fa?text=CWNU+SmartCar+Lab+Banner" alt="Lab Banner" width="100%">

</div>

---

## 📑 Table of Contents
- [🔬 About the Lab](#-about-the-lab)
- [⏱️ Assessment Schedule & Criteria](#-assessment-schedule--criteria)
- [🗺️ Repository Guide](#-repository-guide)
- [🤝 Acknowledgements & Contributing](#-acknowledgements--contributing)
- [💌 Final Words](#-final-words)

---

## 🔬 About the Lab

Welcome to the **CWNU-SmartCar-Lab**!
We are a team of geeks dedicated to autonomous driving chassis, SLAM mapping algorithms, low-level motor control, and embedded system development. Here, code and hardware collide to spark passion, and theory meets practice on real-world racetracks. We are committed to breaking down disciplinary barriers and cultivating engineers with full-stack software and hardware development capabilities.

<div align="center">
  <img src="https://via.placeholder.com/600x300/1e1e2e/f38ba8?text=Working+in+the+Lab" alt="Lab Work" width="80%">
</div>

---

## ⏱️ Assessment Schedule & Criteria

Want to join us and fight alongside the masters? Here are the assessment milestones and cheat codes for our Lab Rising Star Program:

| Phase | Schedule | Objectives & Passing Criteria |
| :---: | :---: | :--- |
| **Preliminary (Phase 1)** | Mid-September | **Basic Skills**: Master fundamental C/C++ syntax, understand basic data structures, and have a preliminary understanding and immense passion for embedded systems or Linux. |
| **Semi-final (Phase 2)** | Mid-October | **Practical Validation**: Independently configure basic MCU peripherals, understand motor drive principles, or successfully run basic ROS nodes on a host computer. |
| **Final Exam** | Late November | **Project Execution**: Independently complete closed-loop control (e.g., PID speed loop tuning), or successfully deploy and run a specified SLAM algorithm. Code must adhere to excellent coding standards. |

> **💡 Pro Tip:** Attitude determines altitude! More than your current technical stack, we value your continuous learning ability, your tenacity to fight bugs to the bitter end, and your team spirit.

---

## 🗺️ Repository Guide

We use GitHub to manage and precipitate our core technical assets. Below is the navigation for our core repositories, divided into open-source and internal archives:

### 🟢 Open Source Projects
*Embrace open source, share our wheels with the world. Stars and Forks are highly welcome!*

| Repository | Domain Tags | Description | Portal |
| :--- | :---: | :--- | :---: |
| **Lidar_SLAM_Car-RDKX5-** | `ROS` `SLAM` | **LiDAR SLAM Host Software**: Implementation of LiDAR SLAM algorithms and host control system deployment based on the RDK X5 platform. | [🔗 Visit Repo](https://github.com/CWNU-SmartCar-Lab/Lidar_SLAM_Car-RDKX5-) |
| **Lidar_SLAM_Car-STM32F411-** | `Embedded` | **LiDAR SLAM Lower-level & Hardware**: Includes chassis kinematics solver, hardware driver code, and core hardware schematics & PCB design files. | [🔗 Visit Repo](https://github.com/CWNU-SmartCar-Lab/Lidar_SLAM_Car-STM32F411-) |
| **vofa_uart** | `vofa usart` | **Serial Tuning Code and Methods**: A toolkit primarily used for serial parameter tuning, utilizing the Justfloat protocol of the VOFA+ software and command frame parsing, with customizable response frames. | [🔗 Visit Repo](https://github.com/CWNU-SmartCar-Lab/vofa_uart) |

### 🔴 Internal Projects (Closed Source)
*The lab's core technical barriers and legacy, accessible only to internal organization members.*

| Repository | Domain Tags | Description | Portal |
| :--- | :---: | :--- | :---: |
| **LADRC_Control** | `Control` | **LADRC Tuning Guide**: Practical deployment, code encapsulation, and detailed tuning guide for Linear Active Disturbance Rejection Control (LADRC). | [🔒 Internal Access](https://github.com/CWNU-SmartCar-Lab/LADRC_Control) |
| **Smart-Car-Private** | `Archive` | **Past Core Codebase**: A collection of excellent code, schematic designs, and post-mortem review documents from past smart car competitions. | [🔒 Internal Access](https://github.com/CWNU-SmartCar-Lab/Smart-Car-Private) |

---

## 🤝 Acknowledgements & Contributing

The growth of a hardcore lab is inseparable from the hard work of every member and the technical accumulation of our predecessors:
* Thanks to every lab senior who stayed up late watching waveforms, tuning PIDs, and soldering boards.
* Thanks to the open-source community for providing so many excellent low-level frameworks, allowing us to stand on the shoulders of giants.
* **Contributing Guide**: Organization members wishing to update code should follow the `Feature Branch` workflow, actively submit Pull Requests, and complete Code Reviews before merging.

---

### 📈 Open Source Impact (Star History)

*Witness the growth trajectory of our open-source projects. Thanks to every developer who has given us a Star!*

<div align="center">
  <a href="https://star-history.com/#CWNU-SmartCar-Lab/Lidar_SLAM_Car-RDKX5-&CWNU-SmartCar-Lab/Lidar_SLAM_Car-STM32F411-&CWNU-SmartCar-Lab/vofa_uart&Date">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/svg?repos=CWNU-SmartCar-Lab/Lidar_SLAM_Car-RDKX5-,CWNU-SmartCar-Lab/Lidar_SLAM_Car-STM32F411-,CWNU-SmartCar-Lab/vofa_uart&type=Date&theme=dark" />
      <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/svg?repos=CWNU-SmartCar-Lab/Lidar_SLAM_Car-RDKX5-,CWNU-SmartCar-Lab/Lidar_SLAM_Car-STM32F411-,CWNU-SmartCar-Lab/vofa_uart&type=Date" />
      <img alt="Star History Chart" src="https://api.star-history.com/svg?repos=CWNU-SmartCar-Lab/Lidar_SLAM_Car-RDKX5-,CWNU-SmartCar-Lab/Lidar_SLAM_Car-STM32F411-,CWNU-SmartCar-Lab/vofa_uart&type=Date" width="80%" />
    </picture>
  </a>
</div>

## 💌 Final Words

> *"Talk is cheap. Show me the code... and let the car run!"*

May you not only write elegant and efficient code here but also meet a group of like-minded comrades. On the smart car racetrack, don't be afraid of errors; bravely explore and trial-and-error, and let your code race at full speed in the real world!

---
<div align="center">
  <b>Made with ⚡️ and 💻 by CWNU-SmartCar-Lab</b>
</div>