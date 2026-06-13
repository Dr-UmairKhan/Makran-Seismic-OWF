Khan et al., 2026
Umair Khan
Hainan Institute of Zhejiang University

## Permission
If you use this code or data in your research, please ask permission from Dr. Umair Khan (Email: umairkhanbku@gmail.com; umairkhan@zju.edu.cn)

## Description
This repository contains the complete analysis pipeline for the paper.  
We integrate geophysical data, machine learning, and multi‑criteria decision analysis to map seismogenic potential and suitable areas for offshore wind turbines in the Makran region (North Arabian Sea).

The code reproduces:
- Geophysical factor maps, boxplots, Cohen’s d effect sizes.
- Machine learning probability maps, feature importance, SHAP, ROC curves.
- Extended suitability maps (7 criteria + final integrated index) plus discussion panels: trade‑off, Pareto front, weighted contribution, correlation matrix.
- Main Tables 1–3 (descriptive statistics, logistic regression odds ratios, stacked ensemble metrics).
- Supplementary Tables S1–S3 (model performance, feature importance, suitability criteria ranges).


## Requirements
- Python 3.9 (recommended)
- Install dependencies: `pip install -r requirements.txt`

## How to run
1. Clone or download this repository.
2. Ensure all input data files are inside `input_data/`.
3. Launch Jupyter Notebook:  
   `jupyter notebook "Seismic-OWFs_Makran_Northern_Arabian_Sea.ipynb"`
4. Run all cells (Kernel → Restart & Run All).
5. Outputs will be written to `output_figures/` and `output_tables/`.

## Input data
All input data are provided in `input_data/`:
- Geophysical grids (magnetic, wedge thickness, density, taper angle, basal stress, slab dip, residual gravity, slab temperature)
- Bathymetry
- Cumulative seismic energy release (log scale)
- Wind capacity factor (IEC Class I)
- Port locations (`Ports Location.xlsx`)

All data sources are cited in the paper.
