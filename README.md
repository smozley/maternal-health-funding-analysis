# Maternal Health Funding Analysis

This repository contains a reproducible workflow for analyzing maternal health funding disparities across Texas counties. It includes data preparation, regression modeling, geospatial analysis (LISA), and visualizations.

## Structure

- `data/`: Contains raw and external source data (already populated).
- `notebooks/`: Jupyter notebooks for each analysis step.
- `outputs/`: Final figures and tables for reporting.
- `environment.yml`: Conda environment for reproducibility.

## Workflow

1. `01_merge_data.ipynb` — Load and merge live births, ACS, and region data.
2. `02_descriptive_analysis.ipynb` — Generate summary statistics and visualizations.
3. `03_regression_modeling.ipynb` — Model associations between funding and outcomes.
4. `04_spatial_analysis_LISA.ipynb` — Detect spatial clusters of poor maternal outcomes.

## Author
Stephanie Mozley
