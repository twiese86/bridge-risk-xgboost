# Bridge Maintenance Risk Forecasting (XGBoost Framework)

This repository contains the full implementation of the cost-driven machine learning framework described in the manuscript:

**"Forecasting the Fracture: A Cost-Driven Machine Learning Framework for Optimal Bridge Maintenance Prioritization"**

## Contents

- `notebooks/Bridgev5.ipynb`: Clean manuscript-ready code and analysis.
- `src/`: Modular Python scripts for preprocessing, model training, evaluation, and decision threshold optimization.
- `outputs/`: Example visual outputs including SHAP feature importance and net savings simulation.
- `data/instructions.txt`: How to acquire and format the National Bridge Inventory (NBI) dataset.

## How to Reproduce

1. Clone the repo
2. Install dependencies: `conda env create -f environment.yml`
3. Download the NBI 2020–2024 data (see `data/instructions.txt`)
4. Run `notebooks/Bridgev5.ipynb` or execute the pipeline via `src/` scripts.

## Features

- XGBoost-based binary classification model
- SHAP-based explainability
- Cost-based decision threshold simulation
- Reproducible longitudinal cohort generation

## Data Source

U.S. National Bridge Inventory: https://www.fhwa.dot.gov/bridge/nbi/ascii.cfm
