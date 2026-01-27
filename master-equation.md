---
layout: default
title: Master Equation
permalink: /master-equation/
---

# Canonical UETC Master Energy Functional

This page presents the canonical master energy functional used throughout Unified Electromagnetic Toroidal Cosmology (UETC).

It is provided as a public reference point only. Detailed scope, constraints, definitions, and falsifiability criteria are maintained in the GitHub repository’s core documents.

## Master Energy Functional (Canonical)

$$
U_{\text{total}} \;=\;
\frac{1}{2}\,\varepsilon(u)\,E^2
\;+\;
\frac{1}{2\,\mu(u)}\,B^2
\;+\;
\frac{1}{2}\,\rho\,v^2
\;+\;
\Pi_{\text{aniso}}
\;+\;
P_{\text{waves}}
$$

## Term Definitions

- $E$ and $B$ are the electric and magnetic field magnitudes.
- $\varepsilon(u)$ and $\mu(u)$ are effective permittivity and permeability functions dependent on the local propagation parameter $u(x)$.
- $\rho$ is the effective mass or charge-carrier density.
- $v$ is the bulk flow velocity.
- $\Pi_{\text{aniso}}$ represents anisotropic pressure or stress arising from directional field gradients or structured confinement.
- $P_{\text{waves}}$ represents stored and propagating wave energy, including oscillatory electromagnetic and magnetohydrodynamic modes.

## Canonical Status

The structure of this functional is treated as canonical within UETC:
- individual terms may be refined or expanded through versioned updates,
- the overall functional form is not redefined without a major version change.

## Related Definition

UETC uses the propagation parameter:

$$
u(x) \;=\; \frac{c_0^2}{c(x)^2} \;=\; n(x)^2,
\qquad \text{vacuum-limit reference: } u = 1
$$

## Repository Reference

For the authoritative, versioned technical reference, see the GitHub repository:
- https://github.com/Kneedeep2005/UETC

Core framework document:
- https://github.com/Kneedeep2005/UETC/blob/main/papers/UETC_Core_Framework.md
