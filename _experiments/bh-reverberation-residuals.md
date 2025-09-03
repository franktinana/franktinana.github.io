---
title: Black-Hole Reverberation Mapping — Signed Residuals
summary: "Compute signed proxy residuals under the temporal-lensing correction; look for systematic signal."
images:
  - src: "/assets/img/experiments/bh-rm/placeholder.png"
    alt: "BH RM dataset placeholder"
---

## Objective
Test whether the correction shows a consistent **signed residual** pattern in BH reverberation-mapped masses.

## Inputs
- Clean RM catalog (object id, z, lag, line width, M_BH)
- Halo environment proxies if available

## Method
1. Build reproducible CSV with provenance.
2. Apply correction; compute signed proxy residuals.
3. Estimate effect size + CIs; non-parametric checks.
4. Record negative results and edge cases.

## Results (TBD)
No significant slope observed in preliminary pass; repeat with stricter quality cuts.

## Artifacts
- `results/bh_residuals.csv`, `figures/bh_residuals_*.png`
