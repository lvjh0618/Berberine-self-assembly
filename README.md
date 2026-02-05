# Molecular Dynamics Study: Self-Assembly of Berberine (BBR)

[![Status](https://img.shields.io/badge/Status-In--Progress-orange.svg)](https://github.com/lvjh0618) 
[![GROMACS](https://img.shields.io/badge/Tools-GROMACS%20%7C%20Python%20%7C%20R-blue.svg)](https://www.gromacs.org/)

## 📝 Overview
This repository hosts the computational workflow for my research on the **supramolecular self-assembly of Berberine**, a prominent herbal small molecule. By employing **Molecular Dynamics (MD) simulations**, I investigate the driving forces behind the formation of antibacterial nano-aggregates.

This project is a core component of my MSc research at **Nanjing Agricultural University**, aiming to bridge traditional herbal pharmacology with modern computational biophysics for aquaculture disease control.

---

## 🔬 Research Objectives
* **Mechanism Elucidation:** Simulate the aggregation kinetics of Berberine in aqueous environments.
* **Structural Analysis:** Identify key interaction motifs, such as $\pi-\pi$ stacking and hydrophobic interactions, that stabilize self-assembled complexes.
* **Bioactivity Correlation:** Provide theoretical insights into how molecular clustering modulates antimicrobial efficacy.

---

## 🛠 Methodology & Tools
* **Simulation Engine:** `GROMACS` (Force fields: CHARMM36 / GAFF).
* **Trajectory Analysis:** Custom `Python` scripts using `MDAnalysis`, `MDTraj`, and `NumPy`.
* **Data Visualization:** `Matplotlib` & `Seaborn` for plotting; `PyMOL` for 3D molecular rendering.
* **Statistical Computing:** `R` for advanced data correlation.

---

## 📂 Repository Structure
```text
.
├── simulation_inputs/      # Reproducible GROMACS configurations
│   ├── em.mdp              # Energy minimization parameters
│   ├── nvt.mdp             # NVT equilibration settings
│   └── npt.mdp             # NPT production run settings
├── notebooks/              # Data analysis & Visualization
│   └── analysis.ipynb      # End-to-end trajectory analysis workflow
├── results/                # Computational outputs
│   └── figures/            # High-resolution plots (RMSD, Rg, SASA)
├── requirements.txt        # Python environment dependencies
└── README.md               # Project documentation[Your Profile Link - Optional]

📈 Current Status
[x] Initial system setup and topology generation.

[x] 100ns production run for Berberine clusters.

[ ] Post-simulation analysis (RMSD/Rg/H-Bonds) - In Progress.

[ ] Free energy landscape calculation - Planned.

👨‍🔬 About Me
Jiahao Lv (吕佳豪) MSc Student in Aquaculture, Nanjing Agricultural University Research Interests: * Molecular Self-assembly

Antimicrobial Mechanisms of Herbal Compounds

Computational Biophysics (MD Simulations)

Goal: Aspiring to pursue a PhD in Europe focusing on the intersection of biomaterials and computational modeling.

📧 Contact: lvjh0618@163.com
🔗 LinkedIn: [leejia030618@gmail.com]
