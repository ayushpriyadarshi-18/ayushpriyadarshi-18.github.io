---
layout: default
title: Research
---

# Research

My research interests lie at the intersection of computational physics, scientific software development, detector simulations, and research instrumentation. I am especially interested in building reproducible simulation and analysis workflows for experimental physics.

---

## Research Focus

My current work focuses on Geant4-based scintillation detector response simulations. The goal is to reduce the manual effort involved in repeated detector-response studies by connecting simulation setup, execution, ROOT analysis, spectrum generation, and count extraction into a structured workflow.

This work is centered on the development of a Python-assisted Geant4 workflow for automated scintillation detector simulations.

---

## Undergraduate Thesis

### A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations

**Institution:** Department of Physics, Indian Institute of Technology Roorkee  
**Supervisor:** Dr. Anil Kumar Gourishetty  
**Period:** 2025–2026  

My undergraduate thesis developed an automated Geant4–Python workflow for campaign-level scintillation detector response studies. The workflow integrates a configurable Geant4 C++ backend with Python automation for macro generation, batch execution, ROOT output validation, deposited-energy spectrum generation, count extraction, plotting, and table generation.

The framework supports:

- Monoenergetic gamma simulations
- Radioactive-decay simulations
- Beta-plus decay cases
- Material-dependent detector studies
- Detector-size studies
- Geometry-dependent response studies

---

## Detector Simulation Work

The simulation backend supports multiple detector geometries:

- Solid cylindrical scintillation detectors
- Hollow annular detector geometries
- Custom near-4π soccer-ball-style detector geometry

Implemented scintillator materials include:

- NaI
- LaBr3
- CsI
- BGO
- GGAG
- PbWO4

These configurations allow systematic comparison of detector response as a function of geometry, material, source configuration, and event statistics.

---

## Simulation and Analysis Workflow

The research workflow connects the following stages:

1. Define detector material, geometry, source configuration, and event count.
2. Generate Geant4 macro files using Python.
3. Run simulation campaigns through the Geant4 executable.
4. Validate ROOT output files.
5. Extract deposited-energy information from the event tree.
6. Generate deposited-energy spectra.
7. Extract photopeak, sum-peak, and total non-zero deposited-energy counts.
8. Export final plots and comparison tables.

This approach makes the simulation-analysis chain more traceable and easier to extend across new detector materials, geometries, and source cases.

---

## High-Performance Computing

As part of workflow validation, high-statistics simulations were executed on the PARAMGanga high-performance computing facility at IIT Roorkee. These included Cs-137 simulations with up to 10^8 events, demonstrating that the same workflow can be used for both lightweight reference examples and larger simulation campaigns.

---

## Research Outputs

This work has resulted in:

- Undergraduate thesis:  
  *A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations*

- Research software repository:  
  [Geant4 Detector Simulation Pipeline](https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline)

- First-author conference submission:  
  *A Python-based Tool for Automated Geant4 Simulations of Scintillation Detectors*  
  Submitted to IEEE Nuclear Science Symposium 2026.

---

## Broader Direction

My broader research direction is to develop computational tools, simulation workflows, and instrumentation-support software for experimental physics. I am interested in applying these skills to detector physics, radiation detection, optical simulations, astrophysical instrumentation, and high-performance scientific computing.