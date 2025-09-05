# Assignment 2 — PCA, Dimensionality Reduction, and Logistic Regression

**Name:** Abesech Inbasekar  
**Roll Number:** ME21B003  

---

## Overview

This assignment applies concepts of **vector spaces, dimensionality reduction, and classification** to the Mushroom dataset. The objective is to use **Principal Component Analysis (PCA)** to reduce the dimensionality of one-hot encoded categorical features, and then evaluate the effect of this reduction on a **Logistic Regression classifier**.

The analysis covers:

- One-hot encoding of categorical attributes and separation of features from the target variable
- Standardization of features to ensure equal variance contribution
- PCA decomposition of the feature space and scree plot analysis
- Selection of an optimal number of principal components (retaining ~95% variance)
- Visualization of the dataset in the reduced PCA space (scatter plots and pair plots)
- Baseline Logistic Regression performance on original features
- Logistic Regression performance on PCA-transformed features
- Comparison and analysis of performance trade-offs between full and reduced feature spaces

The final notebook contains all code, plots, stories, and conclusions.

---

## Folder Structure & Submission Details

├── Assignment_2.ipynb # Main Jupyter notebook with full analysis, plots, and discussion  
├── README.md # This file — explains project structure and submission details  


---

## How to Run

1. Clone the GitHub Classroom repository created from the assignment link.  
2. Open `me21b003_Assignment_2.ipynb` in Jupyter Notebook or JupyterLab.  
3. Install the dependencies:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

