# Quantum ESPRESSO Band Structure and Density of States

## Overview
This project perform Density Functional Theory (DFT) calculations using Quantum ESPRESSO to compute Band Structures and Total Density of States (DOS). Electronic band structures and density of states (DOS) are calculated to understand determine whether a material is a metal, semiconductor, or insulator and conductive behavior of materials.

## Objectives
- Calculate electronic band structures
- Calculate total Density of States (DOS)
- Visualize and interpret the electronic properties of different materials

## Software and Tools
- Quantum ESPRESSO
- Linux
- Pseudopotentials
- xmgrace (Result plotting)

## Materials Studied
-
-
-

## Computational Workflow

```mermaid
flowchart TD
    A[Crystal Structure]
    B[SCF Calculation]
    C[NSCF Calculation]
    D[Band Structure Calculation]
    E[DOS Calculation]
    F[Band Structure Plot]
    G[DOS Plot]
    H[Electronic Structure Analysis]

    A --> B
    B --> C
    C --> D
    C --> E
    D --> F
    E --> G
    F --> H
    G --> H
```

## Results
- Combined Band Structure + DOS plot

  
