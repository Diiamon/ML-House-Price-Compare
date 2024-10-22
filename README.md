# Housing Price Prediction Models

## Overview

This repository contains the analysis and code for predicting housing prices using machine learning models. The study evaluates model performance across three distinct datasets and provides insights into the impact of various factors on prediction accuracy. The repository includes Jupyter notebooks for each dataset, visualisations of model performance, and an analysis of the results.

## Datasets

The following datasets are used in this analysis:

1. **UK Housing Prices Paid**
   - **Description:** This dataset contains detailed information on property transactions across England and Wales, including sale prices, property types, and transaction dates. It features a large and diverse set of data with historical trends and regional variations.
   - **Usage:** `Data/Price_paid_datasets.docx`

2. **Housing in London**
   - **Description:** This dataset focuses on housing data in London, including monthly average house prices, sales volumes, and socio-economic factors by borough. It offers a detailed look at the London housing market with socio-economic variables.
   - **Usage:** `housing_in_london_monthly_variables.csv`
   - **Usage:** `housing_in_london_yearly_variables.csv`

3. **UK Housing Price Index (UK HPI)**
   - **Description:** This dataset provides a comprehensive view of housing prices across the UK, including seasonal adjustments and variables related to different geographic regions and property types.
   - **Usage:** `UK-HPI-full-file-2024-03.csv`

## Code Notebooks

The code for analyzing and modeling the datasets is organized into three Jupyter notebooks. Each notebook corresponds to one of the datasets and includes data preprocessing, model training, and evaluation steps.

1. **Notebook 1: UK Housing Prices Paid**
   - **Description:** Analysis of the UK Housing Prices Paid dataset, including data cleaning, feature engineering, and model training.
   - **File:** `Codes/Price_paid_explore.ipynb`

2. **Notebook 2: Housing in London**
   - **Description:** Analysis of the Housing in London dataset, featuring application of various models, parameter tuning, and performance evaluation.
   - **File:** `Codes/housing_in_london_explore.ipynb`

3. **Notebook 3: UK Housing Price Index (UK HPI)**
   - **Description:** Comparative analysis of model outcomes using the UK Housing Price Index dataset, including insights on seasonal adjustments and geographic variability.
   - **File:** `codes/housing_data_explore_2.ipynb`

## Visualisations

Visualisations of the Root Mean Square Error (RMSE) results for different models are provided to offer a comparative view of model performance.

- **RMSE Results Visualiaation:** A Tableau visualiaation illustrating the RMSE across different models and datasets.
  - **File:** `RMSE_Visualisation/RMSE_visuals.twb`
  -  **Tableau Public:** ['RMSE Visuals'](https://public.tableau.com/views/RMSE_visuals/All_results?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Analysis Summary

### Analysis of Outcomes and Model Performance

- **Model Performance Summary:**
  - **Gradient Boosted Trees (GBT):** Outperformed other models in accuracy, particularly effective due to its handling of non-linear relationships.
  - **Random Forest:** Offered competitive accuracy with greater interpretability but varied slightly across datasets.
  - **Decision Tree:** Served as a baseline model with less accuracy but provided clear insights into feature importance.

- **Influence of Dataset Characteristics:**
  - **UK Housing Prices Paid Dataset:** Highlighted the importance of temporal features and regional data, with Gradient Boosted Trees and Random Forest excelling due to the dataset's size and diversity.
  - **Housing in London Dataset:** Socio-economic factors and regional focus made this dataset complex. GBT excelled due to its ability to model non-linear interactions.
  - **UK Housing Price Index (UK HPI):** Seasonal adjustments and geographic diversity posed challenges for simpler models. Ensemble methods performed well in capturing regional price variations.

- **Explanation of Model Performance:**
  - The ability to handle non-linear relationships and the robustness of ensemble methods were crucial for performance. Data complexity, feature selection, and dataset specificity also played significant roles in the accuracy of predictions.

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/Diiamon/ML-House-Price-Compare.git
