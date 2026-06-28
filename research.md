[Home](index.md) | [Research](research.md) | [Software](software.md) | [Projects](projects.md) | [Publications](publications.md) | [CV](cv.md)

---

# Research

My research interests lie at the intersection of computational physics, scientific software development, detector simulations, and research instrumentation. I am especially interested in building tools and workflows that make experimental and detector-based physics studies more reproducible, automated, and scalable.

---

## Undergraduate Thesis Research

### A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations

**Institution:** Department of Physics, Indian Institute of Technology Roorkee  
**Supervisor:** Dr. Anil Kumar Gourishetty  
**Period:** 2025–2026  

My undergraduate thesis focused on developing an automated Geant4–Python workflow for scintillation detector response simulations. The project was motivated by the need to run large numbers of related Geant4 simulations in a reproducible and organized way.

The workflow integrates:

- A configurable Geant4 C++ simulation backend
- Python-based macro generation
- Automated campaign execution
- ROOT output validation
- Deposited-energy spectrum generation
- Photopeak, sum-peak, and total-count extraction
- CSV/table generation
- Plotting and output organization

The framework supports monoenergetic gamma simulations, radioactive-decay simulations, beta-plus decay cases, material-dependent studies, detector-size studies, and geometry-dependent studies.

---

## Detector Simulation Work

The simulation backend supports multiple detector configurations, including:

- Solid cylindrical scintillation detectors
- Hollow annular detector geometries
- Custom near-4π soccer-ball-style detector geometry

The detector materials implemented in the simulation workflow include:

- NaI
- LaBr3
- CsI
- BGO
- GGAG
- PbWO4

These configurations allow systematic studies of detector response as a function of geometry, material, source type, and event statistics.

---

## Scientific Motivation

In gamma spectroscopy and detector-response studies, repeated simulations are often required across several combinations of source energy, detector material, detector geometry, detector size, and event count. Manually preparing macros, running simulations, checking ROOT files, generating spectra, and extracting counts can become repetitive and error-prone.

My work focuses on reducing this manual effort by creating a structured simulation-analysis pipeline. The goal is not to replace Geant4, but to make Geant4-based detector response campaigns easier to reproduce, extend, and compare.

---

## High-Performance Computing

As part of the validation of the workflow, high-statistics simulations were executed on the PARAMGanga high-performance computing facility at IIT Roorkee. These runs included Cs-137 simulations with up to 10^8 events, demonstrating that the same workflow can be applied to both lightweight reference examples and larger campaign-scale simulations.

---

## Current Research Output

This work resulted in:

- An undergraduate thesis titled  
  *A Python-Assisted Geant4 Workflow for Automated Scintillation Detector Response Simulations*

- A public research software repository:  
  https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline

- A first-author conference paper submitted to IEEE Nuclear Science Symposium 2026:  
  *A Python-based Tool for Automated Geant4 Simulations of Scintillation Detectors*

---

## Broader Research Direction

My broader research direction is to develop computational tools, simulation workflows, and instrumentation-support software for experimental physics. I am interested in applying these skills to detector physics, radiation detection, optical simulations, astrophysical instrumentation, and high-performance scientific computing.
