# Decision Trees and Random Forest Project - Classification Modeling

### 👤 Author
- **Mohammed Abdullah Al Hashim**
- **ID:** 2240006236  
- **Major:** Cybersecurity & Digital Forensics  

---

## Overview
This lab focuses on building **Machine Learning classification models** using **Decision Tree** and **Random Forest** algorithms. The goal is to predict whether a borrower will fully pay back a loan or not based on loan-related features.

---

## Methodology
The workflow follows a standard ML pipeline with a focus on comparing a single tree model with an ensemble learning model:

- **Data Exploration:** Checking the structure of the loan dataset, summary statistics, and understanding the target column `not.fully.paid`.
- **Exploratory Data Analysis (EDA):** Visualizing important relationships such as FICO score, interest rate, loan purpose, credit policy, and payment status.
- **Categorical Data Handling:** Converting the `purpose` column into numerical dummy variables using `pd.get_dummies()`.
- **Train-Test Split:** Partitioning the data into training and testing sets using a 70/30 split.
- **Decision Tree Model:** Training a **DecisionTreeClassifier** to classify loan payment status.
- **Random Forest Model:** Training a **RandomForestClassifier** using multiple decision trees to improve prediction stability.
- **Evaluation:** Measuring model performance using:
  - Confusion Matrix
  - Precision, Recall, and F1-score (Classification Report)

---

## Results
- **Decision Tree:** Built a baseline classification model using a single decision tree.
- **Random Forest:** Improved the model by combining multiple decision trees through ensemble learning.
- **Performance:** Random Forest generally provides more stable and reliable predictions compared to a single Decision Tree.
- **Data Preparation:** Confirmed that converting categorical features into numerical format is required before model training.

---

## Conclusion
The lab demonstrates how **Decision Trees** and **Random Forests** can be used for classification tasks. While Decision Trees are simple and easy to interpret, Random Forests usually perform better because they reduce overfitting by combining multiple trees.

---

*ARTI308 Machine Learning Lab*
