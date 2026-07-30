# Patent Portfolio — Cools Core-Shell RBSC Package Substrate

## Portfolio thesis

This repository is built around one foundational patent family:

> **Replace random mixing of silicon powder and carbon powder with a particle-specific carbon shell whose geometry and mass loading determine the silicon-to-carbon reaction ratio.**

The protected value chain spans raw-material preparation, particle coating, green-sheet formation, reaction sintering, resulting microstructure and use as a semiconductor package substrate.

---

## P01 — Core-shell RBSC flat substrate and manufacturing method

**Patent axis**  
Reaction-bonded silicon carbide flat substrate using carbon-precursor-coated silicon-containing particles, and method of manufacturing the same.

### A. Feedstock scope

The silicon-containing particles may include:

- recycled silicon powder;
- wire-saw slurry recovery material;
- silicon-ingot machining by-products; and
- other crystalline or polycrystalline silicon-containing particles.

Cleaning, impurity removal and particle-size classification may be applied before coating.

### B. Particle-specific carbon supply

The patent protects attaching a carbon precursor directly to the surface of each silicon-containing particle and carbonizing it in place.

Representative precursor classes include:

- phenolic resin;
- sucrose;
- furfuryl alcohol;
- polyvinyl alcohol; and
- polyacrylonitrile.

This eliminates the need to depend on random distribution of a separate carbon powder.

### C. Core-shell geometry

A silicon core is surrounded by a carbonized shell. The carbon-to-silicon molar ratio is defined by particle geometry:

```text
n_C / n_Si
= (ρ_C · M_Si)/(ρ_Si · M_C)
  · {(1 + t_c/r)³ − 1}
```

The patent describes a near-stoichiometric thickness ratio around:

```text
t_c / r ≈ 0.17
```

and claims carbon-shell ratios in a range including approximately `0.10–0.175`.

### D. Particle-size and mass-basis control

Two control routes are protected:

1. classify particles into a narrow size distribution so that a controlled coating thickness produces a controlled `t_c/r`; and
2. attach carbon precursor on a particle-mass basis so that carbon loading follows silicon mass and remains less sensitive to particle size.

A representative classification criterion includes `D90/D10 ≤ 3`.

### E. Carbon-lean composition

The overall composition is intentionally set below a carbon-to-silicon molar ratio of one.

The protected consequence is:

- carbon is substantially consumed;
- free carbon is substantially absent;
- residual free silicon remains as a dispersed phase; and
- local variation moves toward a silicon-rich, rather than carbon-rich, residual condition.

### F. Native-oxide compensation

The patent accounts for carbon consumed by carbothermal reduction of the silicon-particle surface oxide.

Carbon-precursor loading is adjusted to compensate for this consumption so that the effective carbon available for SiC formation remains within the intended range.

### G. Optional amine anchor layer

An amine-functional polymer may be adsorbed onto the particle surface before carbon-precursor attachment.

Ethoxylated polyethyleneimine is identified as one embodiment. The anchor improves aqueous coating uniformity on the oxidized silicon surface.

### H. Green-sheet formation

The core-shell particles are formed into a flat green sheet, including by tape casting.

The carbon precursor may also perform a binder function, allowing reduction or elimination of separate carbon powder, dispersant and binder systems in some embodiments.

### I. Reaction sintering

The green sheet is heated above the silicon melting point so that silicon in the core reacts with carbon in the shell to form a silicon-carbide matrix.

Because composition is distributed particle by particle before sheet formation, shrinkage occurs more uniformly across the plate, suppressing differential shrinkage, warpage and cracking.

### J. Resulting microstructure

The product claims include:

- a reaction-formed silicon-carbide matrix;
- dispersed residual free silicon;
- substantial absence of free carbon;
- residual-silicon domains spatially corresponding to former silicon-particle positions;
- a surface capable of receiving an insulating layer or redistribution layer; and
- an opposite surface capable of receiving external terminals.

The residual-domain distribution is a potential structural fingerprint of the core-shell route.

### K. Package-substrate use

The patent covers the flat substrate as a packaging member and structures further including:

- a flattened surface;
- a dense dielectric skin;
- redistribution layers;
- microbump-connected semiconductor dies; and
- external connection terminals.

It is positioned as a possible replacement for silicon interposers, glass substrates and organic laminate substrates in applications requiring high thermal conductivity, low CTE and high stiffness.

---

## Patent-described quantitative embodiments

Representative patent-described values include:

| Parameter | Described target or example |
|---|---:|
| Carbon-shell thickness ratio `t_c/r` | about 0.10–0.175 |
| Particle-size spread | D90/D10 of 3 or less in one route |
| Carbonization temperature | about 800–1100°C |
| Reaction-sintering temperature | above Si melting point; example about 1450–1600°C |
| Substrate CTE | about 3–5 ppm/K |
| Thermal conductivity | 100 W/m·K or higher |
| Warpage | 50 μm or less per 100 mm side length |
| Residual phase | dispersed free silicon |
| Undesired phase | substantially no free carbon |

These values are patent-described targets, ranges or examples unless separately identified as independently verified production measurements.

---

## Claim-layer map

```text
Raw material
├─ silicon-containing particles
└─ recycled-silicon sources

Particle engineering
├─ carbon-precursor coating
├─ in-situ carbonization
├─ size classification
├─ mass-basis loading
├─ oxide-consumption compensation
└─ optional amine anchor

Panel manufacturing
├─ core-shell particle slurry
├─ tape-cast green sheet
├─ reaction sintering
├─ uniform shrinkage
└─ surface flattening / dielectric skin

Product structure
├─ SiC matrix
├─ dispersed residual silicon
├─ substantial absence of free carbon
├─ RDL-ready flat surface
└─ package substrate / interposer / multi-die base
```

---

## Commercial protection layers

The patent family is structured to reach multiple commercial forms:

- coated silicon core-shell powder;
- classified and coated particle feedstock;
- green sheet or green panel;
- sintered RBSC flat substrate;
- polished RDL-ready panel;
- dielectric-skin-coated panel;
- redistribution-layer-integrated substrate; and
- completed multi-die package structure.

---

## Measurable differentiation

Potential evidence and verification routes include:

- cross-sectional coating-thickness measurement;
- carbon loading per silicon mass;
- particle-size distribution;
- Raman detection of free carbon;
- microscopy and elemental mapping of residual silicon;
- comparison of residual-phase morphology with infiltrated RBSC;
- shrinkage-field mapping across a panel;
- warpage and total-thickness variation;
- CTE and thermal conductivity;
- dielectric-skin and RDL adhesion; and
- thermal-cycle and moisture reliability.

---

## Relationship to other Cools intellectual-property platforms

```text
Core-Shell RBSC Package Substrate
= flat-substrate material and manufacturing platform

RBSC Backside Busbar Platform
= backside electrical, ground and thermal routing infrastructure

Joint-Selective Bonding Platform
= local bonding, annealing, reflow and rapid-solidification process platform
```

The three platforms can be combined but protect distinct technical layers.

---

## Disclosure boundary

This document maps the patent architecture. It does not disclose all precursor chemistry, particle-cleaning conditions, coating equipment settings, carbonization atmosphere control, firing fixtures, impurity specifications, surface-finishing sequences or redistribution-layer integration know-how.
