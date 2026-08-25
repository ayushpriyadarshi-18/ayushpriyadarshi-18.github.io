---
layout: default
title: Home
---

# Ayush Priyadarshi

I am an Integrated BS–MS Physics student at the Indian Institute of Technology Roorkee, working at the intersection of computational physics, scientific software development, detector simulations, and research instrumentation.

My current research develops angle-resolved annihilation-photon correlation factors for coincidence-summing corrections in high-efficiency NaI(Tl) detectors. I work across analytical modelling, Geant4 simulation, ROOT-based analysis, gamma-ray spectroscopy, and reproducible scientific software.

---

## Research Focus

### Annular-Detector Angular Factors

I led an annular NaI(Tl) detector study that establishes the angular factors required before applying our correction formalism to a more complex near-4π array. I corrected and extended an earlier unpublished derivation, performed the angle-resolved Geant4 analysis, developed the public reproducibility package, validated the calculation, prepared the figures, and wrote the complete manuscript.

The conference-paper manuscript is prepared for submission to the DAE Symposium on Nuclear Physics 2026. I am its first and corresponding author.

[View the reproducibility package](https://github.com/ayushpriyadarshi-18/angular-factors-calculator)

### Coincidence-Summing Corrections for β⁺ Emitters

I am working with Prof. Anil Kumar Gourishetty on geometry-dependent corrections for coincidence summing in Na-22, O-14, and Sc-44. I extended my thesis software to model custom decay sources, reconstruct a published eight-block reference detector, run high-statistics campaigns, and calculate the angular factors required for a near-4π soccer-ball NaI(Tl) detector array.

The implementation was checked by reproducing published reference factors within 2.3%, and the soccer-ball detector model was benchmarked against published experimental measurements for the physical TIFR array. A peer-reviewed journal manuscript is planned, with confirmed second authorship.

[Read about the research](research.md)

### Master's Thesis and Continuing Research Platform

My master's thesis developed a Python-assisted Geant4 workflow for automated scintillation detector response simulations. The workflow integrates:

- Geant4 C++ detector simulation backend
- Python-based macro generation
- Automated campaign execution
- ROOT-file validation
- Deposited-energy spectrum generation
- Peak-count and total-count extraction
- CSV/table generation
- Reproducible output organisation

This work forms the software basis of my master's thesis, a first-author conference paper accepted for poster presentation at IEEE Nuclear Science Symposium 2026, and my current detector-physics research.

---

## Featured Software

### Angular Factors Calculator

A tested Python package and command-line tool for calculating annular-detector annihilation-photon correlation factors from angle-resolved ROOT data or supplied mass coefficients.

[View repository](https://github.com/ayushpriyadarshi-18/angular-factors-calculator)

### Geant4 Detector Simulation Pipeline

A Python-assisted Geant4 simulation pipeline for automated scintillation detector response studies.

[View repository](https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline)

The project supports solid cylindrical, hollow annular, and near-4π soccer-ball detector geometries, along with scintillator materials such as NaI, LaBr3, CsI, BGO, GGAG, and PbWO4.

---

## Selected Projects

**Radio Telescope Control and Embedded Linux Support**  
Contributed to Raspberry Pi-based embedded Linux and hardware-control support for a student-led radio telescope project under the Physics and Astronomy Club, IIT Roorkee.

**WiFi IP Mouse**  
Built a Raspberry Pi-based WiFi IP mouse system during the Syntax Error Hackathon organised by SDS Labs, IIT Roorkee. Awarded First Prize.

**Raspberry Pi Home Server**  
Designed and maintain a Raspberry Pi-based home server for self-hosted services, home automation, file sharing, DNS filtering, reverse proxy services, and network gateway functionality.

---

## Publications

**A. Priyadarshi**, R. Chauhan, A. Srivastava, and G. Anil Kumar,<br>
“Angle-resolved annihilation-photon correlation factors for an annular NaI(Tl) detector,”<br>
conference-paper manuscript prepared for submission to the DAE Symposium on Nuclear Physics, 2026.<br>
Role: First and corresponding author.

**A. Priyadarshi**, G. A. Kumar, K. Madhan, and V. Ranga,  
“A Python-based Tool for Automated Geant4 Simulations of Scintillation Detectors,”  
accepted for poster presentation at IEEE Nuclear Science Symposium, 2026.  
Status: Accepted for poster presentation.

---

## Quick Links

- [Research](research.md)
- [Software](software.md)
- [Projects](projects.md)
- [Publications](publications.md)
- [Download CV](files/Ayush_Priyadarshi_CV.pdf)

---

## Contact

Email: [a_priyadarshi@ph.iitr.ac.in](mailto:a_priyadarshi@ph.iitr.ac.in)  
GitHub: [github.com/ayushpriyadarshi-18](https://github.com/ayushpriyadarshi-18)
