# Sunny Deshpande

**MEng Autonomy & Robotics @ UIUC** (Dec 2026) · [sunnydeshpande.com](https://sunnydeshpande.com)

```yaml
focus:      humanoid robot learning · full-stack autonomy · sim-to-real transfer
languages:  C++ (17/20) · Python
stack:      ROS 2 · Isaac Lab · PyTorch · OpenCV · Nav2
```

---

## What I'm building

**Unitree G1 locomotion — Isaac Lab**
PPO locomotion policy trained through a 7-phase curriculum (standing → omnidirectional walking).
Achieved stable bipedal gait at 1.5 m/s. Actively extending to rough terrain with scandot observations.

**H-MARL — dual humanoid coordination**
Hierarchical MARL: high-level PPO navigator [64,64] + decentralized low-level locomotion agents [256,256].
Two G1 robots autonomously locate, approach, and stop at a fixed distance from each other in Isaac Lab.

**VLA fine-tuning (HumanVLA)**
Replaced visual encoder with frozen CLIP backbone. Diagnosed catastrophic forgetting as primary failure mode.
Investigating frozen-backbone vs. selective-unfreeze tradeoffs for robot manipulation tasks.

**AutoShield — real-vehicle autonomy stack (ROS 2 / UIUC GEM)**
LiDAR (Ouster OS1-128) + RGB-D (OAK-D LR / YOLOv11) pedestrian pipeline with DBSCAN clustering,
EMA centroid tracking, weighted sensor fusion, TTC estimation, and Stanley/PID control with hard-brake override.
Deployed on a real drive-by-wire vehicle.

---

## Experience

| | |
|---|---|
| **Hyundai Motor Group Innovation Centre SG** | Robotics Fleet Software Engineer — 200+ AMR fleet management |
| **Venti Technologies** | AV Simulation Engineer |
| **A\*STAR** | Research — end-to-end CNN navigation on Pioneer P3-DX hardware |

---

## Stats

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SunnyDeshpande&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=5)](https://github.com/SunnyDeshpande)

---

[![Portfolio](https://img.shields.io/badge/Portfolio-sunnydeshpande.com-58a6ff?style=flat-square&logo=googlechrome&logoColor=white)](https://sunnydeshpande.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sunnydeshpande)
[![Email](https://img.shields.io/badge/sunnynd2@illinois.edu-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:sunnynd2@illinois.edu)
