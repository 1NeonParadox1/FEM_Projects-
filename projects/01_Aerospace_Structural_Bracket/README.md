# Project 01 — Aerospace Structural Bracket

**Status:** Planned / in progress once modelling begins  
**Primary tools:** ANSYS Mechanical, SolidWorks; Python for calculations and plots where useful

## Objective

Develop a documented finite element workflow for an aerospace-style structural bracket. The project will start with a simple, verifiable static structural model and expand as additional structural-analysis concepts are learned.

This is a learning case study, not a certified aerospace design. Loads and geometry will be treated as representative assumptions unless supported by a documented source.

## Progression

### Phase 1 — Static structural baseline
- Create or prepare bracket geometry.
- Record dimensions, units, material properties, and their sources.
- Define loads, supports, contacts, and boundary conditions.
- Solve for displacement, stress, and reaction forces.
- Record modelling assumptions and limitations.

**Completion evidence:** model setup notes, result plots, force-balance check, and an initial interpretation.

### Phase 2 — Mesh convergence and verification
- Compare coarse, medium, and fine meshes.
- Track meaningful outputs and investigate stress concentrations or singularities.
- Compare a simplified result with an independent hand calculation where possible.

**Completion evidence:** mesh comparison table/plot and verification notes.

### Phase 3 — Fatigue
- Define a representative cyclic load case.
- Source suitable S–N data and document its applicability.
- Estimate fatigue life and damage using an appropriate method.
- Investigate sensitivity to loading assumptions.

**Completion evidence:** fatigue setup, material-data reference, results, and limitations.

### Phase 4 — Fracture mechanics and damage tolerance
- Define a hypothetical crack and a suitable geometry model.
- Calculate stress intensity and compare with appropriate fracture-toughness data where valid.
- Explore crack-growth estimation only if suitable material constants and loading data are available.

**Completion evidence:** documented analytical or FE assessment with stated assumptions.

### Phase 5 — Nonlinear FEA
- Investigate large-displacement/geometric nonlinearity.
- Add elastoplastic material behaviour or nonlinear contact when justified.
- Compare the nonlinear result with the linear baseline.

**Completion evidence:** solver settings, convergence notes, comparison, and interpretation.

### Phase 6 — Design comparison and optimization
- Compare selected geometric variants, such as thickness or fillet radius.
- Evaluate mass, stress, deformation, and durability measures.
- Define constraints and explain the trade-offs.

**Completion evidence:** comparison table and a justified design recommendation.

### Phase 7 — Advanced FE methods (later learning)
Study implicit versus explicit methods, substructuring, global-to-detailed load transfer, material damage/failure models, and Nastran/DMAP fundamentals. These require additional learning and may be documented as separate exercises rather than forced into the bracket model.

## Planned folder contents

- `CAD/` — native/neutral geometry files when available.
- `ANSYS/` — manageable project archives, solver inputs, or exported setup data.
- `Calculations/` — hand calculations and independent checks.
- `Results/` — plots, screenshots, tables, and exported numerical results.
- `References/` — material datasheets, standards, papers, and source notes.

Add files as the work is completed; these folders do not need to be populated in advance.

## Verification checklist

- [ ] Objective, units, assumptions, and loads documented
- [ ] Material properties have traceable sources
- [ ] Boundary conditions and load path reviewed
- [ ] Reaction forces checked against applied loads
- [ ] Mesh sensitivity investigated
- [ ] Independent calculation completed where practical
- [ ] Results interpreted with limitations clearly stated

## Current status

No numerical results are claimed in this README. Update the status and checklist as each phase is actually completed.
