# Spacefield Transformation I

## A Geometric Closure Framework for Cosmological Mass, Confinement Scale, and Expansion Dynamics

**Author:** Joshua Chukwuemeke Egbon  
**Affiliation:** Spacefield Transformation Technologies Ltd, United Kingdom  
**Contact:** joshua@spacefieldtech.com  
**Version:** 1.0.0  
**Release date:** 19 August 2026  
**DOI:** 10.5281/zenodo.22004528

---

## Overview

This repository contains the manuscript source, numerical notebooks, figures,
and reproducibility materials associated with **Spacefield Transformation I
(Paper I)**.

Paper I formulates the minimal **Spacefield Transformation (SFT)** /
**Universal Confinement Zone (UCZ)** cosmological closure framework.

The framework distinguishes between:

- the dimensionless SFT closure and partition structure;
- the specified dimensional confinement normalization of the minimal branch;
- quantities determined conditionally from the closure construction; and
- present-epoch cosmological quantities supplied as observational anchors.

The baseline dimensional confinement normalization is

\[
\eta_{\min}=\frac{2}{9}\ {\rm kg\,m^{-2}}.
\]

This dimensional normalization is specified for the minimal SFT branch rather
than derived from the dimensionless partition ratios alone.

Conditional on this normalization, the closure construction determines the
baseline matter mass \(M_m\) and confinement radius \(R_c\).

Present-epoch observational quantities are then combined with the
closure-normalized quantities and standard FRW consistency relations to
reconstruct the corresponding late-time cosmological background.

---

## Dark-Energy Evolution

Paper I introduces the phenomenological boundary-scaling law

\[
\rho_{\rm DE}(a)
=
\rho_{{\rm DE},0}a^{3(1-\alpha)}.
\]

The transport parameter \(\alpha\) is not assigned a unique SFT-predicted
value in Paper I.

The limit

\[
\alpha=1
\]

corresponds to constant dark-energy density and therefore reproduces the
corresponding Lambda-CDM background evolution.

Values of \(\alpha\) close to unity are used to calculate **conditional
observational response curves**, rather than parameter-free predictions of
the minimal closure condition.

---

## Standard Sirens

Paper I assumes standard General-Relativistic tensor propagation.

Consequently, gravitational-wave and electromagnetic signals propagating
through the same SFT cosmological background share the same cosmological
luminosity distance.

The standard-siren observable studied in the final Paper I formulation is

\[
\Delta_{\rm siren}(z)
=
\frac{d_L^{\rm SFT}(z)}
     {d_L^{\Lambda{\rm CDM}}(z)}
-1,
\]

rather than a gravitational-wave versus electromagnetic propagation offset.

---

## Reproducibility

The numerical materials associated with Paper I include calculations for:

- cosmic-age integration;
- supernova distance-modulus residuals;
- fractional-density evolution;
- SFT versus Lambda-CDM expansion-rate residuals;
- standard-siren luminosity-distance residuals; and
- future comoving-horizon calculations.

The final repository preserves the numerical notebooks and figure-generation
materials corresponding specifically to **Paper I v1.0.0**.

Development-stage calculations that were superseded during the final
scientific audit should not be interpreted as part of the final Paper I
formulation.

---

## Repository Structure

The v1.0.0 release is organised around the following structure:

```text
Spacefield-Transformation-Paper-1/
│
├── README.md
├── CITATION.cff
├── main.tex
├── SFT_Paper1_References.bib
├── Spacefield_Transformation_I_v1.0.pdf
│
├── figures/
│   ├── Appendix_Fig_A1_t0_integrand_updated.png
│   ├── SFT_SN_residuals_updated.png
│   ├── DeltaMu_panels.png
│   ├── H_ratio_SFT_LCDM.png
│   └── standard_siren_SFT_LCDM_residual.png
│
└── notebooks/
    ├── Integrand_Cosmic_Age.ipynb
    ├── SFT_SN_Residuals_vs_LCDM.ipynb
    ├── Fractional_Density_Evolution.ipynb
    ├── Fractional_Hubble_Deviation.ipynb
    ├── SFT_Standard_Siren_Distance_Residual.ipynb
    └── Cumulative_Comoving_Horizon.ipynb
```

---

## Archival Record and DOI

The frozen **Paper I v1.0.0** release is archived on Zenodo.

**DOI:** 10.5281/zenodo.22004528

**Permanent record:** https://doi.org/10.5281/zenodo.22004528

The Zenodo record provides the permanent archival version of Paper I, while
this GitHub repository contains the version-controlled manuscript source,
numerical notebooks, figure-generation materials, bibliography, and
supporting reproducibility files.

The archived materials correspond to the frozen **Paper I v1.0.0** release.

---

## Citation

If you use or discuss this work, please cite:

> Egbon, Joshua Chukwuemeke (2026). *Spacefield Transformation I: A Geometric
> Closure Framework for Cosmological Mass, Confinement Scale, and Expansion
> Dynamics*. Version 1.0.0. Zenodo.
> DOI: 10.5281/zenodo.22004528.

BibTeX:

```bibtex
@misc{egbon2026spacefieldI,
  author       = {Egbon, Joshua Chukwuemeke},
  title        = {Spacefield Transformation I: A Geometric Closure Framework
                  for Cosmological Mass, Confinement Scale, and Expansion Dynamics},
  year         = {2026},
  version      = {1.0.0},
  publisher    = {Zenodo},
  doi          = {10.5281/zenodo.22004528},
  url          = {https://doi.org/10.5281/zenodo.22004528}
}
```

Machine-readable citation metadata are also provided in `CITATION.cff`.

---

## Source and Archival Relationship

The GitHub repository is the version-controlled source and reproducibility
repository for Paper I.

The Zenodo record is the permanent archival record for the frozen
**v1.0.0** release.

Future development of the SFT framework may occur in this repository or in
subsequent repositories and publications. Such later development should not
be interpreted as modifying the archived Paper I v1.0.0 record.

---

## License

The archived Paper I record is released under the license specified in the
corresponding Zenodo record.

Please cite the work when reusing or discussing material from this repository.

---

## Status

**Paper I v1.0.0 — Frozen archival release**

Permanent DOI:

**10.5281/zenodo.22004528**
