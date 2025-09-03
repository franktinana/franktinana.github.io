---
title: MACS J0138 — NFW Lensing Fit
summary: "Infer (ρ_s, r_s) from θ_E / κ(R); compare to literature."
images:
  - src: "/assets/img/experiments/macs-j0138/f160w.png"
    alt: "HST WFC3/IR F160W (placeholder until cutout uploaded)"
---

## Objective
Estimate NFW parameters **(ρ_s, r_s)** for MACS J0138 and validate against published constraints.

## Inputs
- Cosmology & redshifts (z_L, z_S)
- Observables: Einstein radius **θ_E** and/or convergence profile **κ(R)**
- Imaging cutouts (HST/MAST)

## Method
1. Adopt priors and cosmology; fix (z_L, z_S).
2. Fit **(ρ_s, r_s)** using θ_E or κ(R); record uncertainties.
3. Cross-check with literature values; track differences.
4. Save artifacts: `nfw_fit.json`, plots.

## Results (TBD)
- Parameter table + residual plots to be added after the next run.

## Artifacts
- `data/` (sources), `figures/` (plots), `nfw_fit.json` (parameters)
