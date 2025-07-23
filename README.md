# Focused Ultrasound Heating Simulation in COMSOL

This project simulates focused ultrasound-induced heating in a tissue phantom using COMSOL Multiphysics. The model investigates how ultrasound waves can generate localized heating in biological tissue and analyzes the influence of mesh resolution and coupling medium (water vs. air) on simulation outcomes.

## Report
The simulation setup and results are fully documented in the PDF report.  
**`Focused_Ultrasound_Heating_Report.pdf`**  
Contains:
- Model setup and geometry
- Acoustic field and temperature rise simulations
- Mesh refinement study
- Effect of air gap between transducer and tissue
- Comparative analysis of heating efficiency and safety

## Simulation Overview

This work is based on the **COMSOL Acoustics Module** and **Bioheat Transfer Module**, following a provided tutorial that simulates:
- **Part 1: Baseline Simulation**
  - Acoustic pressure and intensity fields
  - Heating and cooling curves at focal points
  - Contour and surface plots of temperature rise
  - Mesh size sensitivity study
- **Part 2: Model Modification**
  - Introduction of a 2 mm **air gap** between probe and tissue
  - Analysis of impact on acoustic transmission and heating
  - Repetition of mesh sensitivity analysis with the modified setup

## Software

- **COMSOL Multiphysics 6.2**
  - Modules used:
    - Acoustics Module
    - Heat Transfer Module
- Simulation run in **2D Axisymmetric** configuration

## References

- COMSOL Tutorial: *Focused Ultrasound Induced Heating in Tissue Phantom*
- J. Huang et al., *J. Acoust. Soc. Am.*, 2004
- Duck, F.A., *Physical Properties of Tissue*, Academic Press
- FDA and NCRP guidelines on ultrasound safety
