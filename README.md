# COMPAS Fairness Audit

This project contains a Jupyter Notebook for a fairness audit of the COMPAS dataset using the AI Fairness 360 (AIF360) toolkit.

## Assignment Overview
This notebook is part of the "Designing Responsible and Fair AI Systems" assignment. It demonstrates how to:
- Load and preprocess the COMPAS dataset
- Train a simple classifier
- Compute and visualize fairness metrics
- Summarize findings and suggest remediation steps

## How to Run
1. **Install dependencies:**
   ```bash
   pip install aif360 pandas matplotlib scikit-learn jupyter
   ```
2. **Download the COMPAS dataset:**
   The notebook will automatically download `compas-scores.csv` if it is not present.
3. **Start Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```
4. **Open and run `compas_fairness_audit.ipynb`.**

## Interpreting Results
- The notebook explains each fairness metric and its ethical significance.
- Visualizations highlight disparities in model performance across race groups.
- The final report summarizes findings and suggests ways to mitigate unfairness.
