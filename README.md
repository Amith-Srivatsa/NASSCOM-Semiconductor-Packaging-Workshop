# NASSCOM-Semiconductor-Packaging-Workshop
# Packaging Evolution: From Basics to 3D Integration
# Semiconductor Packaging Design & Testing – Ansys AEDT Project

This repository presents a complete hands-on journey through semiconductor package development using **Ansys Electronics Desktop (AEDT)**, including **design, modeling, testing, and reliability analysis**. It follows a 5-module structure covering real-world steps in packaging ICs using wire bonding.

---

#### Package Stack Details:

| Component             | Material          | Dimensions            | Thickness/Height |
|-----------------------|-------------------|------------------------|------------------|
| Die                   | Silicon           | 3 mm × 3 mm           | 0.2 mm           |
| Substrate             | FR4               | 5 mm × 5 mm           | 0.5 mm           |
| Die Attach            | Modified Epoxy    | 3 mm × 3 mm           | 0.1 mm           |
| Die Bond Pads         | Copper            | 0.2 mm × 0.2 mm       | 0.005 mm         |
| Substrate Bond Pads   | Copper            | 0.2 mm × 0.2 mm       | 0.01 mm          |
| Bond Wires            | Gold              | JEDEC 4-point         | —                |
| Mold Compound         | Epoxy             | 5 mm × 5 mm           | 1.2 mm           |

#### 🛠️ AEDT Modeling Steps:
1. **Set up units** in mm in Q3D layout
2. **Draw die** and assign material as Silicon
3. **Create substrate**, offset under die, assign FR4
4. **Add die attach** layer (modified epoxy) between die and substrate
5. **Place bond pads** on die and substrate using copper
6. **Connect pads using bond wires**, JEDEC 4-point, gold
7. **Encapsulate with mold compound** to protect wires and die
8. **Color code parts** for easy visual identification

## Tools Used
- **Ansys Electronics Desktop (AEDT)**
- **Q3D Extractor**
- Material Library within AEDT

---

## Applications
- IC Packaging Labs
- Electronic Component Design
- Signal Integrity Prep Models
- Capacitance/Inductance Extraction
- Thermal Interface Material Design

