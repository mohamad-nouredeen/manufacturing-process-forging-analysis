# Manufacturing Process – Forging Analysis

Engineering study of a **C45 steel component** focused on the design and simulation of a hot-forging manufacturing process.

The project covers the complete workflow from the nominal CAD geometry to forged-part design, billet and die sizing, flash design, and 2D/3D process simulation.

## Project Overview

The objective of this project was to develop and evaluate a forging process for a mechanical component manufactured from C45 steel.

The work included:

- Nominal-part CAD modeling
- Material classification and geometry analysis
- Forged-part design
- Forging allowances and dimensional modifications
- Flash geometry design
- Billet dimensioning
- Die-block dimensioning
- Forging assembly preparation
- 2D QForm simulation
- 3D QForm simulation
- Stress and strain evaluation
- Workpiece and tool temperature analysis
- Process improvement through billet and lubrication optimization

## Engineering Workflow

### 1. Nominal Part

The initial component geometry was modeled and analyzed to determine its dimensions, mass, volume, and shape-complexity category.

### 2. Forged Part Design

The nominal geometry was modified according to forging design requirements, including:

- dimensional allowances
- draft angles
- fillets
- machining allowances
- geometry simplification for manufacturability

### 3. Flash Design

Flash thickness and flash-land dimensions were calculated and incorporated into the forged-part geometry.

### 4. Billet Dimensioning

The billet dimensions were calculated from the required forged-part volume and material properties.

The initial billet geometry was later modified after evaluating the simulation results.

### 5. Die Design

The required die-block dimensions were selected based on the forged geometry and manufacturing constraints.

### 6. QForm Simulation

Both **2D and 3D forging simulations** were performed to evaluate the forming process.

The simulations were used to investigate:

- material flow
- forging defects
- stress distribution
- strain distribution
- workpiece temperature
- die temperature
- flash formation

## Process Optimization

The initial simulation showed problems related to billet dimensions and flash formation.

The billet geometry was therefore modified by increasing its diameter and reducing its height before repeating the simulation.

The thermal behavior of the process was also investigated. A lubricant change was evaluated to improve the workpiece and tool temperature conditions.

## Software

- **SolidWorks** – CAD modeling and engineering drawings
- **QForm** – 2D and 3D forging-process simulation
- **Microsoft Excel** – engineering calculations and process dimensioning

## Repository Contents

The repository contains the engineering documentation, drawings, CAD-related material, and simulation results developed during the project.

```text
manufacturing-process-forging-analysis/
│
├── README.md
├── report/
├── drawings/
├── cad/
├── simulation/
│   ├── 2D-QForm/
│   └── 3D-QForm/
└── media/

