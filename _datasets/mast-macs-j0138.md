---
title: MAST — MACS J0138 Cutouts
summary: "HST cutouts + WCS notes; filters F110W/F160W. Includes dataset details for NFW experiment."
links:
  - text: "MAST search portal"
    href: "https://mast.stsci.edu/"
---

## Provenance
Describe exact program ids, filters, and retrieval scripts here. Include WCS, pixel scale, and checksums.

## Datasets for MACS J0138 — NFW Fit

### Imaging (HST/MAST)
- **Source:** Mikulski Archive for Space Telescopes (MAST)
- **Programs used:**
  - *HST WFC3/IR* — F105W, F110W, F160W cutouts
  - *HST ACS/WFC* — F555W
- **Paths after download:**
  ```text
  ~/Downloads/MAST_MACS_J0138/mastDownload/output/*cutout.fits
  ```
- **Role in experiment:** context images for Einstein ring, convergence map checks, and BCG centering.

### Redshifts
- **Lens redshift (cluster):** \( z_L = 0.336 \)  
- **Source redshift (SN host galaxy):** \( z_S = 1.949 \)  
- **Sources:** CLASH/HST programs, Newman et al. (2022, A&A) multiply-imaged SN host redshift.

### Mass Constraint
- **Reference:** enclosed mass at \( R_* = 60\, \mathrm{kpc} \)  
- **Value used:** \( M(<R_*) = 2.89 \times 10^{13} \, M_\odot \)  
- **Role in fit:** anchor to compute expected Einstein radius and derive NFW parameters.

### Einstein Radius
- **Observed / published:** ~13 arcsec scale from strong-lensing reconstructions.  
- **Used in run:** solved \( \theta_E \approx 13.03'' \) from \( M(<60 \, \mathrm{kpc}) \) prior.  
- **Role in fit:** main observable for cross-check with NFW halo.

### Artifacts & Outputs
- **Data folder:** `data/`
  - `bcg_center.txt` (cluster center)  
  - Literature values (collected notes, redshifts, θ_E)  
- **Generated:**
  - `nfw_fit.json` (fitted \( \rho_s, r_s \))  
  - `output/figures/` (κ(R) plots, residuals, θ_E diagnostics)

## Plain-English Summary
- **Images**: HST cutouts show arcs and Einstein ring for MACS J0138.  
- **Numbers**: cluster redshift (0.336), source redshift (1.949), known enclosed mass at 60 kpc.  
- **Checks**: predicted Einstein radius (13.03 arcsec) matches literature, validating the NFW setup.  
- **Storage**: sources in `data/`, fits in `nfw_fit.json`, plots in `figures/`.  

