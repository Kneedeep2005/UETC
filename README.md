[![UETC Release](https://img.shields.io/badge/release-uetcref--v1.0-blue)](https://github.com/Kneedeep2005/UETC/releases/tag/uetcref-v1.0)
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

The canonical, citable snapshot of this repository is the release **`uetcref-v1.0`**.

### Observational Constraints

UETC includes observation-driven constraint analyses derived directly from published
astrophysical measurements. These entries are intended to remain model-agnostic,
revision-safe, and suitable as empirical anchors for future testing.

#### Black Holes

- **Growth-Time Constraints on Ultramassive Black Holes**  
  [`observational_constraints/black_holes/growth_time_constraints.md`](observational_constraints/black_holes/growth_time_constraints.md)  
  Documents the well-known Eddington-limited growth-time tension for ultramassive
  black holes and motivates investigation of alternative physical regimes without
  asserting a resolution.

- **Normalized Electromagnetic Domain Scaling Framework**  
  [`observational_constraints/black_holes/em_domain_scaling.md`](observational_constraints/black_holes/em_domain_scaling.md)  
  Introduces a dimensionless, GR-baselined framework for comparing electromagnetic
  structure across black hole systems spanning many orders of magnitude in mass.

- **AT2020afhd (Tidal Disruption Event)**  
  Disk–jet co-precession with a measured period of 19.6 ± 1.5 days has been used to
  extract a characteristic coherent-precession radius in gravitational units.
  The analysis follows standard Lense–Thirring precession assumptions as presented
  in the literature and does not introduce additional theoretical claims.

  Location:  
  `observational_constraints/black_holes/AT2020afhd_precession_scaling.md`

  Reference:  
  *Science Advances* (2025), “Detection of disk–jet coprecession in a tidal disruption event”

## Documents

### `papers/UETC_Overview_v1.0.md`
A compact, citable overview intended for readers asking:
- “Where is the paper?”
- “What exactly is UETC claiming?”
- “What are the definitions and boundaries?”

### `papers/UETC_Core_Framework.md`
The technical nucleus:
- Definitions and invariants (including \(u(x)\))
- Toroidal scaling logic
- Mechanism-first explanations
- Minimal math where it clarifies, without attempting full formal closure

### `papers/UETC_Observational_Implications.md`
A structured reinterpretation layer:
- What UETC would predict qualitatively/structurally
- What would count as supportive vs non-supportive observations
- Known limitations and constraints

## Relationship to *The Shape of Everything*

The book is the narrative, conceptual entry point.
This repo is the technical reference.

**Policy for book material**
- This repo will **reference** the book for extended discussion and narrative presentation.
- This repo will **excerpt only what is necessary** for definitions, core equations/relations, and figure context.
- If a section is primarily explanatory prose from the book, we will link to it by chapter/section reference rather than reproducing it here.

## Versioning and Change Control

The Unified Electromagnetic Toroidal Cosmology (UETC) repository follows an explicit versioning and change-control policy to preserve internal consistency and prevent untracked conceptual drift.

Version numbers reflect **structural significance**, not publication status.

### Version Numbering

UETC uses a semantic-style versioning scheme:

- **Major versions (X.0)**  
  Reserved for changes that modify core definitions, foundational assumptions, or primary framework parameters (for example, redefining the propagation parameter \(u(x)\) or altering the role of toroidal geometry).

- **Minor versions (X.Y)**  
  Used for additions or clarifications that extend the framework without altering its foundational structure.  
  Examples include:
  - adding new observational constraint categories,
  - introducing a canonical energy functional,
  - expanding explanatory text or figures.

- **Patch revisions (X.Y.Z)**  
  Used for non-structural changes such as:
  - typographical corrections,
  - formatting improvements,
  - citation updates,
  - wording clarifications that do not affect meaning.

### Canonical Content

Material designated as *canonical* (for example, core definitions, primary parameters, or master equations) may be expanded or clarified in later versions, but is not redefined without a corresponding major version change.

### Scope Discipline

The GitHub repository is intended to document the **framework structure and constraints**, not to serve as a complete mathematical derivation or finalized theory.

Speculative extensions, open questions, and future research directions are tracked separately and do not modify the current canonical framework unless explicitly promoted via a versioned update.

### Change Transparency

All substantive changes should be reflected in:
- the repository version number,
- commit history,
- and, where appropriate, section-level revision notes.

This policy exists to ensure that UETC remains internally consistent, reviewable, and traceable over time.

### 1) Repository document versions
- `UETC_Overview_vX.Y.pdf` increments when the PDF is revised.
- `UETC_Core_Framework.md` and other Markdown files include a version header at top:
  - `Version: X.Y`
  - `Last updated: YYYY-MM-DD`
  - `Change summary: ...`

### 2) Git tags for public milestones
Use annotated tags for stable reference points:
- `uetcref-v1.0` (first public canonical release)
- `uetcref-v1.1`, etc.

Recommended convention:
- Increment **minor** (`1.0 → 1.1`) for clarified text, reorganizations, added figures.
- Increment **major** (`1.x → 2.0`) only if core definitions change (e.g., redefining \(u(x)\), replacing core mechanism statements, or restructuring the foundation).

## Roadmap (High-Level)

Planned next steps include:
- stabilization of the core framework documents,
- expansion of the observational implications section,
- refinement of figures for cross-scale consistency,
- preparation of a standalone technical preprint if warranted.
- expansion of observation-driven scaling analyses across astrophysical systems
- **Future Work (deferred, non-canonical)**  
  [`papers/UETC_Future_Work.md`](papers/UETC_Future_Work.md)


## How to Engage

Constructive engagement is welcome in the form of:
- clarification questions tied to specific definitions,
- proposed observational tests or falsification criteria,
- identification of internal inconsistencies or ambiguous language.

General debate, rhetorical critique, or speculative extensions are out of scope for this repository phase.

## How to Cite UETC

Until a formal peer-reviewed paper is submitted, UETC should be cited using the canonical repository release and the overview document.

### Canonical Citation

Gregory A. Beckman,  
*Unified Electromagnetic Toroidal Cosmology (UETC): Canonical Technical Reference*,  
GitHub repository, release **uetcref-v1.0**, 2026.  
https://github.com/Kneedeep2005/UETC

### Citing the Overview Document

When referring specifically to the framework summary or definitions presented in the overview, cite:

Beckman, G. A.,  
*Unified Electromagnetic Toroidal Cosmology: Overview v1.0*,  
Unified Field Press, 2026.  
Available at: `papers/UETC_Overview_v1.0.pdf`

### Versioning Guidance

- Always cite the **release tag** (`uetcref-v1.0`, `uetcref-v1.1`, etc.), not individual commits.
- If quoting or relying on specific definitions, equations, or figures, reference the **Overview version** used.
- Subsequent releases may refine language, structure, or figures; citations should reflect the version consulted.

### BibTeX and Machine-Readable Citations

- A BibTeX entry template is maintained at:  
  `citations/references.bib`
- A machine-readable citation file (`CITATION.cff`) is provided at the repository root to support GitHub, Zotero, and other reference managers.

### Citation Scope Notes

- This repository represents a **working research framework** and is **not peer reviewed**.
- Citation indicates reference to definitions, structural interpretation, or organizational concepts, not endorsement or experimental validation.


## License

**Recommended:** `CC BY 4.0` (Creative Commons Attribution 4.0)
- Encourages discussion and reuse with attribution.
- Appropriate for written technical documentation and figures.
- Keeps the work openly citable while preserving authorship credit.

(If later you want stronger controls on commercial reuse, switch to `CC BY-NC 4.0`, but that can reduce academic/engineering reuse.)

## Author

**Gregory A. Beckman**  
Independent researcher  
Retired U.S. Coast Guard (Operations, SAR, communications)  
Publisher: Unified Field Press

## Author Context

The UETC framework is developed from a first-principles and observational perspective, informed by professional experience in operations, systems reliability, and communications rather than by formal academic appointment.

This work is presented as an independent research framework intended for technical scrutiny. Evaluation should be based on internal consistency, clarity of definitions, and correspondence with observation, not on author affiliation.


## Contact / Notes

If you are evaluating UETC critically, the most useful contributions in this phase are:
- identifying ambiguous definitions,
- proposing clearer observational tests,
- pointing out internal inconsistencies,
- suggesting better organization and citations.

Discussion should focus on technical clarity and falsifiable structure, not rhetoric.

> Note: GitHub Markdown does not render display equations; canonical equations are rendered inline or in the PDF overview.


# Changelog

## uetcref-v1.0 (2026-01-27)
- Initial canonical public release
- Core framework established
- Observational constraints scaffolded

