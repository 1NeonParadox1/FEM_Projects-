# FEM Projects

A growing portfolio of finite element analysis (FEA) and structural mechanics projects, focused on aerospace applications.

This repository documents a progression from fundamental finite element modelling to advanced structural analysis. Work will be added as concepts are learned, implemented, and verified.

> **Status:** Learning roadmap in progress. Planned topics are not claims of completed work; results will be added only after the corresponding analysis has been performed and checked.

## Roadmap

### 01 — Static Structural Analysis
- Prepare a parametric aerospace-style bracket model.
- Define material properties, loads, supports, and boundary conditions.
- Run a static analysis and inspect displacement, stress, and reactions.
- Document assumptions, units, and limitations.

### 02 — Mesh Convergence and Verification
- Compare coarse, medium, and fine meshes.
- Track relevant outputs while accounting for stress singularities.
- Check force equilibrium and compare simplified cases with hand calculations.
- Document numerical sensitivity and limitations.

### 03 — Fatigue Analysis
- Define a documented cyclic load case and stress ratio.
- Use traceable material S–N data.
- Estimate fatigue life and damage with an appropriate method.
- Investigate sensitivity to loading assumptions.

### 04 — Fracture Mechanics and Damage Tolerance
- Define a hypothetical crack geometry and assumptions.
- Calculate stress intensity using an appropriate geometry factor.
- Compare with suitable fracture-toughness data where valid.
- Explore crack-growth estimates only when reliable material constants and loading data are available.

### 05 — Nonlinear FEA
- Study geometric nonlinearity and large-displacement behaviour.
- Introduce material nonlinearity, such as elastoplasticity, using documented data.
- Explore nonlinear contact where relevant.
- Compare nonlinear and linear results and explain their differences.

### 06 — Structural Design and Optimization
- Compare design variables such as thickness, fillets, or reinforcement.
- Evaluate mass, stress, deformation, and durability measures.
- Document constraints and design trade-offs.
- Explore parameter-based optimization after model verification.

### 07 — Advanced FE Methods
Topics for later study:
- Implicit versus explicit solution methods.
- Substructuring and component-level modelling.
- Global-to-detailed FEM load transfer and boundary-condition continuity.
- Material damage and failure models.
- Nastran fundamentals and DMAP concepts.

These are future learning goals, not current proficiency claims. Nastran/DMAP is a specialised workflow that requires study beyond the ANSYS bracket model.

## Planned repository structure

```text
FEM_Projects-/
├── README.md
├── 01_Static_Structural_Analysis/
├── 02_Mesh_Convergence/
├── 03_Fatigue_Analysis/
├── 04_Fracture_Mechanics/
├── 05_Nonlinear_FEA/
├── 06_Structural_Optimization/
└── 07_Advanced_FE_Methods/
```

Each completed study can include:
- `README.md`: objective, theory, assumptions, setup, results, and limitations.
- `CAD/`: source geometry and suitable neutral exports.
- `ANSYS/`: manageable solver/project files, subject to file-size constraints.
- `Calculations/`: hand calculations or verification scripts.
- `Results/`: plots, screenshots, tables, and exported data.
- `References/`: material datasheets, standards, papers, and other sources.

Use only the subfolders needed for each study. Avoid committing temporary solver files, very large generated data, licensed software, or confidential information.

## Verification checklist

For every completed study:
1. State the objective, units, assumptions, and load case.
2. Identify material-data sources and applicability.
3. Document geometry idealisations, contacts, supports, and loads.
4. Check equilibrium and perform appropriate independent calculations.
5. Report mesh sensitivity and investigate singularities.
6. Separate solver output from engineering interpretation.
7. State limitations and avoid calling an unverified result validated.

## Progress tracker

- [ ] Static structural baseline
- [ ] Mesh convergence and verification
- [ ] Fatigue analysis
- [ ] Fracture mechanics / damage tolerance
- [ ] Nonlinear FEA
- [ ] Structural design comparison / optimization
- [ ] Advanced FE methods study

Update this checklist only when each milestone is completed. The goal is a transparent learning process with reproducible engineering work and increasing technical depth.
