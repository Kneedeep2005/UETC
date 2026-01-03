# Unified Electromagnetic Toroidal Cosmology (UETC)

Canonical technical reference for **Unified Electromagnetic Toroidal Cosmology (UETC)**, an independent, first-principles framework for interpreting structure and propagation across scales using toroidal electromagnetic geometry, density-layering, and observational reinterpretation.

- **Book (conceptual entry point):** *The Shape of Everything* (Unified Field Press)
- **Repository (technical backbone):** This GitHub repo, designed to answer “where is the paper?”, establish scope, authorship, and versioning, and provide a stable reference for technically literate readers.

## Status and Scope

This repository is a **working framework**, not a finalized theory.

Observational reinterpretation here means reanalyzing existing measurements under different structural and propagation assumptions, not rejecting observational data.


### Intended audience
This repository is written for technically literate readers, including engineers, physicists, applied researchers, and advanced students familiar with classical electromagnetism, wave propagation, and observational astrophysics.

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

UETC uses an effective propagation framework with:

\[
u(x) = \frac{c_0^2}{c(x)^2} = n(x)^2,\quad \text{vacuum limit: } u=1
\]

Where:
- \( c_0 \) is the vacuum-limit reference speed,
- \( c(x) \) is an effective local propagation speed,
- \( n(x) \) is an effective refractive index,
- \( u(x) \) is a density/medium-coupled propagation parameter inferred observationally.

## Repository Map


UETC/
├── README.md
├── papers/
│ ├── UETC_Overview_v1.0.pdf
│ ├── UETC_Core_Framework.md
│ └── UETC_Observational_Implications.md
├── figures/
│ ├── toroidal_scales.png
│ ├── heliosphere_structure.png
│ └── galaxy_em_flows.png
├── appendices/
│ ├── terminology.md
│ ├── historical_context.md
│ └── comparison_standard_models.md
├── citations/
│ └── references.bib
└── LICENSE


## Documents

### `papers/UETC_Overview_v1.0.pdf`
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

This repo uses two related version tracks:

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

## How to Engage

Constructive engagement is welcome in the form of:
- clarification questions tied to specific definitions,
- proposed observational tests or falsification criteria,
- identification of internal inconsistencies or ambiguous language.

General debate, rhetorical critique, or speculative extensions are out of scope for this repository phase.

## How to Cite

Until a formal paper is submitted, cite the repository release and the overview PDF:

- **PDF:** `papers/UETC_Overview_v1.0.pdf`
- **Repo release/tag:** `uetcref-v1.0`

A BibTeX entry template will be maintained in:
- `citations/references.bib`

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

## Contact / Notes

If you are evaluating UETC critically, the most useful contributions in this phase are:
- identifying ambiguous definitions,
- proposing clearer observational tests,
- pointing out internal inconsistencies,
- suggesting better organization and citations.

Discussion should focus on technical clarity and falsifiable structure, not rhetoric.
