---
layout: default
title: Master Equation
permalink: /master-equation/
---

# Canonical UETC Master Energy Functional

This page presents the canonical master energy functional used throughout **Unified Electromagnetic Toroidal Cosmology (UETC)**.

It is provided as a public reference for readers seeking a compact, formal expression of how energy is partitioned within structured electromagnetic systems. Detailed definitions, scope boundaries, and falsifiability criteria are maintained in the GitHub repository’s core framework documents.

## Master Energy Functional (Canonical)

{% raw %}
$$
U_{\text{total}}
=
\frac{1}{2}\varepsilon(u)E^2
+
\frac{1}{2\mu(u)}B^2
+
\frac{1}{2}\rho v^2
+
\Pi_{\text{aniso}}
+
P_{\text{waves}}
$$
{% endraw %}



## Term Definitions

- $E$ and $B$ are the electric and magnetic field magnitudes.
- $\varepsilon(u)$ and $\mu(u)$ are effective permittivity and permeability functions dependent on the local propagation parameter $u(x)$.
- $\rho$ is the effective mass or charge-carrier density.
- $v$ is the bulk flow velocity.
- $\Pi_{\text{aniso}}$ represents anisotropic pressure or stress arising from directional field gradients, structured confinement, or field geometry.
- $P_{\text{waves}}$ represents stored and propagating wave energy, including oscillatory electromagnetic and magnetohydrodynamic modes.

## Canonical Status

The structure of this energy functional is treated as **canonical** within UETC.

- Individual terms may be refined, clarified, or expanded in later versions.
- The overall functional form is not redefined without a corresponding **major version change**.
- No exotic matter, new forces, or violations of conservation laws are introduced.

Dependence on $u(x)$ modifies effective energy partitioning and propagation behavior, not fundamental constants.

## Related Definition: Propagation Parameter

UETC uses an effective propagation parameter defined as:

$$
u(x) \;=\; \frac{c_0^2}{c(x)^2} \;=\; n(x)^2,
\qquad \text{vacuum-limit reference: } u = 1
$$

This parameter is inferred observationally and provides a compact description of how structured electromagnetic environments influence propagation behavior without modifying spacetime itself.

## Repository Reference

This website is a public-facing overview.  
The authoritative, versioned technical reference for UETC is maintained in the GitHub repository:

- https://github.com/Kneedeep2005/UETC

Relevant core documents:
- `papers/UETC_Core_Framework.md`
- `papers/UETC_Observational_Implications.md`
