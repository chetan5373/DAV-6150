# Final Project: Heart Disease Risk Prediction

This folder contains the resources for the final project of DAV 6150. The project analyzes Medicare claims data to explore factors associated with cardiovascular disease and builds machine learning models to identify populations at risk.

## Contents

- `C_Devarshi_FinalProject.ipynb` – the main analysis notebook.
- `C_Devarshi_FinalProjectProposal.ipynb` – the initial proposal for this project.
- `Center_for_Medicare___Medicaid_Services__CMS____Medicare_Claims_data_20241024.csv` – dataset of Medicare claims with demographic and geographic information.
- `DAV 6150 Fall 2024 Final Project Guidelines.pdf` – project assignment description.

## Overview

The project leverages a dataset compiled by the Centers for Medicare & Medicaid Services (CMS) that tracks heart disease indicators across the United States from 2016 onward. Variables include age group, gender, race, location, and hospitalization rates.

Using this dataset we performed several analyses:

1. **Predictive Modeling** – Training models such as XGBoost and logistic regression to predict which groups are at higher risk for heart disease.
2. **Clustering** – Applying K-means clustering to group regions with similar heart disease rates.
3. **Feature Importance** – Using SHAP values to understand which socioeconomic and demographic factors most influence disparities in heart health.

The XGBoost model achieved the highest predictive performance, and clustering results highlighted socioeconomic differences across regions. The full methodology, code, and visualizations are contained in the main notebook.

## Running the Notebook

Open `C_Devarshi_FinalProject.ipynb` in Jupyter Notebook or JupyterLab and execute the cells in sequence. The notebook expects the CSV data file to remain in the `Final_Project` folder.

---
