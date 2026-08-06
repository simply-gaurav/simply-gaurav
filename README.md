Markdown

# Gaurav Kumar Verma
**Robotics Systems Architect & Researcher** | CSIR-CMERI & NIT Patna

> Focus: Real-time autonomous navigation, state estimation, and sensor fusion for GPS-denied environments (AUV/ROV, Swarms, WMR). Full-stack execution from bare-metal C and custom PCB signal conditioning up to ROS 1/2 control stacks and dynamic decision engines.

---

### 🔬 Core Engineering Domains

| Domain | Systems & Frameworks | Key Highlights |
| :--- | :--- | :--- |
| **Underwater Robotics** | ROS 1/2, Decoupled PID, Acoustic Localisation | Target-agnostic homing/docking architectures, range & bearing global frame transformations[cite: 1]. |
| **Custom Hardware & Sensing**[cite: 1] | STM32, ESP32, Bare-Metal C, DMA, Custom PCBs[cite: 1] | Indigenous multi-channel acoustic array, zero-overhead bit-serial parallel acquisition[cite: 1]. |
| **Perception & Navigation**[cite: 1] | 2D/3D LiDAR SLAM, AMCL, ICP, OpenCV[cite: 1] | Custom kinematic noise model tuning, dynamic human-tracking collision avoidance[cite: 1]. |
| **Multi-Agent Systems**[cite: 1] | Consensus Algorithms, LLM Intent Wrappers[cite: 1] | Decoupled swarm logic transferred across GPS-denied subsea and aerial domains[cite: 1]. |

---

### 🛠️ Subsystem Architecture & R&D

#### 1. Target-Agnostic Subsea Homing & Autonomous Docking
* **System Pipeline:** Acoustic Sensors $\rightarrow$ Global Frame Transformation Node $\rightarrow$ Decoupled Yaw/Surge/Depth Control Stack $\rightarrow$ Actuator Array[cite: 1]
* Architected alocator-centric navigation framework in ROS that converts raw acoustic range and bearing into dynamic reference offsets[cite: 1].
* Implemented multi-threaded PID loops gated by heading lock to eliminate lateral crabbing during docking maneuvers[cite: 1].
* Integrated non-blocking depth control coupled with a hardware-level altimeter safety override ($<2\text{m}$ seabed threshold)[cite: 1].

#### 2. Indigenous Multi-Channel Acoustic Hardware (Ph.D. Research)
* **System Pipeline:** Transducer Suite $\rightarrow$ Custom Signal Conditioning PCB $\rightarrow$ STM32 (DMA Acquisition) $\rightarrow$ Ubuntu / ROS Node[cite: 1]
* Designed custom signal-conditioning hardware to replace high-cost commercial DVL/USBL payloads for scalable swarms[cite: 1].
* Authored bare-metal C firmware utilizing Direct Memory Access (DMA) for deterministic, parallel bit-serial signal sampling[cite: 1].
* Direct ROS integration streaming custom sonar data as native ROS topics[cite: 1].

---

### 📑 Key Research & Milestones

* **ISRO ASCEND 2026:** Shortlisted (Round 1) — Multi-agent aerial swarm logic for planetary exploration without pseudolite or GNSS aids[cite: 1].
* **Smart India Hackathon 2024 Winner:** Satellite-independent climate and crop monitoring drone system[cite: 1].
* **Publications:** *International Journal of Control, Automation, and Systems* (2025), *IEEE Conference* (2024), *ACM/IEEE Conference* (2023)[cite: 1].
* **Intellectual Property:** 1 Patent Under Review (Underwater Sensing Optimization), 1 Copyright Under Review (System Architecture)[cite: 1].

---

### ⚙️ Technical Environment

```text
Languages     : C++, C (Bare-Metal), Python, Bash
Frameworks    : ROS 1 (Melodic/Noetic), ROS 2, OpenCV, Node.js
Micro/HW      : STM32, ESP32, Custom Signal PCBs, SolidWorks, 3D Prototyping
Sensors       : DVL, USBL, Acoustic Sonar, AHRS, Altimeter, 2D/3D LiDAR, Depth Cameras

📬 Contact & Credentials

    Institution: CSIR-CMERI Durgapur / NIT Patna[cite: 1]

    Email: gauravkhunti@gmail.com

    [cite: 1]

    LinkedIn: gaurav-kumar-verma-94a580ab

    [cite: 1]
