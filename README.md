# DA5401 Assignment 2 — PCA, Dimensionality Reduction, and Logistic Regression

**Name:** Abesech Inbasekar  
**Roll Number:** ME21B003  

---

## 📂 Repository Structure

├── Assignment_2.ipynb     # Main Jupyter notebook with code, visualizations, and analysis
├── README.md              # This file
└── data/                  # (Optional) Folder for dataset if needed locally


- **Assignment_2.ipynb**: Contains the complete workflow, including  
  - Part A: EDA & preprocessing (one-hot encoding, standardization)  
  - Part B: PCA analysis, scree plots, and visualizations  
  - Part C: Logistic Regression models (baseline vs PCA) with comparison and narrative  

- **data/**: If you downloaded the Kaggle Mushroom dataset locally, place it here.  
  The notebook is written so that the dataset path can be easily modified if required.

---

## 📝 Assignment Overview

This assignment explores the application of **Principal Component Analysis (PCA)** to a high-dimensional categorical dataset (Mushroom classification). The task is to reduce dimensionality after one-hot encoding and evaluate the effect of this reduction on a **Logistic Regression classifier**.  

Key objectives:  
1. Apply one-hot encoding and standardization to categorical features.  
2. Perform PCA and analyze variance distribution via scree plot.  
3. Visualize data in reduced dimensions to assess class separability.  
4. Compare baseline Logistic Regression performance with PCA-transformed performance.  
5. Reflect on trade-offs between dimensionality reduction, information retention, and model efficiency.  

---

## ✅ How to Run

1. Clone the GitHub Classroom repository created from the assignment link.  
2. Open `me21b003_assignment_2.ipynb` in Jupyter Notebook or JupyterLab.  
3. Ensure dependencies are installed:  
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn

