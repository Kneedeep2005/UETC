[![UETC Release](https://img.shields.io/badge/release-uetcref--v1.2-blue)](https://github.com/Kneedeep2005/UETC/releases/tag/uetcref-v1.2)
[![License: CC BY 4.0](https://img.shields.io/badge/license-CC%20BY%204.0-lightgrey)](https://creativecommons.org/licenses/by/4.0/)
[![Status](https://img.shields.io/badge/status-active%20development-blue)](#)


# Unified Electromagnetic Toroidal Cosmology (UETC)

Canonical technical reference for **Unified Electromagnetic Toroidal Cosmology (UETC)**, an independent, first-principles framework for interpreting structure and propagation across scales using toroidal electromagnetic geometry, density-layering, and observational reinterpretation.

- **Book (conceptual entry point):** *The Shape of Everything* (Unified Field Press)
- **Repository (technical backbone):** This GitHub repo, designed to answer “where is the paper?”, establish scope, authorship, and versioning, and provide a stable reference for technically literate readers.

## Project Philosophy

UETC is developed using a mechanism-first, observation-respecting approach.
The framework prioritizes structural clarity, explicit constraints, and falsifiability
over completeness or explanatory reach. Absence of a claim should not be interpreted
as omission, but as deliberate scope control.

## Status and Scope

This repository is a **working framework**, not a finalized theory.

Observational reinterpretation here means reanalyzing existing measurements under 
different structural and propagation assumptions, not rejecting observational data.
Where observational tensions exist (e.g., growth-time limits or large-scale electromagnetic structure),
they are documented explicitly and treated as motivation rather than proof.

### Intended audience
This repository is written for technically literate readers, including engineers, physicists, applied researchers, 
and advanced students familiar with classical electromagnetism, wave propagation, and observational astrophysics.

### What this repo is
- A structured technical reference that organizes UETC concepts, definitions, mechanisms, and observational implications.
- A public authorship and versioning anchor.
- A foundation for later formalization (e.g., arXiv / ResearchGate / journal submission), if warranted.

### What this repo is not
- **Not peer reviewed.**
- **Not a claim of experimental proof.**
- **Not a replacement** for standard cosmology, nor an adversarial critique.
- Not a complete mathematical formalism in its current phase; mathematical development is incremental and driven by structural clarity.

The emphasis here is on **structure, scaling, and mechanisms**, with clear boundaries on claims.

## Core Definition

UETC uses an effective propagation framework with the master energy functional:

$$
U_{\text{total}} =
\frac{1}{2}\varepsilon(u)E^2 +
\frac{B^2}{2\mu(u)} +
\frac{1}{2}\rho v^2 +
\Pi_{\text{aniso}} +
P_{\text{waves}}
$$

with vacuum-limit reference $u = 1$.

Where:
- $c_0$ is the vacuum-limit reference speed,
- $c(x)$ is an effective local propagation speed,
- $n(x)$ is an effective refractive index,
- $u(x)$ is a density or medium-coupled propagation parameter inferred observationally.

This parameter is an effective descriptor inferred from observation and does not imply modification of fundamental constants.

## Repository Map

This repository is organized to separate conceptual foundations, observational interpretation, and supporting context. Use the links below to navigate directly to the relevant materials.

### Core Documents

- **Overview (entry point)**  
  [`papers/UETC_Overview_v1.0.pdf`](papers/UETC_Overview_v1.0.pdf)  
  A compact, citable overview answering “where is the paper?”, defining scope, assumptions, and boundaries.

- **Core Framework**  
  [`papers/UETC_Core_Framework.md`](papers/UETC_Core_Framework.md)  
  Formal definitions, propagation parameterization, geometric structure, and falsifiability criteria.

- **Observational Implications**  
  [`papers/UETC_Observational_Implications.md`](papers/UETC_Observational_Implications.md)  
  Expected signatures, observational constraints, and competing interpretations.

### Figures

- [`figures/`](figures/)  
  Conceptual and observational schematics illustrating toroidal geometry, heliospheric structure, and large-scale electromagnetic organization.

### Appendices

- **Terminology**  
  [`appendices/terminology.md`](appendices/terminology.md)

- **Historical Context**  
  [`appendices/historical_context.md`](appendices/historical_context.md)

- **Comparison to Standard Models**  
  [`appendices/comparison_standard_models.md`](appendices/comparison_standard_models.md)

### Citations

- **Consolidated bibliography**  
  [`citations/references.bib`](citations/references.bib)

The canonical, citable snapshot of this repository is the release **`uetcref-v1.1`**.

### Observational Constraints

UETC includes observation-driven constraint analyses derived directly from published
astrophysical measurements. These entries are intended to remain model-agnostic,
revision-safe, and suitable as empirical anchors for future testing.

#### Black Holes

- **Growth-Time Constraints on Ultramassive Black Holes**  
  [`observational_constraints/black_holes/growth_time_constraints.md`](observational_constraints/black_holes/growth_time_constraints.md)

- **Normalized Electromagnetic Domain Scaling Framework**  
  [`observational_constraints/black_holes/em_domain_scaling.md`](observational_constraints/black_holes/em_domain_scaling.md)

- **AT2020afhd (Tidal Disruption Event)**  
  `observational_constraints/black_holes/AT2020afhd_precession_scaling.md`

- **TON 618 (Ultramassive Black Hole)**  
  An extreme-mass black hole treated as an upper-bound scaling and structural constraint, relevant for future comparative lensing and propagation studies without assuming exact geometric realization.

#### Galaxies

  * [Density-Gradient–Based Inference Scaler (Working Hypothesis)](observational_constraints/galaxies/density_gradient_inference_scaler.md)

  * [NGC 2403: Normalized-Radius Overlay on Conceptual u(x) (Working Hypothesis)](observational_constraints/galaxies/ngc2403_normalized_overlay.md)


## Relationship to *The Shape of Everything*

The book is the narrative, conceptual entry point.
This repo is the technical reference.

## How to Cite UETC

Gregory A. Beckman,  
*Unified Electromagnetic Toroidal Cosmology (UETC): Canonical Technical Reference*,  
GitHub repository, release **uetcref-v1.1**, 2026.  
https://github.com/Kneedeep2005/UETC

> Note: This repository uses `$...$` for inline math and `$$...$$` for display equations to ensure consistent rendering on GitHub and GitHub Pages.


# Changelog

## uetcref-v1.2 (2026-02-01)
- Added galactic-scale observational constraints category.
- Added density-gradient–based inference scaler (working hypothesis).
- Added illustrative normalized-radius galaxy overlay (NGC 2403).
- Updated observational-constraints indices to reflect partial population.

## uetcref-v1.1 (2026-01-28)
- Added DES / DECam observational constraint.
- Added geometric constraints section, including Clifford tori as reference toroidal geometry.
- Added TON 618 as an ultramassive black hole scaling constraint.
- Added black hole constraints README for structural clarity.
- Math rendering standardized using `$` / `$$`.

## uetcref-v1.0 (2026-01-27)
- Initial canonical public release
- Core framework established
- Observational constraints scaffolded
- Core framework established
- Observational constraints scaffolded
