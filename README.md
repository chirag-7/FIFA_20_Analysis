# FIFA 20 Data Analysis Notebook

## Overview

This Jupyter notebook (`FIFA 20.ipynb`) contains a comprehensive analysis of the FIFA 20 player dataset, combining data cleaning, exploratory visualization, and basic modeling to uncover insights about player attributes and market values.

## Contents

1. **Data Loading & Cleaning**

   * Import CSVs, handle missing values, and standardize column names.
2. **Exploratory Data Analysis (EDA)**

   * Distribution plots, correlation heatmaps, and feature distributions.
   * Top performers by position, age, nationality, and club.
3. **Feature Engineering**

   * Creation of composite metrics (e.g., Overall vs. Potential gap).
   * Binning and normalization of key stats.
4. **Clustering & Segmentation**

   * K‑Means clustering to identify player archetypes.
   * Visualization of clusters in 2D feature space.
5. **Predictive Modeling**

   * Regression models (Linear, Random Forest) to predict player market value.
   * Model evaluation and performance metrics.
6. **Interactive Visualizations (optional)**

   * Plotly-based charts for dynamic exploration.

## Requirements

* **Python**: ≥3.7
* **Libraries**: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`, `plotly` (optional)

## How to Run

1. Clone or download the repository containing `FIFA 20.ipynb`.
2. Install dependencies:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn plotly
   ```
3. Launch Jupyter Notebook in the project directory and open `FIFA 20.ipynb`.
4. Execute cells sequentially to reproduce the analysis.

