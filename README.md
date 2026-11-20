# Monetary Forensics via Spectral Auditing: Augsburg & Central Europe (1500–1700)

Reproducible Python pipeline, Jupyter/Colab notebook, and high-resolution figures accompanying the preprint:

> **Petr Avtonomov (2026).** *Monetary Forensics via Spectral Auditing: Separating Coinage Debasement from Real Subsistence Crises in Early Modern Augsburg (1500–1700)*.

## Overview
This repository implements the **Two-Echelon Spectral Audit Protocol** on dual-currency commodity price matrices from the Allen–Unger Global Commodity Prices Database (`DOI: 10.34894/IPVXMW`), contrasting nominal accounting units (*Augsburg Dinar*) against pure silver equivalents across:
1. **Augsburg 8-Commodity Basket (`201 × 8`, 1500–1700):** *Barley, Oats, Salt, Beef, Oil, Peas, Flax, Canvas* (after pre-audit sparsity filtering of discontinuous *Beer* and *Paper* series).
2. **Central European 7-Market Grain Benchmark (`201 × 7`, 1500–1700):** *Augsburg (Barley, Oats), Strasbourg (Barley, Rye, Wheat), Frankfurt (Rye), Munich (Rye)*.

## Repository Structure
- `augsburg_monetary_spectral_audit.ipynb` — End-to-end Google Colab / Jupyter notebook reproducing all metrics, 300-iteration bootstrap confidence intervals, Leave-One-Out stability scans, and figures.
- `augsburg_figures/` — High-resolution (300 DPI) publication figures (`fig1`–`fig3`) and the summary table (`augsburg_audit_summary.csv`).

## Data Source
Primary historical price series are openly archived in the **Allen–Unger Global Commodity Prices Database** at the International Institute of Social History (IISH) Dataverse (`doi:10.34894/IPVXMW`). Place `doi-10.34894-ipvxmw.zip` in the working directory to run the notebook from scratch.
