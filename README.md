# Battery Charging and Discharge in CAISO’s Spring Duck Curve

This repository supports a short whitepaper comparing battery charging and discharge in CAISO’s spring duck curve from 2021–2025.

## Main question

This project compares April and May operating days across recent years to examine:

1. Whether batteries increasingly charge during the midday dip
2. Whether batteries increasingly discharge during the evening ramp
3. How large battery discharge is compared with the 5–9 PM net-load ramp

## Project structure

- `notebooks/`: Jupyter notebook for data cleaning, analysis, and figures
- `data/raw/`: raw CAISO data downloads, not tracked by Git
- `data/processed/`: cleaned data files, not tracked by default
- `figures/`: exported figures used in the paper
- `paper/`: whitepaper draft and final PDF
- `references/`: source and citation notes

## Scope

The analysis is descriptive, not causal. It does not claim that batteries caused the duck curve to change or that batteries reduced the evening ramp. It verifies how the documented battery charging-and-discharge pattern appears in public CAISO spring operating data.