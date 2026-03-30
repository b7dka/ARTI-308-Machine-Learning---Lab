# Student Health Data - Machine Learning Modeling

### 👤 Author
- **Mohammed Abdullah Al Hashim**  
- **ID:** 2240006236  
- **Major:** Cybersecurity & Digital Forensics  

---

## 📌 Overview
This lab builds a **Machine Learning classification model** to predict students' **Health Risk Level** using lifestyle and health-related features.

---

## 🛠️ Methodology
The workflow follows a standard ML pipeline:

- **Data Exploration:** checking structure, missing values, and duplicates  
- **Feature Engineering:** creating new features and using **discretization (binning)**  
- **Feature Selection:** defining target (`Health_Risk_Level`) and removing unnecessary columns  
- **Train-Test Split:** separating data for training and evaluation  
- **Preprocessing:** using `ColumnTransformer` with:
  - One-Hot Encoding (categorical)
  - Numerical features (as-is)  
- **Model:** Random Forest Classifier inside a Pipeline  
- **Evaluation:** Accuracy, Classification Report, Confusion Matrix  

---

## 💻 Tech Stack
- Python 3  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  

---

## 📊 Results
- Built a complete **end-to-end ML pipeline**  
- Improved interpretability using feature engineering  
- Ensured reliable results by avoiding **data leakage**  

---

## 🚀 Conclusion
The model successfully classifies student health risk levels using a structured and reusable ML workflow.

---

*ARTI308 Machine Learning Lab*
