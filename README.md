# Finite-Element Analysis of Crack Arrest Properties of Resin Toughened Composites

**Project Code:** RP-3  
**Phase:** Phase-2  
**Institution:** Amrita School of Engineering, Bengaluru  
**Department:** Mechanical Engineering  
**Date:** 01-08-2022

---

## Project Overview

This repository contains comprehensive research on the **Finite-Element Analysis (FEA) of Crack Arrest Properties in Resin-Toughened Composites**. The project focuses on understanding delamination failure mechanisms in aerospace composite structures and implementing Through-Thickness Reinforcements (TTR) to enhance fracture toughness and structural integrity.

---

## Quick Links

- 📚 [Documentation](/docs/)
- 🖼️ [Technical Images](/images/)
- 🔧 [FEA Models](/models/)
- 📊 [Analysis Data](/data/)

---

## Key Highlights

✅ **Phase-2 Completion Status:** In Progress  
✅ **Geometry Design:** Complete with ANSYS CAD  
✅ **Mesh Generation:** Successfully refined (0.2mm global sizing)  
✅ **FEA Setup:** ANSYS Workbench R17.2 configured  
✅ **Literature Review:** 7 key research papers surveyed  

---

## Table of Contents

1. [Introduction](#introduction)
2. [Problem Statement](#problem-statement)
3. [Literature Survey](#literature-survey)
4. [Motivation](#motivation)
5. [Objectives](#objectives)
6. [Challenges](#challenges)
7. [Plan of Action](#plan-of-action)
8. [Methodology](#methodology)
9. [Technical Specifications](#technical-specifications)
10. [Expected Outcomes](#expected-outcomes)
11. [Folder Structure](#folder-structure)

---

## Introduction

Fracture mechanics is a branch of mechanics dealing with the investigation of fracture propagation in materials. It calculates the driving force on a crack using analytical solid mechanics methods and characterizes the material's resistance to fracture using experimental solid mechanics methods.

### Key Concepts

- **Stress Intensity Factor (K):** Characterizes the strength of a singularity at a crack tip
- **Linear Elastic Fracture Mechanics (LEFM):** Applicable when the plastic zone at the crack tip is small
- **Three Modes of Fracture:**
  - **Mode I (Opening):** Tensile stress parallel to crack plane and perpendicular to crack front
  - **Mode II (Sliding):** Shear stress parallel to crack plane and perpendicular to crack front
  - **Mode III (Tearing):** Shear stress parallel to crack plane and parallel to crack front

---

## Problem Statement

**Delamination is a critical failure mode in laminated fiber-reinforced polymer matrix composites.** It is one of the key factors differentiating composite behavior from metallic structures.

### Root Causes:
- High interlaminar stresses in conjunction with typically very low through-thickness strength
- Fibers lying in the plane of a laminate do not provide reinforcement through the thickness
- Composite relies on relatively weak matrix to carry loads in that direction
- Matrix resins are typically quite brittle

### Solution: Through-Thickness Reinforcements (TTR)

TTR produces a bridging region and hides crack development when delamination cracks develop, improving:
- **Fracture Toughness**
- **Impact Resistance**
- **Compression After Impact (CAI) Strength**
- **Interlaminar Strength**
- **Stiffness & Pull-off Strength**

---

## Literature Survey

| # | Title | Authors |
|---|-------|----------|
| 1 | Modelling of dynamic mode I crack growth in glass fiber-reinforced polymer composites: fracture energy and failure mechanism | Y. Liu, F.P. van der Meer, L.J. Sluys, L. Ke |
| 2 | Finite element analysis of natural fibers composites: A review | Mohammad Alhijazi, Qasim Zeeshan, Zhaoye Qin, Babak Safaei, Mohammed |
| 3 | Three-Dimensional Modelling of Concrete Reinforced with Randomly Distributed Fiber | Sahar Y. Ghanem |
| 4 | Finite-Element Analysis of Crack Arrest Properties of Fiber Reinforced Composites Application in Semi-Elliptical Cracked Pipelines | Linyuan Wang, Shulei Song, Hongbo Deng, Kai Zhong |
| 5 | Finite element analyses of mode I interlaminar Delamination in z-fibre reinforced composite laminates | Marcello Grassi & Xiang Zhang |
| 6 | Voids in fiber-reinforced polymer composites: A review on their formation, characteristics, and effects on mechanical performance | Mahoor Mehdikhani, Larissa Gorbatikh, Ignaas Verpoest, Stepan V Lomov |
| 7 | Dynamic fracture toughness of polymer Composites | Harmeet Kaur |

---

## Motivation

- **Aerospace Industry Need:** Composite structures require enhanced damage tolerance
- **Cost-Effectiveness:** Resin-toughened composites offer superior properties at reasonable costs
- **Performance Enhancement:** TTR mechanisms significantly improve structural integrity
- **Research Gap:** Limited comprehensive FEA studies on crack arrest properties
- **Industrial Application:** Results applicable to aircraft, automotive, marine, and sports equipment

---

## Objectives

1. **Optimal Parameter Selection:** Identify best FEA study parameters for crack arrest analysis
2. **Crack Energy Propagation Modeling:** Develop models to investigate and visualize crack energy propagation
3. **Fracture Energy Reduction:** Research methods to reduce fracture energy propagation
4. **Composite Delamination Prevention:** Utilize composites to minimize delamination and fracture
5. **Geometry Modeling:** Create accurate fracture geometry models and simulations
6. **Computational Visualization:** Visualize crack energy propagation from computational perspective
7. **Design Optimization:** Provide recommendations for improved composite designs

---

## Challenges

- Accurate mesh refinement at crack tips
- Capturing singular stress fields near crack tips
- Modeling fiber/matrix debonding mechanisms
- Incorporating through-thickness reinforcement effects
- Validation with experimental data
- Computational resource optimization
- Multi-scale modeling integration

---

## Plan of Action

### Phase 1: Geometry Design & Modeling ✓
- Design geometry with crack configuration
- Model geometry according to problem statement
- Apply boundary conditions and loading

### Phase 2: FEA Analysis & Parameter Study (Current)
- Study FEA from ANSYS and modify parameters
- Change parameters as per problem statement
- Analyze crack arrest behavior

### Phase 3: Composite Material Study
- Study composites as per problem statement
- Act on FEA for desired results
- Optimize design for maximum crack arrest capability

---

## Methodology

### Step 1: Geometric Design and Illustration
The geometric model is a three-dimensional (3D) computer-aided design (CAD) model used to create physical systems with crucial representation.

**Crack Geometry Coordinates (meters):**
- Point 1: (0, 5E−5)
- Point 2: (0.015, 5E−5)
- Point 3: (0.02, 0)
- Point 4: (0.015, −5E−5)
- Point 5: (0, −5E−5)
- Point 6: (0, −0.1)
- Point 7: (0.1, −0.1)
- Point 8: (0.1, 0)
- Point 9: (0.1, 0.1)
- Point 10: (0, 0.1)

**Crack Parameters:**
- Crack Front: 1E-5 meters (0.01 mm)
- Rectangular box configuration

### Step 2: Parameters for Finite-Element Investigations
The literature survey's inputs are extensively analyzed and iterated to accomplish specific objectives.

**Meshing Parameters:**
- Mesh Sizing Ratio: 0.2 mm
- Mesh Refinement: Successfully applied
- Mesh Type: Tetrahedral/Triangular elements

### Step 3: Composite Materials Development and Utilization
Composite selection for the problem statement is executed with application of the composite in FEA studies.

---

## Technical Specifications

### Software Used
- **Composite Analysis:** Helios Composite by Autodesk
- **FEA Analysis:** ANSYS Workbench R17.2
- **Alternative FEA:** ABAQUS
- **CAD Modeling:** ANSYS Design Modeler

### Analysis Parameters
- **Analysis Type:** Nonlinear dynamics with implicit scheme
- **Load Cases:** Dynamic mode-I loading at strain rates up to 250/s
- **Fracture Parameter:** J-integral (dynamic J-integral per time step)
- **Element Type:** 3D solid tetrahedral elements (SOLID185)
- **Crack Tip Treatment:** Refined mesh with singularity elements

### Material Properties
- **Matrix:** Epoxy resin (thermoset)
- **Reinforcement:** Glass fibers or natural fibers
- **TTR Methods:** Z-fiber pinning, particles, fillers, flakes, stitching, 3D woven fabrics

---

## Expected Outcomes

1. **Comprehensive FEA Models:** Validated finite element models for crack arrest analysis
2. **Optimal Design Parameters:** Recommendations for TTR configuration and placement
3. **Fracture Energy Maps:** Visualization of crack propagation and energy distribution
4. **Design Guidelines:** Practical guidance for composite structure design
5. **Research Publication:** Findings suitable for peer-reviewed journal submission
6. **Performance Metrics:** Quantified improvements in fracture toughness and impact resistance
7. **Industry Applicability:** Results transferable to aerospace and automotive applications

---

## Folder Structure

```
crack-arrest-composite-fea/
├── README.md                          # Project overview
├── docs/                              # Documentation
│   ├── phase_2_synopsis.md            # Phase-2 synopsis
│   └── references.md                  # Bibliography
├── images/                            # Technical diagrams & figures
│   ├── 01_fracture_mechanics/         # Fracture modes
│   ├── 02_geometry_design/            # ANSYS geometry designs
│   ├── 03_mesh_analysis/              # Meshing visualizations
│   ├── 04_delamination/               # Delamination mechanisms
│   ├── 05_composite_structure/        # Material composition
│   └── 06_literature_survey/          # Reference materials
├── models/                            # FEA models & geometry
│   ├── geometry_coordinates.txt       # Crack geometry data
│   └── README.md                      # Model documentation
├── data/                              # Analysis data & results
│   ├── mesh_parameters.txt            # Meshing specifications
│   ├── material_properties.txt        # Composite properties
│   └── README.md                      # Data documentation
└── LICENSE                            # Project license
```

---

## Contact Information

**Institution:**  
Amrita School of Engineering, Bengaluru  
Department of Mechanical Engineering

**Project Guide:**  
R Pramod  
Assistant Professor (Sr Gr)  
Department of Mechanical Engineering

---

## License

This project is part of academic research at Amrita School of Engineering. All content is provided for educational and research purposes.

---

## Acknowledgments

- Amrita School of Engineering, Bengaluru
- Department of Mechanical Engineering
- All referenced researchers and authors in the literature survey
- ANSYS and Autodesk for software tools

---

**Last Updated:** May 29, 2026  
**Status:** Phase 2 - Active Development  
**Project Code:** RP-3
