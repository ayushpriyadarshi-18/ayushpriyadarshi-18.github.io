# Software

## Geant4 Detector Simulation Pipeline

**Role:** Developer and Maintainer  
**Repository:** https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline  

The Geant4 Detector Simulation Pipeline is a Python-assisted Geant4 workflow for automated scintillation detector response simulations. It was developed to reduce manual work in repeated detector-response studies and to make simulation campaigns more reproducible and traceable.

The software connects a configurable Geant4 C++ simulation backend with Python tools for macro generation, campaign execution, ROOT-file validation, deposited-energy spectrum generation, peak-count extraction, total-count extraction, plotting, and output organisation.

---

## Main Features

- Automated Geant4 macro generation
- Batch execution of simulation campaigns
- ROOT-file validation and deposited-energy extraction
- Spectrum generation from `EdepCrystal_keV`
- Photopeak, sum-peak, and total non-zero count extraction
- CSV/table generation for comparison studies
- Support for multiple detector geometries
- Support for multiple scintillator materials
- Reference outputs for reproducible testing

---

## Detector Geometries

The pipeline currently supports:

- Solid cylindrical scintillation detector geometry
- Hollow annular detector geometry
- Near-4π soccer-ball-style modular detector geometry

These geometries are used to compare detector response under different angular-coverage and source-placement conditions.

---

## Detector Materials

Implemented scintillator materials include:

- NaI
- LaBr3
- CsI
- BGO
- GGAG
- PbWO4

---

## Simulation and Analysis Workflow

The typical workflow is:

1. Define source, detector material, geometry, and event count.
2. Generate Geant4 macro files using Python.
3. Run the Geant4 simulation campaign.
4. Validate ROOT output files.
5. Extract deposited-energy information from the ROOT event tree.
6. Generate deposited-energy spectra.
7. Extract peak counts and total non-zero deposited-energy counts.
8. Export results as tables and plots.

---

## Research Use

This software formed the basis of my undergraduate thesis:

*A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations*

It is also the software basis for my first-author conference paper submitted to IEEE Nuclear Science Symposium 2026:

*A Python-based Tool for Automated Geant4 Simulations of Scintillation Detectors*

The pipeline is actively maintained and used as part of ongoing detector simulation research.

---

## Related Links

GitHub repository:  
https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline

Publications page:  
publications.md
