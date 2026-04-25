# Overall Drag Reduction of a 750F Race Car

## Overview

This project aimed to reduce overall drag of a 750F car by 10%. Simulations were performed using Siemens Star-CCM+.

## Objectives

* Complete full baseline analysis of 750F car including both quantative and qualitative data.
* Modify the exsisting model to reduce drag by 10% while maintaining lift characteristics. Creating 3-5 design iterations.
* Produce a final low-drag aero package that complies with 750F regulations.

## Methodology

* 3D CAD model of 750F car was imported into Star-CCM and extensively repaired.
* An open road test area was created with a moving floor section.
* A mesh convergence study was carried out to detemrine the most efficient mesh refinement.
* Steady-state simulations were run at a calculated average race speed of 39m/s.
* New field functions created to display pressure coefficient in the X and Z directions.

## Key Areas of Investigation

* Cockpit area
* Rear bodywork
* Wheel wake management
* Diffuser

## Results

* Identified main drag areas on the car.
* Changes were made to reduce drag in the cockpit and rear body areas, totalling a 10% reduction
* The diffuser was modified to improve efficiency and reduce tyre wake ingestion, improving negative lift characteristics with no drag penalty.

## Baseline Analysis
Baseline 750F race car
<img width="846" height="407" alt="image" src="https://github.com/user-attachments/assets/b955c174-c118-4310-aea2-d97455541834" />
Front and rear CPx distribution - Areas in red highlight the main drag areas
<img width="915" height="354" alt="image" src="https://github.com/user-attachments/assets/26ff2bbd-5fed-462f-a05d-56a4b1a3fd3b" />
Isosurface - Highlights the wake caused by the roll hoop, rear body, and the effect it has on the diffuser
<img width="449" height="290" alt="image" src="https://github.com/user-attachments/assets/12550c76-c87a-4be1-91c9-c73ded8b8d35" />



![Velocity Streamlines](images/streamlines.png)

## Tools & Skills Demonstrated

* CFD simulation (Star-CCM+)
* Aerodynamic analysis
* Mesh generation and refinement
* Post-processing and flow visualisation

## Key Learning

This project developed my ability to:

* Interpret complex flow structures
* Balance simulation accuracy with computational cost
* Translate CFD results into practical design improvements

## Files

* Full report: `report.pdf`
* Simulation outputs: `/images`
