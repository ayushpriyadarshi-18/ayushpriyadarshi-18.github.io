---
layout: default
title: Publications
---

# Publications

This page lists my research publications, conference submissions, and software-related research outputs.

---

## Conference Submissions

### A Python-based Tool for Automated Geant4 Simulations of Scintillation Detectors

**Authors:** Ayush Priyadarshi, G. Anil Kumar, Kavish Madhan, and Virender Ranga  
**Venue:** IEEE Nuclear Science Symposium 2026  
**Status:** Submitted; under review  

This paper presents a compact Geant4–Python simulation-analysis tool for reproducible scintillation detector response studies. The tool connects a configurable Geant4 C++ simulation backend with Python automation for macro generation, simulation execution, ROOT-file validation, deposited-energy spectrum generation, count extraction, and summary table generation.

The workflow is demonstrated using Cs-137 simulations across solid cylindrical, hollow cylindrical, and near-4π soccerball-style detector geometries. High-statistics validation runs on the PARAMGanga supercomputing facility demonstrate that the same workflow can be extended toward larger detector-response simulation campaigns.

**Related software:**  
[Geant4 Detector Simulation Pipeline](https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline)

---

## Research Software

### Geant4 Detector Simulation Pipeline

**Developer:** Ayush Priyadarshi  
**Repository:** [geant4-detector-simulation-pipeline](https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline)  
**Year:** 2026  

A public, version-controlled Geant4–Python repository for automated scintillation detector simulations. The repository contains Geant4 source code, Python automation scripts, macro examples, reference outputs, analysed spectra, tabulated results, and geometry visualisation files.

The software supports:

- Automated Geant4 macro generation
- Campaign execution
- ROOT-file validation
- Deposited-energy spectrum generation
- Peak-count extraction
- Total non-zero count extraction
- CSV/table generation
- Geometry-dependent detector response studies

This repository forms the software basis of my undergraduate thesis and first-author IEEE NSS 2026 conference submission.

---

## Thesis

### A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations

**Degree:** Integrated BS–MS Physics  
**Institution:** Indian Institute of Technology Roorkee  
**Supervisor:** Dr. Anil Kumar Gourishetty  
**Period:** 2025–2026  

My undergraduate thesis developed an automated Geant4–Python workflow for campaign-level scintillation detector response studies. The work focused on reproducibility, traceability, simulation automation, ROOT-based analysis, and detector-response comparison across materials and geometries.