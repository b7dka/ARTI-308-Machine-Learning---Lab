# Student Health Data - Data Quality & Preprocessing

### 👤 Author Information
- **Name:** Mohammed Abdullah Al Hashim
- **University ID:** 2240006236
- **Major:** Cybersecurity & Digital Forensics

---

## 📌 Lab Overview
This Lab performs a comprehensive **Data Preprocessing and Quality Assessment** on a student healthcare dataset. The goal is to transform raw, noisy data into a clean, scaled, and optimized format suitable for building robust Machine Learning models, specifically focusing on handling missing data, outliers, and dimensionality reduction.

## 🛠️ Workflow & Methodology
Following a standard Machine Learning preprocessing pipeline, this analysis includes:

1.  **Data Loading & Environment Setup:**
    - Importing essential libraries (`Pandas`, `NumPy`, `Matplotlib`, `Seaborn`, `Scikit-learn`).
    - Implementing a robust loading logic to handle inconsistent CSV formatting (semicolon headers vs. comma-separated data).
2.  **Data Quality Assessment (DQA):**
    - Auditing and converting data types (Age to Integer, Heart Rate/Study Hours to Numeric).
    - Verifying data integrity and ensuring consistency across all 1,000 student records.
3.  **Handling Missing Values (Imputation):**
    - Simulating data loss in `Heart_Rate` for demonstration.
    - Implementing and comparing three strategies: **Removal (Dropna)**, **Mean Imputation**, and **Median Imputation** to preserve dataset size.
4.  **Outlier Detection & Treatment:**
    - Visualizing distribution anomalies using **Boxplots**.
    - Applying the **Interquartile Range (IQR)** method to identify extreme values.
    - Handling outliers via **Removal** and **Capping (Percentile-based clipping)**.
5.  **Data Transformation (Normalization):**
    - Scaling features using **Min-Max Normalization** (0-1 range).
    - Implementing **Z-Score Standardization** to center data around a mean of 0.
6.  **Data Reduction (PCA):**
    - Generating a **Correlation Heatmap** to check for redundant features.
    - Applying **Principal Component Analysis (PCA)** to reduce feature dimensions while capturing maximum variance.

## 💻 Tech Stack
- **Language:** Python 3
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Environment:** Jupyter Notebook / VS Code

## 📊 Key Findings
- Successfully processed **1,000 student health records** into a model-ready format.
- Identified and treated significant outliers in physiological metrics to reduce model bias.
- Reduced dataset dimensions via **PCA**, capturing essential variance while simplifying the feature space.
- Established a clean foundation for subsequent predictive tasks (e.g., Health Risk Classification).

---
*Developed as part of the ARTI308
