# Student Health Data - Machine Learning Modeling

### 👤 Author Information
- **Name:** Mohammed Abdullah Al Hashim  
- **University ID:** 2240006236  
- **Major:** Cybersecurity & Digital Forensics  

---

## 📌 Lab Overview
This Lab focuses on building a complete **Machine Learning Classification Pipeline** using a student health dataset. The objective is to predict the **Health Risk Level** of students based on behavioral, physiological, and lifestyle factors.

The workflow follows a structured approach starting from feature engineering to model evaluation, ensuring the dataset is properly prepared for accurate and reliable predictions.

---

## 🛠️ Workflow & Methodology

### 1. Data Loading & Exploration
- Loading the dataset and inspecting structure, shape, and column types.
- Checking for missing values and duplicates.
- Understanding feature distributions and dataset characteristics.

---

### 2. Feature Engineering
- Creating new meaningful features to improve model performance.
- Derived categorical tiers using **Discretization (Binning)**.
- Transforming numerical values into interpretable categories.
- Avoiding features that may cause **Data Leakage**.

---

### 3. Feature Selection & Preparation
- Defining the **target variable**:
  - `Health_Risk_Level`
- Removing unnecessary columns:
  - `Student_ID` (identifier only)
- Splitting dataset into:
  - Features (X)
  - Target (y)

---

### 4. Train-Test Split
- Splitting data into training and testing sets.
- Ensuring proper evaluation on unseen data.

---

### 5. Data Preprocessing Pipeline
Using `ColumnTransformer`:

- **Categorical Features:**
  - One-Hot Encoding

- **Numerical Features:**
  - Passed directly (or optionally scaled)

---

### 6. Model Building
- Model used:
  - **Random Forest Classifier**
- Integrated into a **Pipeline** for:
  - cleaner workflow
  - avoiding data leakage
  - reproducibility

---

### 7. Model Evaluation
- Accuracy Score  
- Classification Report  
- Confusion Matrix  

---

### 8. Feature Importance & Selection
- Extracting important features
- Understanding key predictors
- Applying `SelectFromModel` (optional)

---

## 💻 Tech Stack
- **Language:** Python 3  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Jupyter Notebook / VS Code  

---

## 📊 Key Findings
- Built a complete **end-to-end ML pipeline**.
- Identified key factors affecting student health risk.
- Improved interpretability using feature engineering.
- Prevented **data leakage** for reliable evaluation.
- Created a reusable and scalable ML workflow.

---

## 🚀 Conclusion
This lab demonstrates how raw data can be transformed into actionable insights using Machine Learning. The model effectively classifies student health risk levels using a structured pipeline approach.

---

*Developed as part of the ARTI308 Machine Learning Lab* 🚀
