# Density-Gradient–Based Inference Scaler (Working Hypothesis)

## Status and intent

This is a **working hypothesis**, recorded to support falsifiable tests and structured discussion.

It is **not** a precision fit, **not** unique, and **not** a claim of proof. The purpose is to propose a minimal, bounded response law that can be tested against observational inference behavior across systems.

## Motivation

We explore a simple, bounded inference-correction law motivated by **cumulative exposure to density gradients along photon paths**, rather than additional mass components or modified gravity.

The idea is to treat certain propagation-linked inference distortions as potentially correlated with integrated “structure exposure” along the line of sight.

## Gradient-exposure variable

We define a dimensionless gradient-exposure variable:

$$
\chi \equiv \int_{\mathrm{LOS}} \left| \nabla \ln \rho \right| \, ds
$$

where:
- $\rho$ is an effective medium or plasma-linked density proxy (context-dependent),
- $ds$ is a differential path-length element along the line of sight,
- $\left|\nabla \ln \rho\right|$ emphasizes **relative** density structure rather than absolute scaling.

## Saturating response law

We use a saturating response:

$$
u(\chi) = 1 + A\left(1 - e^{-\chi/\chi_0}\right),
\qquad u \rightarrow 1 \;\; \text{in vacuum}
$$

This form is intentionally minimal and chosen for its constraints:

- **Bounded** (no divergences),
- **Monotonic** (increasing exposure produces a non-decreasing response),
- **Dimensionless** (scale-free),
- **Cross-system compatible** (galaxies → compact objects).

## Relationship to UETC propagation parameterization

UETC uses the effective propagation modifier:

$$
u(x)=\frac{c_0^2}{c(x)^2}=n(x)^2
$$

The \(\chi\)-based form above is a **candidate organizing variable** for how \(u\) might respond to cumulative structured environments along a path, without implying changes to fundamental constants.

## Illustrative application (galactic-scale)

As an illustrative, non-fitted example, this hypothesis is applied at the
galactic scale in:

- **NGC 2403: Normalized-Radius Overlay on Conceptual u(x)**  
  `ngc2403_normalized_overlay.md`

That entry presents a qualitative shape comparison between a bounded u(x)
response and the observed NGC 2403 rotation curve using shared normalized-radius
coordinates.

The purpose of the example is to assess **structural compatibility**, not to
demonstrate agreement, derive parameters, or assert explanatory completeness.

## Explicit non-claims

This entry does **not** claim:
- an observationally validated best-fit form,
- a unique mapping from baryonic density to \(\rho\),
- a completed derivation from first principles,
- or a dark-matter replacement result.

It records a bounded functional form intended to be tested, constrained, or rejected.
