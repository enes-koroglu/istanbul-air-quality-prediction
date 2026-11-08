# Istanbul Air Quality Prediction

## Project Overview

This project aims to predict next-day PM2.5 concentrations
across 10 districts of Istanbul using historical air
pollution and meteorological measurements.

The project also investigates whether meteorological
variables improve prediction performance.

## Dataset

Dataset: Air Quality Monitoring Istanbul 2025-2026

Source:
https://www.kaggle.com/datasets/alirezasouri2/air-quality-monitoring-istanbul-2025-2026

Authors: Souri, A. and Ebrahimishadman, M. (2026)

License: CC BY 4.0

The dataset contains:
- 18,264 observations
- 14 columns
- 10 districts
- Measurements from March 2025 to April 2026

Target variable: Next-day PM2.5 concentration

## Technologies

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- GitHub

## Repository Structure

- data/: Original dataset and source information
- notebooks/: Jupyter notebooks
- src/: Reusable Python source code
- reports/: Reports, figures and results
- requirements.txt: Project dependencies

## How to Run

1. Open notebooks/01_data_loading.ipynb in Google Colab.
2. Run the notebook cells in order.
3. The dataset is loaded directly from GitHub.
4. Inspect the dataset structure and missing values.
5. Run the preliminary chronological data split.

No manual CSV upload is required.

## Data Splitting

The initial chronological split uses:
- Training: approximately 70%
- Validation: approximately 15%
- Testing: approximately 15%

The final split will be checked after constructing
the next-day PM2.5 prediction target.

## Reproducibility

Random seed: 42

Dependencies are documented in requirements.txt.

## Project Status

Stage 4: Data loading, environment setup,
and preliminary split validation completed.

Data cleaning, feature engineering, and model
development are planned for subsequent stages.

