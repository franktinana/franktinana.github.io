---
title: MACS J0138 — NFW Lensing Fit
summary: "Infer (ρ_s, r_s) from θ_E / κ(R); compare to literature."
images:
  - src: "/assets/img/experiments/macs-j0138/f160w.png"
    alt: "HST F160W"
    caption: "HST WFC3/IR F160W drizzled preview (MACS J0138)."
  - src: "/assets/img/experiments/macs-j0138/f110w.png"
    alt: "HST F110W"
    caption: "HST WFC3/IR F110W preview."
---

**Goal.** Estimate NFW parameters and validate against published constraints.

**Inputs.** z_L, z_S, θ_E (or κ(R)), cosmology; imaging cutouts; priors.

**Outputs.** `nfw_fit.json`, comparison plots, residuals.

### Observational Images
{% include gallery.html images=page.images %}
