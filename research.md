---
layout: default
title: Research
---

# Research

My research interests lie at the intersection of computational physics, scientific software development, detector simulations, and research instrumentation. I am especially interested in building reproducible simulation and analysis workflows for experimental physics.

---

## Research Focus

My current work uses Geant4-based detector simulation, custom radioactive-source modelling, and ROOT analysis to study coincidence summing in beta-plus emitters. The research builds on the automated simulation platform developed during my undergraduate thesis.

The central progression of my work is: **build a reusable simulation platform → validate it against published calculations and measurements → apply it to an active detector-physics problem.**

---

## Current Research

### Coincidence-Summing Correction for β⁺ Emitters in a Near-4π NaI(Tl) Detector Array

**Institution:** Department of Physics, Indian Institute of Technology Roorkee<br>
**Supervisor:** Prof. Anil Kumar Gourishetty<br>
**Period:** July 2026–Present<br>
**Status:** Ongoing research; peer-reviewed journal manuscript planned with confirmed second authorship

When multiple photons from the same decay deposit energy within a detector's resolving interval, counts can be lost from individual photopeaks and transferred into sum peaks. In beta-plus emitters, the two back-to-back 511 keV annihilation photons introduce an additional geometry-dependent angular relationship that must be treated carefully in a high-efficiency detector array.

Prof. Gourishetty is developing the coincidence-summing correction formalism. My contribution is the computational work required to apply and validate it:

- Extended my Geant4–Python platform with new detector, source, campaign, and analysis capabilities.
- Reconstructed the published eight-block near-4π NaI(Tl) reference detector of Byun et al.
- Reproduced its published angular factors within a maximum relative difference of 2.3%.
- Implemented custom Geant4 sources from nuclear decay schemes, including probabilistic gamma emission and back-to-back 511 keV annihilation photons.
- Completed 10^8-event campaigns for Na-22, O-14, and Sc-44.
- Calculated detector-specific angular factors for the 32-element TIFR soccer-ball NaI(Tl) array.
- Benchmarked the detector model against published experimental measurements for the physical TIFR array, with simulated efficiencies consistent within 5%.
- Validated the correction procedure using independent coincidence-free monoenergetic simulations.

The detector-specific factor values, detailed correction results, equations, calculation tables, plots, and research code remain private until approved for public release by the supervisor.

---

## Undergraduate Thesis

### A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations

**Institution:** Department of Physics, Indian Institute of Technology Roorkee<br>
**Supervisor:** Prof. Anil Kumar Gourishetty<br>
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

As part of workflow validation, high-statistics simulations were executed on the PARAMGanga high-performance computing facility at IIT Roorkee. These included simulations with up to 10^8 events, demonstrating that the same workflow can be used for both lightweight reference examples and larger research campaigns.

---

## Research Outputs

This work has resulted in:

- Undergraduate thesis:
  *A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations*

- Research software repository:
  [Geant4 Detector Simulation Pipeline](https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline)

- First-author conference presentation:
  *A Python-based Tool for Automated Geant4 Simulations of Scintillation Detectors*<br>
  Accepted for poster presentation at IEEE Nuclear Science Symposium 2026.

---

## Broader Direction

My broader research direction is to develop computational tools, simulation workflows, and instrumentation-support software for experimental physics. I am interested in applying these skills to detector physics, radiation detection, optical simulations, astrophysical instrumentation, and high-performance scientific computing.
