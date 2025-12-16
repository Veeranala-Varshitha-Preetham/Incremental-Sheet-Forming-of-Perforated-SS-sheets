# Incremental Forming of Perforated SS304L Sheets

This repository contains a finite element study on **Single Point Incremental Sheet Forming (SPIF)** of perforated SS304L stainless steel sheets. The work investigates the influence of key process parameters on deformation behaviour, stress distribution, strain evolution, and sheet thinning, serving as a numerical foundation for experimental validation.

## Project Overview

Incremental Sheet Forming is a flexible, die-less forming process suitable for low-volume and custom manufacturing. Perforated sheets present additional challenges due to stress concentration around holes and non-uniform material flow. This project uses numerical simulation to understand these effects in detail.

The forming of a truncated cone geometry is simulated using **Abaqus CAE**, with the toolpath generated in **Autodesk Fusion 360** and CAD geometry created in **SolidWorks**.

## Objectives

- Study the deformation behaviour of perforated SS304L sheets during SPIF  
- Analyse the effect of **feed rate**, **step depth**, and **tool rotational speed**  
- Evaluate contact forces, Von Mises stress, strain paths, and thickness variation  
- Identify stable forming conditions for future experimental work  

## Methodology

- CAD modelling of truncated cone geometry in SolidWorks  
- Spiral toolpath generation in Autodesk Fusion 360  
- Finite element simulation in Abaqus CAE  
- Sheet modelled as a deformable shell (S4R elements)  
- Tool modelled as an analytically rigid body  
- Parametric study with independent variation of:
  - Feed rate (600, 800, 1000 mm/min)
  - Step depth (0.1, 0.2, 0.3 mm)
  - Tool speed (200, 300, 400 rpm)

## Key Results

- Perforations cause stress concentration near hole edges  
- Higher feed rates and step depths increase thinning and stress gradients  
- Moderate parameter values provide smoother deformation and lower stress  
- Simulation trends are consistent with reported literature  

## Tools and Software

- **Abaqus CAE** – Finite element simulation  
- **SolidWorks** – CAD modelling  
- **Autodesk Fusion 360** – Toolpath generation  
- **CNC-based SPIF framework** (for future experimental validation)

## Applications

- Medical implants (cranial and facial implants)  
- Custom sheet metal components  
- Low-volume and prototype manufacturing  
- Research on die-less forming of perforated sheets  

## Future Scope

- Experimental validation of simulation results  
- Study of different perforation patterns and hole sizes  
- Heat-assisted incremental forming  
- Damage and failure modelling near perforations  

## Author

**Veeranala Varshitha Preetham**  
B.Tech, Mechanical Engineering  
Indian Institute of Technology Bhubaneswar  

## Supervisor

**Dr. Gaurav Bartarya**  
School of Mechanical Sciences  
IIT Bhubaneswar  

## License

This project is intended for academic and research purposes.

