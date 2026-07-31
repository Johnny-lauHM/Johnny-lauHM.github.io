---
layout: homepage
---

## About Me

I am an M.Sc. student in Robotics at the [National University of Singapore](https://nus.edu.sg/), where I work on **embodied AI** and **robot learning**. I received my B.Sc. in Opto-Electronics Information Science and Engineering from [Sun Yat-sen University (SYSU)](https://www.sysu.edu.cn/).

My research focuses on teaching robots to act in the physical world — vision-language-action (VLA) models, imitation learning, dexterous manipulation, and high-DoF teleoperation for contact-rich tasks. I enjoy building full-stack systems that span from low-level motor control and IK solvers to end-to-end learned policies.

## Research Interests

- **Embodied AI & Robot Learning:** VLA models, imitation learning (ACT, SmolVLA), few-shot policy learning
- **Dexterous Manipulation:** contact-rich tasks, tactile-visual fusion, multi-fingered hands
- **Teleoperation & Data Collection:** bimanual glove/tracker retargeting, VR teleoperation, real-time IK

## 🔥 News

- **[Jul. 2026]** Started my research on high-DoF teleoperation for contact-rich dexterous manipulation.
- **[Jan. 2026]** Began a Software Engineering internship at Ronovo Surgical, building VR teleoperation for surgical robots.
- **[Nov. 2025]** Started work on VLA fine-tuning and tactile-visual fusion with the SO-ARM101 platform.

## 🚀 Selected Projects

<div class="publications">
<ol class="bibliography">

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
    <div class="title">High-DoF Teleoperation for Contact-Rich Dexterous Manipulation</div>
    <div class="author">Haoming Liu</div>
    <div class="periodical"><em>National University of Singapore, 2026 – Present</em></div>
    <div>Bimanual teleoperation system with two decoupled paths — MANUS gloves → 20-DoF Wuji dexterous hands, and VIVE trackers → Franka via cuRobo IK — for imitation-learning data collection. Built an analytical-gradient IK retargeting pipeline mapping 21-keypoint glove input to 20-DoF joint angles at ~50 ms latency over ROS 2.</div>
  </div>
</div>
</li>
<br>

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
    <div class="title">Robotic Arm Control & VLA Fine-Tuning (SO-ARM101)</div>
    <div class="author">Haoming Liu</div>
    <div class="periodical"><em>2025 – 2026</em></div>
    <div>End-to-end imitation-learning system on ROS 2 + MoveIt 2 with RRT* planning. Trained ACT/SmolVLA policies from 50+ expert demonstrations; fused FlexiTac-V2 tactile pressure maps with visual observations, improving real-robot grasping success by 30% over a vision-only baseline (60% pick-and-place success).</div>
  </div>
</div>
</li>
<br>

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
    <div class="title">Omnidirectional Intelligent Vehicle (Mecanum Wheels)</div>
    <div class="author">Haoming Liu</div>
    <div class="periodical"><em>2024</em></div>
    <div>Distributed upper/lower control architecture: Raspberry Pi running ROS 2 for LiDAR SLAM (slam_toolbox) and Navigation2 global/local planning; STM32F103 for encoder PID closed-loop motor control with IMU heading correction.</div>
  </div>
</div>
</li>
<br>

<li>
<div class="pub-row">
  <div class="col-sm-9" style="position: relative;padding-right: 15px;padding-left: 20px;">
    <div class="title">Multimodal Efficient Power Conversion for Electric Vehicles</div>
    <div class="author">Haoming Liu</div>
    <div class="periodical"><em>2023 – 2025</em></div>
    <div>High-efficiency Buck-Boost + charge-pump DC-DC converter supporting four modes (boost/buck charging, V2G grid feedback). Achieved 100V→250V boost and 400V→200V buck at up to 500W. <strong>2 invention patents filed (published)</strong>; recognized as a university-level Outstanding Innovation & Entrepreneurship Project.</div>
  </div>
</div>
</li>
<br>

</ol>
</div>

## 💼 Experience

- **Ronovo Surgical** — Software Engineering Intern, Shanghai *(Jan. 2026 – May 2026)*<br>
  Built a Pico-headset VR teleoperation system for surgical robots (XR tracking → DDS comms → stereo video feedback, 50–100 ms latency). Developed an RCM-constrained IK solver in MuJoCo with null-space singularity avoidance and gravity compensation.

## 🎓 Education

- **National University of Singapore** — M.Sc. in Robotics *(Present)*
- **Sun Yat-sen University** — B.Sc. in Opto-Electronics Information Science and Engineering *(2022 – 2026)*

## 🛠 Skills

**Programming & Tools:** Python, MATLAB, PSIM, PyTorch, Isaac Lab, MuJoCo<br>
**Languages:** Mandarin (native), Cantonese (native), English (fluent, IELTS 7.5)
