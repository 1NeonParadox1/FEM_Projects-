# FEM Projects

A growing portfolio of finite element analysis (FEA) projects, primarily focused on structural mechanics and aerospace applications.

This repository is designed to hold **multiple independent projects**. Each project gets its own folder, report, files, and progress tracker. Projects will progress from foundational FEA to more advanced methods as they are learned and verified.

> **Current focus:** Aerospace Structural Bracket — static analysis first, followed by mesh verification, fatigue, fracture mechanics, nonlinear FEA, and optimization. Future projects can be added alongside it.

## Repository layout

```text
FEM_Projects-/
├── README.md
├── projects/
│   └── 01_Aerospace_Structural_Bracket/
│       ├── README.md
│       ├── CAD/
│       ├── ANSYS/
│       ├── Calculations/
│       ├── Results/
│       └── References/
├── resources/       # Shared notes, equations, and learning references (as needed)
└── templates/       # Reusable report/checklist templates (as needed)
```

## Current project

### [01 — Aerospace Structural Bracket](projects/01_Aerospace_Structural_Bracket/README.md)

A progressive structural-analysis case study of an aerospace-style bracket. It begins with a basic static structural model in ANSYS Mechanical and grows toward fatigue, fracture mechanics, nonlinear analysis, and design optimization.

## Planned progression

1. **Static structural analysis** — geometry, material properties, loads, supports, stress, and deformation.
2. **Verification and mesh convergence** — mesh sensitivity, equilibrium checks, and hand-calculation comparisons.
3. **Fatigue** — cyclic loading and S–N-based life estimation using documented material data.
4. **Fracture mechanics** — crack sensitivity, stress intensity, and damage-tolerance fundamentals.
5. **Nonlinear FEA** — geometric/material nonlinearity and contact where appropriate.
6. **Design comparison and optimization** — evaluate mass and structural performance across variants.
7. **Advanced FE methods** — learn implicit/explicit methods, substructuring, global-to-detailed load transfer, and Nastran/DMAP fundamentals.

These are planned learning stages, not claims that the analyses or tools have already been mastered. The project documentation will distinguish completed work from future plans.

## Documentation principles

Every project should explain its objective, assumptions, units, material-data sources, model setup, verification, results, and limitations. Large solver files may be stored separately when necessary; do not commit licensed software or confidential data.

New projects should receive their own numbered folder under `projects/`, with a dedicated README describing the question, method, status, and deliverables.
