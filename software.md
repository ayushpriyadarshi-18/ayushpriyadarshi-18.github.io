---
layout: default
title: Software
---

# Software

My software work focuses on building reproducible tools for detector simulation, scientific computing, and automated analysis workflows.

---

## Geant4 Detector Simulation Pipeline

**Role:** Developer and Maintainer  
**Repository:** [geant4-detector-simulation-pipeline](https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline)

The Geant4 Detector Simulation Pipeline is a Python-assisted Geant4 workflow for automated scintillation detector response simulations. It was developed to reduce manual effort in repeated detector-response studies and to make simulation campaigns more reproducible, traceable, and easier to extend.

The software connects a configurable Geant4 C++ backend with Python tools for simulation setup, campaign execution, ROOT-file validation, deposited-energy spectrum generation, count extraction, plotting, and output organisation.

---

## Motivation

Systematic detector-response studies often require many related Geant4 simulations across different source energies, detector materials, detector geometries, event counts, and source configurations. Manually preparing macros, running simulations, checking outputs, generating spectra, and extracting counts can become repetitive and error-prone.

This pipeline was developed to automate that workflow from simulation configuration to final spectra and count tables.

---

## Main Capabilities

- Automated Geant4 macro generation
- Batch execution of simulation campaigns
- ROOT-file validation and deposited-energy extraction
- Spectrum generation from `EdepCrystal_keV`
- Photopeak, sum-peak, and total non-zero count extraction
- CSV/table generation for comparison studies
- Reproducible output organisation
- Reference outputs for testing and demonstration

---

## Supported Detector Geometries

The pipeline currently supports three detector configurations:

- Solid cylindrical scintillation detector geometry
- Hollow annular detector geometry
- Near-4π soccer-ball-style modular detector geometry

These geometries allow detector response to be compared under different angular-coverage and source-placement conditions.

---

## Supported Scintillator Materials

Implemented scintillator materials include:

- NaI
- LaBr3
- CsI
- BGO
- GGAG
- PbWO4

---

## Simulation and Analysis Workflow

A typical simulation campaign follows this structure:

1. Define detector material, geometry, source configuration, and event count.
2. Generate Geant4 macro files using Python.
3. Execute Geant4 simulations.
4. Validate ROOT output files.
5. Extract deposited-energy data from the event tree.
6. Generate deposited-energy spectra.
7. Extract photopeak, sum-peak, and total non-zero deposited-energy counts.
8. Export final results as plots and comparison tables.

---

## Research Use

This software forms the basis of my undergraduate thesis:

*A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations*

It is also the software basis for my first-author conference paper submitted to IEEE Nuclear Science Symposium 2026:

*A Python-based Tool for Automated Geant4 Simulations of Scintillation Detectors*

The pipeline is actively maintained and used as part of ongoing detector simulation research.

---

## Links

- [GitHub Repository](https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline)
- [Research Page](research.md)
- [Publications Page](publications.md)