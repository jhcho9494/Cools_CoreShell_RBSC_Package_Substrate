# Cools Core-Shell RBSC Package Substrate

## Do not mix silicon powder and carbon powder. Give every silicon particle its own carbon shell.

> **Cools replaces random powder mixing with particle-by-particle stoichiometric design.**

[한국어](README_KR.md) · [中文](README_ZH.md) · [Patent Portfolio](PATENT_PORTFOLIO.md)

---

## Executive proposition

The **Cools Core-Shell RBSC Package Substrate** is a patent-backed route to a large-area reaction-bonded silicon carbide (RBSC) flat substrate for semiconductor packaging.

Instead of mechanically mixing silicon powder and carbon powder, the process coats each silicon-containing particle with a measured carbon precursor, carbonizes the coating into a carbon shell, forms the resulting core-shell particles into a sheet, and reaction-sinters the sheet into a SiC-based plate.

```text
Silicon-containing particle
→ carbon-precursor coating
→ in-situ carbonization
→ silicon-core / carbon-shell particle
→ tape-cast green sheet
→ reaction sintering
→ low-warpage RBSC flat substrate
```

The approach targets a substrate that combines:

- silicon-like coefficient of thermal expansion;
- high thermal conductivity;
- high stiffness;
- low large-area warpage;
- a surface suitable for redistribution layers; and
- the use of recycled silicon as a high-value raw material.

---

## The powder-mixing problem

Conventional powder routes mix silicon-containing powder with carbon black, graphite or other carbon powder. The two powders behave very differently in a slurry:

- fine carbon has high surface area, is hydrophobic and strongly agglomerates;
- silicon particles commonly carry a hydrophilic surface oxide and have a different density;
- random mixing creates carbon-rich agglomerates and silicon-rich regions;
- local stoichiometric variation causes unreacted free carbon and free silicon;
- the Si + C → SiC reaction involves substantial volume shrinkage;
- spatially different shrinkage produces warpage and cracking.

For a packaging plate, this is not merely a material-strength problem. It directly affects whether the product can remain flat enough for redistribution layers, die attachment and fine-pitch interconnects.

Free carbon is particularly undesirable near the redistribution-layer side because it can form a porous, weak and oxidation-sensitive phase.

---

## Core-shell solution

Cools removes the statistical mixing problem at its source.

Each silicon-containing particle receives its own carbon supply. The carbon precursor is attached to the particle surface and carbonized in place. Carbon therefore does not need to find silicon through macroscopic powder mixing.

```text
Random two-powder mixture
= uncontrolled local segregation

Particle-specific carbon shell
= deterministic silicon-to-carbon geometry
```

The reaction distance is reduced to the particle scale, and the composition of the green sheet is frozen before sintering.

---

## Particle-level stoichiometry

For a silicon core of radius `r` and a carbon shell of thickness `t_c`, the carbon-to-silicon molar ratio is determined by core-shell geometry:

```text
n_C / n_Si
= (ρ_C · M_Si)/(ρ_Si · M_C)
  · {(1 + t_c/r)³ − 1}
```

Using representative densities for carbonized char and silicon, the patent describes a near-stoichiometric condition around:

```text
t_c / r ≈ 0.17
```

The ratio can be controlled by:

- classifying particles into a narrow size distribution and controlling coating thickness; or
- applying carbon precursor on a mass basis so that carbon loading follows each particle's silicon mass.

This converts an uncontrollable mixing fluctuation into a measurable geometric or mass-loading parameter.

---

## Deliberately carbon-lean design

The substrate is intentionally designed on the carbon-lean, silicon-rich side of stoichiometry.

The reason is practical:

- residual free carbon is a porous, weak and oxidation-sensitive defect phase;
- residual free silicon can fill pores and assist densification;
- package back-end processing generally remains far below the melting point of silicon;
- a small silicon-rich residual phase is therefore safer than a carbon-rich residual phase.

The carbon-lean design causes the carbon shell to be substantially consumed during reaction, leaving dispersed residual silicon rather than free carbon.

---

## Surface-oxide compensation

Silicon particles, especially recycled silicon powder, carry a native silicon-oxide layer. Carbon at the particle surface can consume this oxide through carbothermal reduction.

The process therefore compensates for the amount of carbon consumed by oxide reduction when setting the carbon-precursor loading.

This turns the oxide from a passive barrier into a quantified reaction demand.

---

## Recycled silicon as a packaging material feedstock

The silicon-containing particles may come from:

- wire-saw slurry recovery;
- ingot machining by-products; or
- other recovered silicon powder streams.

After cleaning and classification, the material is converted from a low-value waste stream into a high-stiffness, high-thermal-conductivity package substrate.

The platform therefore combines semiconductor packaging performance with materials circularity.

---

## Optional amine anchor layer

An amine-containing polymer, including ethoxylated polyethyleneimine, may be adsorbed onto the silicon-oxide surface before carbon-precursor coating.

The anchor layer can improve coating uniformity in an aqueous process by coupling the oxidized silicon surface to the carbon precursor.

This is compatible with Cools interface-engineering concepts developed for other substrates and metallization processes.

---

## Flat-sheet manufacturing flow

1. recover or prepare silicon-containing particles;
2. clean and optionally classify the particles;
3. optionally form an amine-functional anchor layer;
4. attach carbon precursor to each particle;
5. carbonize the coating in an inert atmosphere;
6. form the core-shell particles into a green sheet by tape casting or another sheet-forming process;
7. reaction-sinter above the silicon melting point;
8. flatten and finish the plate surface;
9. optionally form a dense dielectric skin; and
10. build redistribution layers and external terminals.

The carbon precursor can serve both as the carbon source and as part of the green-sheet binder system, reducing the need for a separate carbon powder and potentially simplifying slurry formulation.

---

## Resulting microstructure

The resulting substrate contains:

- a reaction-formed silicon-carbide matrix;
- dispersed residual free-silicon domains;
- substantially no free carbon; and
- a residual-silicon distribution corresponding to the former silicon-particle locations.

That spatial fingerprint distinguishes the core-shell reaction route from conventional external silicon infiltration or random silicon/carbon powder mixing.

---

## Packaging value proposition

| Existing substrate | Structural limitation | Core-shell RBSC proposition |
|---|---|---|
| Silicon interposer | expensive semiconductor processing | lower-cost large-area ceramic route |
| Glass substrate | very low thermal conductivity | high-conductivity SiC-based plate |
| Organic laminate | high CTE and low stiffness | inorganic low-CTE, high-stiffness plate |
| Conventional RBSC powder mixture | free carbon and differential shrinkage | particle-level stoichiometry and uniform shrinkage |

The intended role is a single inorganic plate that can carry redistribution layers, support multiple dies, spread heat and suppress large-area package warpage.

---

## Patent-described design targets

Representative targets and embodiments described in the patent include:

- coefficient of thermal expansion: approximately **3–5 ppm/K**;
- thermal conductivity: **100 W/m·K or higher**;
- warpage: **50 μm or less per 100 mm side length**;
- carbon-shell ratio `t_c/r`: approximately **0.10–0.175**, with carbon-lean preferred ranges;
- residual free silicon dispersed through the SiC matrix; and
- substantially no detectable free carbon.

These values are patent-described targets or examples unless separately identified as independently measured production data.

---

## Product forms

- polished RBSC flat substrate
- dielectric-skin-coated substrate
- redistribution-layer-ready panel
- interposer or package-substrate panel
- multi-die package base
- thermally conductive stiffener-substrate hybrid
- recycled-silicon-derived ceramic panel

---

## Relationship to the Cools RBSC platform

```text
Cools Core-Shell RBSC Package Substrate
= how to manufacture a flat, uniform RBSC packaging plate

Cools RBSC Backside Busbar Platform
= how to integrate backside power, ground and heat paths through an RBSC support
```

The core-shell flat substrate can serve as a material base for later redistribution, metallization, conductive through-portions and backside-busbar integration.

---

## Validation roadmap

- particle-size distribution and coating-thickness mapping;
- carbon loading and char-yield verification;
- oxide-content and carbothermal-consumption balance;
- free-carbon detection by Raman spectroscopy and microscopy;
- residual-silicon volume fraction and domain mapping;
- sintering shrinkage uniformity;
- panel warpage and total-thickness variation;
- thermal conductivity and coefficient of thermal expansion;
- flexural strength and thermal-cycle reliability;
- dielectric-skin adhesion;
- redistribution-layer adhesion and reliability; and
- comparison with glass, silicon and organic package substrates.

---

## Intellectual property notice

This repository provides a public overview of a patent-backed Cools material and manufacturing platform. It does not disclose every precursor formulation, coating condition, classification window, firing profile, impurity-control method or surface-finishing know-how required for commercialization.
