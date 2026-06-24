# Robotic Application Development — Phase 2 (Months 7–18)

This phase translates lab-validated MICP mixtures into controlled robotic fabrication processes for spraying and 3D printing.

---

## Objectives

- Develop robotic spraying protocols for uniform MICP solution distribution over trail surfaces
- Develop 3D printing workflows for trail surfacing and integrated furniture elements using MICP-stabilized local soil
- Validate consistency and reproducibility of robotic fabrication in lab conditions

---

## Equipment

**Primary robot:** KUKA KR60 industrial robotic arm (available at participating research labs)

**End effectors:**
- Custom spraying nozzle for MICP solution application
- Extrusion head for soil-based 3D printing

---

## Tasks

### 2.1 Robotic Arm Setup and Tool Development
- Mount and calibrate spraying and printing end effectors on the KUKA KR60
- Define operational parameters: flow rate, travel speed, layer height, nozzle pressure

### 2.2 Spraying Protocol Development
- Develop toolpaths for uniform coverage of flat and irregular trail surfaces
- Test multi-cycle spraying to achieve target calcite deposition depth and density
- Calibrate solution concentration and application rate based on Phase 1 lab results

### 2.3 3D Printing Protocol Development
- Adapt Phase 1 soil mixtures for extrudability (rheology tuning)
- Develop toolpaths for:
  - Trail surface panels (various textures and drainage profiles)
  - Integrated trail elements: seating, rest stops, shading structures
- Incorporate MICP treatment into the printing workflow (pre-treatment, post-treatment, or inline)

### 2.4 Lab Validation
- Print and spray test specimens
- Assess uniformity of MICP distribution across printed layers
- Mechanical testing of printed specimens (UCS, cracking) vs. hand-cast controls
- Document parameters for field-scale replication

---

## Success Criteria

- Uniform calcite distribution (≤ 15% coefficient of variation across specimen)
- Printed specimens reach strength and cracking targets set in Phase 1
- Full reproducibility across repeated fabrication runs

---

## Folder Contents

```
robotic/
├── toolpaths/        # Robot programs and motion paths
├── parameters/       # Material and process parameter logs
├── prints/           # Photos and scans of fabricated specimens
└── analysis/         # Uniformity and mechanical test results
```
