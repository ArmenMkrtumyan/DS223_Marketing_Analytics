# Homework 3: Survival Analysis & CLV

This repository contains the code and report for Homework 3 in **DS 223 Marketing Analytics**.  
The goal of the assignment is to model subscriber churn using survival analysis techniques and to compute customer lifetime value (CLV).

## Project Overview

We use the `telco` subscriber dataset to:

- Fit and compare **parametric AFT models** (Weibull, Log-Logistic, Log-Normal) for churn.
- Select a final AFT model based on statistical fit and managerial interpretability.
- Compute **CLV per customer** using survival probabilities and discounting.


## Repository Structure

- `survival_analysis.ipynb` — main Jupyter notebook with data preparation, survival modeling, CLV calculation, and commentary.
- `telco.csv` — telecom subscriber dataset used in the analysis (time-to-churn and covariates).
- `requirements.txt` — list of Python dependencies to reproduce the analysis.
- `README.md` — this brief project description.

## How to Run

1. Create and activate a virtual environment (recommended).
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter and open the notebook:

   ```bash
   jupyter notebook models.ipynb
   ```

4. Run all cells to reproduce the models, plots, and CLV calculations.