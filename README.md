# Sunny Deshpande

**MEng Autonomy & Robotics @ UIUC** (Dec 2026) · [sunnydeshpande.com](https://sunnydeshpande.com)

```yaml
focus:      humanoid robot learning · full-stack autonomy · sim-to-real transfer
languages:  C++ (17/20) · Python
stack:      ROS 2 · Isaac Lab · PyTorch · OpenCV · Nav2
```

---

## What I'm building

**Terrain-aware RL humanoid locomotion - Unitree G1 · Isaac Lab**
PPO policy with a stand → walk → domain-randomization curriculum; a CNN encodes height scans +
proprioception. Domain randomization over mass, friction, PD gains, and pushes; tested across 15
unique terrains with sim-to-real transfer planned.

---

## What I've recently built

**ADAPT - Active Dynamic Avoidance with Pedestrian Trajectory Reasoning (ROS 2 / UIUC GEM e4)**
Diffusion Transformer pedestrian predictor (DDPM-trained, DDIM 10-step) feeds an MPPI motion planner
(K=600 rollouts, 3 s horizon) for proactive avoidance instead of reactive late braking. Text-promptable
goal selection via YOLO-World / LangSAM. Deployed on the UIUC Polaris GEM e4 drive-by-wire platform.

**Conversational VLA navigation - Unitree Go1**
Fine-tuned NaVILA-8B with an added "ask user" action token: when uncertain, the robot opens a
clarification loop instead of committing, with a GPT-4o oracle generating the questions. Trained via
LoRA + DAgger; ~1 Hz offboard inference with 8-bit quantization.

**Contact-gated residual RL - USB-A insertion (UR5e)**
SAC residual policy layered on a classical CV + IK base, gated by force/torque feedback for precise
contact-rich insertion. Trained in MuJoCo with domain randomization; achieves zero-shot sim-to-real
transfer on a real UR5e arm.

---

## Experience

| | |
|---|---|
| **Hyundai Motor Group Innovation Centre SG** | Robotics Fleet Software Engineer Intern - 200+ AMR fleet management |
| **Venti Technologies** | AV Simulation Engineer Intern |
| **A\*STAR** | Robotics & AI Research Intern - end-to-end CNN navigation on Pioneer P3-DX hardware |

---

## Stats

[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SunnyDeshpande&layout=compact&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9&langs_count=5)](https://github.com/SunnyDeshpande)

---

[![Portfolio](https://img.shields.io/badge/Portfolio-sunnydeshpande.com-58a6ff?style=flat-square&logo=googlechrome&logoColor=white)](https://sunnydeshpande.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/sunnydeshpande)
[![Email](https://img.shields.io/badge/sunnydeshpande9900@gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:sunnydeshpande9900@gmail.com)
