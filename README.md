# Computer-Aided Design & Manufacturing (CAD/CAM) ⚙️🖥️

[![Software](https://img.shields.io/badge/Software-CATIA_V5-blue.svg)](https://www.3ds.com/products-services/catia/)
[![Domain](https://img.shields.io/badge/Domain-CAD_%2F_CAM-orange.svg)]()
[![Universidad de Sevilla](https://img.shields.io/badge/Academic-Universidad_de_Sevilla-red?style=flat-square&logo=university&logoColor=white)](https://www.us.es/)

A collection of 3D modeling, assembly, and Computer Numerical Control (CNC) manufacturing simulation projects.

Developed for the **Computer-Aided Design and Manufacturing (DFAO)** course within the Bachelor's Degree in Aerospace Engineering at Universidad de Sevilla.

---

## 📌 Project Overview

This repository demonstrates a complete mechanical engineering workflow using **CATIA V5**, ranging from the conceptualization and modeling of individual parts to the simulation of their manufacturing process using CNC machine tools.

The repository is divided into two main practical blocks:

### 📐 Block 1: Computer-Aided Design (CAD)
Parametric design and assembly of a complex mechanical system: a **motion transformation gearbox** (converting rotary input motion into reciprocating linear motion).
* **Part Modeling (`.CATPart`):** Design of the casing, input shaft, sliders, and fasteners, strictly adhering to the tolerances and dimensions of the original blueprints.
* **Assembly (`.CATProduct`):** Integration of all components applying geometric and contact constraints (coincidences, offsets, angles) to ensure the kinematic viability of the assembly.

### 🏭 Block 2: Computer-Aided Manufacturing (CAM)
Design and programming of the manufacturing process for a custom aluminum part (Logo with the initials "ARM") using a 2.5-axis machining center.
* **Tool Definition:** Configuration of the tool catalog, including face mills (D80), drill bits, and countersinks, adjusting cutting speeds and feed rates to comply with the machine's 4500 rpm limit.
* **Machining Strategies:** Programming of pocketing, profile contouring, and drilling operations, optimizing approach and retract trajectories.
* **CNC Code Generation:** Collision verification, cycle time calculation (approx. 18.8 minutes), and generation of the machine code (APT/ISO code) ready to be loaded into the numerical control.

## 📂 Repository Contents

* **`docs/`**: Contains the original project statements and the detailed CAM report featuring the operation tree and cutting parameters.
* **`cad/`**: 3D design files (`.CATPart`) and the complete assembly (`.CATProduct`) of the transformation gearbox.
* **`cam/`**: Process files (`.CATProcess`), the rough/final part models, and the text files containing the generated CNC code.

## 👨‍💻 Author

* **Alejandro Rivera Míguez**

---

Bachelor in Aerospace Engineering | Universidad de Sevilla

---
*Disclaimer: This is an academic project. The CAD models and generated CNC codes are intended for educational purposes and technical demonstration of PLM/CAM software usage.*
