---
title: Gravitational-Wave Events — Timing Residuals
summary: "Check event timing proxies for the same correction signature."
images:
  - src: "/assets/img/experiments/gw-events/placeholder.png"
    alt: "GW event set placeholder"
---

## Objective
Look for a consistent correction signature in GW event timing proxies.

## Inputs
- Curated GW event list (id, z/host proxy, SNR, timing quantities)
- Environment/halo context where available

## Method
1. Build CSV with provenance & quality filters.
2. Compute timing proxy residuals under the correction.
3. Assess significance; compare to null.

## Results (TBD)
Preliminary pass shows no robust signal; expand sample and refine proxies.

## Artifacts
- `results/gw_residuals.csv`, `figures/gw_residuals_*.png`
