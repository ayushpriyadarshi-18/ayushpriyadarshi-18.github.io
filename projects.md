---
layout: default
title: Projects
---

# Projects

This page collects selected research, instrumentation, embedded systems, and systems-engineering projects. The common theme across these projects is building practical software and hardware tools for technical and research-oriented problems.

---

## Research and Scientific Software

### Geant4 Detector Simulation Pipeline

**Type:** Research software  
**Role:** Developer and maintainer  
**Repository:** https://github.com/ayushpriyadarshi-18/geant4-detector-simulation-pipeline  

A Python-assisted Geant4 workflow for automated scintillation detector response simulations. The project integrates a Geant4 C++ backend with Python automation for macro generation, campaign execution, ROOT-file validation, spectrum generation, peak-count extraction, total-count extraction, plotting, and result organisation.

The pipeline supports:

- Monoenergetic gamma simulations
- Radioactive-decay simulations
- Solid cylindrical detector geometry
- Hollow annular detector geometry
- Near-4π soccer-ball-style detector geometry
- Scintillator materials including NaI, LaBr3, CsI, BGO, GGAG, and PbWO4
- ROOT-based deposited-energy analysis using `EdepCrystal_keV`

This project forms the basis of my undergraduate thesis and my first-author IEEE Nuclear Science Symposium 2026 submission.

---

## Research Instrumentation

### Radio Telescope Control and Embedded Linux Support

**Organisation:** Physics and Astronomy Club, IIT Roorkee  
**Role:** Assisting contributor  
**Type:** Student-led research instrumentation project  

Contributed to Raspberry Pi-based embedded Linux and hardware-control support for a student-led radio telescope project under the Physics and Astronomy Club, IIT Roorkee.

My contributions included:

- Assisting in the development of a custom Raspberry Pi image for the telescope system
- Modifying Raspberry Pi boot configuration for reliable startup under lower-voltage portable power conditions
- Enabling networking over the power/data port for a single-cable portable Linux setup
- Building support for an initially unsupported Wi-Fi module
- Assisting with hardware-control integration for telescope operation

This project gave me experience with embedded Linux, Raspberry Pi configuration, networking, hardware interfacing, and scientific instrumentation.

---

## Systems Engineering

### Raspberry Pi Home Server and Network Gateway

**Type:** Independent systems engineering project  
**Platform:** Raspberry Pi, Linux, Docker  

Designed and maintain a Raspberry Pi-based home server for self-hosted services, network management, and automation.

The system includes:

- Docker-based self-hosted services
- Jellyfin media server
- Home Assistant automation
- Samba/NFS file sharing
- Reverse proxy services
- DNS filtering and ad-blocking
- Network gateway functionality

This project helped me build practical experience in Linux system administration, networking, Docker, service deployment, and home automation.

---

## Hackathon Project

### WiFi IP Mouse

**Award:** First Prize, Syntax Error Hackathon, SDS Labs, IIT Roorkee  
**Year:** 2022  
**Repository:** https://github.com/ayushpriyadarshi-18/MyPi.git  

Built a WiFi-based IP mouse system using Raspberry Pi during the Syntax Error Hackathon organised by SDS Labs, IIT Roorkee.

The project involved:

- Raspberry Pi-based wireless mouse/control functionality
- Network-based communication between the Raspberry Pi and host device
- Rapid prototyping under hackathon time constraints
- Embedded systems and networking-based problem solving

---

## Embedded Systems

### IoT Smart Switch with Alexa Integration

**Type:** Independent embedded systems project  
**Year:** 2020  
**Platform:** ESP8266, relays, Wi-Fi, Alexa-compatible control  

Built a Wi-Fi-enabled smart switch from scratch using an ESP8266 microcontroller and relay-based switching to control household lights and fans through Alexa voice commands.

The project involved:

- Relay-based switching circuit design
- ESP8266 programming
- Wi-Fi-based device control
- Alexa-compatible smart-home integration
- Practical testing with lights and fan control

---

## Early Programming Project

### Python + MySQL Travel Agency Management System

**Type:** Class XII Computer Science project  
**Year:** 2021  
**Technologies:** Python, MySQL  

Developed a terminal-based travel agency management system using Python and MySQL. The project included database design, basic authentication, reporting features, and command-line interaction.
