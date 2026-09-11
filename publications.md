---
layout: default
title: Publications
---

# Publications

This page lists my research publications, conference presentations, and software-related research outputs.

---

## Submitted Conference Papers

### Angle-resolved annihilation-photon correlation factors for an annular NaI(Tl) detector

**Authors:** Ayush Priyadarshi, Rahul Chauhan, Asit Srivastava, and G. Anil Kumar<br>
**Intended venue:** DAE Symposium on Nuclear Physics 2026<br>
**Status:** Submitted on 8 September 2026<br>
**My role:** First and corresponding author

This manuscript presents a full-interval, angle-resolved calculation of annihilation-photon correlation factors for an annular NaI(Tl) detector. I corrected and extended an earlier unpublished mathematical treatment, completed the Geant4 analysis, implemented and validated the numerical calculation, prepared the figures, developed the public software package, and wrote the complete manuscript.

**Reproducibility package:**<br>
[Angular Factors Calculator](https://github.com/ayushpriyadarshi-18/angular-factors-calculator)

---

## Conference Presentations

### A Python-based Tool for Automated Geant4 Simulations of Scintillation Detectors

**Authors:** Ayush Priyadarshi, G. Anil Kumar, Kavish Madhan, and Virender Ranga  
**Venue:** IEEE Nuclear Science Symposium 2026  
**Status:** Accepted for poster presentation  

**Related recognition:** Selected recipient of the **2026 Paul Phelps Continuing Education Grant**, recognising promise in radiation instrumentation and supporting participation in IEEE NSS/MIC/RTSD 2026 short courses.

This paper presents a compact Geant4–Python simulation-analysis tool for reproducible scintillation detector response studies. The tool connects a configurable Geant4 C++ simulation backend with Python automation for macro generation, simulation execution, ROOT-file validation, deposited-energy spectrum generation, count extraction, and summary table generation.

The workflow is demonstrated using Cs-137 simulations across solid cylindrical, hollow cylindrical, and near-4π soccerball-style detector geometries. High-statistics validation runs on the PARAMGanga supercomputing facility demonstrate that the same workflow can be extended toward larger detector-response simulation campaigns.

**Related software:**  
[Geant4 Detector Simulation Pipeline](https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline)

---

## Research Software

### Angular Factors Calculator

**Developer:** Ayush Priyadarshi<br>
**Repository:** [angular-factors-calculator](https://github.com/ayushpriyadarshi-18/angular-factors-calculator)<br>
**Year:** 2026

A public Python package, command-line tool, and reproducibility record for the annular-detector angular-factor manuscript. It supports ROOT analysis, coefficient-based calculation, independent numerical cross-checks, structured JSON/CSV outputs, regression tests, continuous integration, and citation metadata.

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

This repository forms the software basis of my master's thesis and first-author IEEE NSS 2026 poster presentation.

---

## Thesis

### A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations

**Degree:** Integrated BS–MS Physics  
**Institution:** Indian Institute of Technology Roorkee  
**Supervisor:** Prof. Anil Kumar Gourishetty<br>
**Period:** 2025–2026  

My master's thesis developed an automated Geant4–Python workflow for campaign-level scintillation detector response studies. The work focused on reproducibility, traceability, simulation automation, ROOT-based analysis, and detector-response comparison across materials and geometries.
