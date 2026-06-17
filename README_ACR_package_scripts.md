# ACR Scripts Package

This package contains all executable scripts used in the revised ACR manuscript and OSF preregistration materials.

## Included scripts
- `metrics_core.py` — corrected metric library for FC, beta_n_star, n_eff, and P_tilde_q.
- `simulate_ds004024.py` — synthetic digital-twin pipeline for the structural anchor dataset.
- `simulate_ds006623.py` — synthetic propofol-state pipeline for the exploratory state-sensitivity dataset.
- `ablation_tests.py` — formal sanity/ablation tests confirming that corrected estimators pass and deprecated invalid formulas are excluded.
- `run_all.py` — convenience script to reproduce all synthetic outputs.

## Scope
Only corrected formulas and valid estimators are included in this package. No scripts implementing deprecated or mathematically invalid definitions are included.

## Expected outputs
- `syn-ds004024/derivatives/metrics/*.tsv`
- `syn-ds006623/derivatives/metrics/*.tsv`
