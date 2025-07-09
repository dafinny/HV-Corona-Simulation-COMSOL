
# ⚡ High Voltage Corona Discharge Simulation using COMSOL Multiphysics

This project investigates the impact of electrode geometry on electric field intensification and corona inception in high-voltage systems using COMSOL Multiphysics. The goal is to evaluate which configurations are more prone to corona discharge, thereby offering insights for insulation design and HV equipment optimization.

## 🧩 Problem Statement

Corona discharge is a significant concern in high-voltage power systems, often triggered by localized field intensification near sharp geometries. This can lead to energy loss, audible noise, and long-term insulation degradation. The project aims to simulate various electrode profiles and determine:

- Maximum electric field strength
- Distribution of equipotential lines
- Corona inception voltage for each geometry

## 🛠️ Simulation Setup

- **Software Used**: COMSOL Multiphysics
- **Module**: Electrostatics (AC/DC Module)
- **Domain**: 2D Geometry
- **Boundary Conditions**: Electrode at high voltage, surrounding boundary at 0 V (grounded)
- **Dielectric Medium**: Air

### ✏️ Electrode Geometries Simulated

1. Flat Electrode with Flat Surrounding Edge  
2. Flat Electrode with Needle-Tip Surrounding  
3. Flat Electrode with Protruded Grounded Projection  
4. Flat Electrode with Angled Surrounding Edge

## 📊 Key Findings

| Geometry Type | Max Electric Field (V/m) | Corona Risk | Observation |
|---------------|--------------------------|-------------|-------------|
| Flat          | ~2.5 MV/m                | Low         | Uniform field |
| Needle        | ~13.3 MV/m               | Very High   | Sharp tip intensifies field |
| Projection    | ~5.9 MV/m                | Medium      | Field curves around projection |
| Angled Edge   | ~7.4 MV/m                | High        | Sharp corner increases field |

- **Needle geometries** showed the highest field intensity and the lowest corona inception threshold.
- **Flat configurations** offered the safest profile in terms of insulation margin.

## 📄 Report

📥 Download the full report here:  
[Comsol_simulation.pdf](./Comsol%20simulation.pdf)


The PDF includes:
- Geometry schematics  
- Simulation plots (equipotentials, field stress)  
- Calculated results and inferred thresholds  
- Design insights and engineering takeaways  

## ✅ Skills Demonstrated

- High-voltage insulation modeling  
- Electric field analysis in dielectrics  
- COMSOL setup for 2D electrostatics  
- Visualization of field distributions  
- Critical evaluation of design trade-offs

## 📬 Contact

If you're working on power system insulation, high-voltage design, or multiphysics simulations, feel free to connect or collaborate:

**Dafinny Thanigaivel**  
MEng – Electrical & Computer Engineering, University of Waterloo  
[LinkedIn]([https://www.linkedin.com/in/dafinny-thanigaivel/](https://www.linkedin.com/in/dafinny-thanigaivel-298572245/)) • [GitHub](https://github.com/dafinny)
