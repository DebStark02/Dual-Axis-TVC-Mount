# Thrust Vector Control (TVC) Mount Mechanism

This project contains the complete CAD files, assembly drawings, motion study, and render screenshots for a dual-axis Thrust Vector Control (TVC) mechanism designed in SOLIDWORKS. The assembly uses two standard micro servos (TowerPro SG90) connected via linkage rods to actuate a 2-DOF gimbal housing an A2212 brushless motor and propeller setup.

> **Note:** This is my **first SOLIDWORKS CAD project**, created primarily to explore kinematic mates, multi-axis linkage articulation, and CAD modeling workflows. The model is **not 3D print ready** in its current state, as parts require additional design for additive manufacturing (DFAM) tweaks such as tolerance clearances, print orientation optimizations, and structural wall reinforcements.

---

## 🛠️ Features & Hardware Components

- **Dual-Axis Thrust Vectoring:** 2-DOF gimbal articulation driven by two orthogonal micro servos.
- **Actuation System:** Pushrod linkages connected to servo horns for pitch and yaw control.
- **Propulsion Mount:** Designed around a standard A2212 Brushless Outrunner Motor and matched propeller.
- **CAD Environment:** Built, mated, and animated using SOLIDWORKS 2021.

---

## 📁 Repository Structure

```text
├── hardware/
│   ├── cad/               # SOLIDWORKS assembly (.SLDASM) and part (.SLDPRT) files
│   ├── drawings/          # Technical manufacturing drawings (tvcdrawing.pdf)
│   └── exports/           # Universal 3D files (.STEP / .IGES)
├── media/
│   ├── motion-study/      # Screen recording / animation of the TVC motion study
│   └── screenshots/       # High-resolution render views (tvc1.jpg to tvc6.jpg)
├── docs/                  # Detailed system documentation (DOCUMENTATION.md)
└── README.md              # Project overview
