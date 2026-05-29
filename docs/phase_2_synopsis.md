# Phase-2 Synopsis

**Project Title:** Finite-Element Analysis of Crack Arrest Properties of Resin Toughened Composites  
**Project Code:** RP-3  
**Phase:** Phase-2  
**Institution:** Amrita School of Engineering, Bengaluru  
**Date:** 29-05-2026

---

## Introduction

The most dangerous failure mode in aerospace composite structures is **Delamination**. Through Thickness Reinforcements (TTR) produce a bridging region and hide crack development when delamination cracks develop.

### Benefits of TTR:
- Fracture toughness improvement
- Impact resistance enhancement
- Compression after impact (CAI) strength
- Interlaminar strength improvement
- Stiffness and pull-off strength enhancement

### TTR Application Methods:
1. Z-fiber pinning
2. Particulates
3. Fillers
4. Flakes
5. Stitching
6. 3D woven composites

---

## TTR Considerations

### Advantages:
- Effectively suppresses delamination through through-the-thickness reinforcement
- Increases in-plane and through-thickness strength
- Fiber bridging mechanism enhances toughness

### Challenges:
- Fiber breakage and misalignment can occur
- May reduce in-plane stiffness
- Can reduce in-plane fracture resistance
- Z-pinning requires careful design (rigidity more stapled)

---

## Material Selection: Resin-Toughened Composites

### Definition:
A resin (or "plastic") is a substance used to transmit stress between the reinforcing fibers of a composite material. Resins keep fibers together and protect them from mechanical and environmental degradation.

### Advantages:
- Cost-effective solutions
- Outstanding mechanical properties
- Wide range of available formulations
- Suitable for critical applications

### Resin Types:

#### Thermoset Resins:
- Polyester
- Epoxy
- Vinyl ester
- Polyurethane

#### Thermoplastic Resins:
- ABS
- Polyethylene
- Polystyrene
- Polycarbonate

---

## Operations to be Performed

### 1. Literature Survey
**Purpose:** Critical foundation for understanding problem statement

**Status:** ✓ Ongoing
- Multiple reference and research articles reviewed
- Key publications identified and documented
- Understanding of state-of-the-art crack arrest mechanisms
- Acknowledgement of existing research ongoing

### 2. Selection of Composite
**Purpose:** Choose practical and affordable composite for investigation

### 3. Software Part

#### 3.1 For Composite Studies: Helios Composite by Autodesk
- Conceptual design and laminate development
- Material property calculation
- Strength assessment (first ply failure, progressive failure)
- Testing modules for various structures

#### 3.2 For FEA Studies: ANSYS Workbench & ABAQUS
- Computational analysis for crack arrest properties
- Stress concentration visualization
- Delamination propagation modeling
- Dynamic loading analysis

---

## Phase-2 Work Completed

### 1. Geometry Design & Modeling ✓

**Rectangular Box Coordinates (meters):**
- Point 1: (0, 5E−5) | Point 6: (0, −0.1)
- Point 2: (0.015, 5E−5) | Point 7: (0.1, −0.1)
- Point 3: (0.02, 0) | Point 8: (0.1, 0)
- Point 4: (0.015, −5E−5) | Point 9: (0.1, 0.1)
- Point 5: (0, −5E−5) | Point 10: (0, 0.1)

**Crack Specification:**
- Crack front: 1E-5 meters (0.01 mm)
- Configuration: One side of rectangular box
- Design tool: ANSYS Design Modeler (CAD)

### 2. Meshing & Refinement ✓

**Mesh Parameters:**
- Sizing ratio: 0.2 mm
- Element type: Tetrahedral/Triangular
- Refinement: Successfully completed
- Mesh density: Highest concentration at crack tip

### 3. ANSYS FEA Model Setup ✓

**Software Version:** ANSYS R17.2  
**Analysis Type:** Nonlinear with implicit dynamics  
**Fracture Parameter:** Dynamic J-integral per time step

---

## Key Research Parameters

### Optimal Parameter Selection for FEA
- Mesh sizing: 0.2 mm (validated)
- Crack front refinement: 1E-5 m
- Loading rate: Up to 250/s (strain rate)
- Analysis type: Implicit dynamics with J-integral

### Methods for Fracture Energy Reduction
1. TTR Implementation
2. Material Optimization
3. Geometry Design
4. Layup Configuration
5. Hybrid Reinforcement

---

## Expected Phase-3 Outcomes

1. **Composite Material Studies** - Detailed property analysis
2. **Design Validation** - FEA correlation with experimental data
3. **Industry Applicability** - Aerospace/automotive recommendations
4. **Research Contribution** - Publication-ready results

---

## References

1. Y. Liu, F.P. van der Meer, L.J. Sluys, L. Ke - Dynamic mode I crack growth
2. Mohammad Alhijazi et al. - Finite element analysis of natural fibers composites
3. Sahar Y. Ghanem - 3D Modelling of Concrete Reinforced with Fiber
4. Linyuan Wang et al. - Crack Arrest Properties Application in Pipelines
5. Marcello Grassi & Xiang Zhang - Mode I interlaminar Delamination
6. Mahoor Mehdikhani et al. - Voids in fiber-reinforced composites
7. Harmeet Kaur - Dynamic fracture toughness of polymer Composites

---

**Last Updated:** May 29, 2026
