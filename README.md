# NIF Laser Fusion Seminar 

*A short presentation on the National Ignition Facility (LLNL) and the principles of inertial confinement fusion.*

> **Note:** The presentation slides (`slides.pdf`) and the seminar itself are in German, as this project was created as a prerequisite for the module exam. The simulation code, data processing scripts, and repository structure are maintained in English.

## 🎓 Academic Context
This repository contains the presentation and supplementary materials for a short seminar in the module **"Kerne und Teilchen"** (Nuclear and Particle Physics). It was created as a qualification requirement for the module exam in the Physics B.Sc. program at the **Friedrich-Schiller-Universität Jena**.

## 🔬 Overview
The seminar focuses on the laser fusion experiments conducted at the Lawrence Livermore National Laboratory (LLNL). Specifically, it addresses the breakthrough in December 2022, where target gain > 1 was achieved, and discusses the implications of inertial confinement fusion as a potential solution to the energy crisis.

Topics covered in the slides (Max. 5 slides / 10 minutes):
1. Principle of Inertial Confinement Fusion (ICF)
2. The National Ignition Facility (NIF) setup
3. Hohlraum thermodynamics and target compression
4. Energy yield analysis (Dec 2022 breakthrough)
5. Future perspectives and challenges

## 🛠️ Built With
* **LaTeX (Beamer):** For typesetting the presentation slides and generating complex mathematical equations.
* **Python (NumPy, Matplotlib):** Used to calculate the thermodynamic energy balance and generate the data visualizations embedded in the slides.

## 📂 Repository Structure
```text
.
├── README.md
├── src/
│   └── energy_yield_plot.py    # Python script for generating visualizations
├── slides/
│   ├── main.tex                # LaTeX source code for the presentation
│   ├── figures/                # Images and generated plots
│   └── main.pdf                # Compiled presentation (German)
└── references/                 # Papers and LLNL press releases used
