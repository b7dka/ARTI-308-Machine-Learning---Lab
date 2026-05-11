# Support Vector Machines Project - Iris Classification

### 👤 Author
- **Mohammed Abdullah Al Hashim**
- **ID:** 2240006236  
- **Major:** Cybersecurity & Digital Forensics  

---

## Overview
This lab focuses on building a **Machine Learning classification model** using the **Support Vector Machine (SVM)** algorithm. The goal is to classify iris flowers into their correct species based on flower measurements such as sepal length, sepal width, petal length, and petal width.

The project uses the famous **Iris dataset**, which contains three flower species:

- Iris-setosa
- Iris-versicolor
- Iris-virginica

---

## Methodology
The workflow follows a standard ML pipeline with a focus on training and evaluating a Support Vector Machine classifier:

- **Data Loading:** Loading the Iris dataset using `sns.load_dataset('iris')`.
- **Data Understanding:** Reviewing the structure of the dataset and identifying the feature columns and target column `species`.
- **Exploratory Data Analysis (EDA):** Visualizing the dataset using:
  - Pairplot to compare species separation across features.
  - KDE plot to analyze the relationship between `sepal_length` and `sepal_width` for the setosa species.
- **Feature Selection:** Separating the dataset into:
  - Features: `sepal_length`, `sepal_width`, `petal_length`, and `petal_width`
  - Target: `species`
- **Train-Test Split:** Partitioning the data into training and testing sets using a 70/30 split.
- **SVM Model:** Training an **SVC** model from Scikit-Learn to classify the iris flower species.
- **Model Evaluation:** Evaluating the model using:
  - Confusion Matrix
  - Precision, Recall, and F1-score (Classification Report)
  - Accuracy Score
- **Hyperparameter Tuning:** Using **GridSearchCV** to test different values of `C` and `gamma` for the RBF kernel.

---

## Results
- **EDA:** The pairplot showed that **setosa** is the most separable species compared to versicolor and virginica.
- **SVM Classifier:** The initial SVC model performed very well on the test data.
- **Model Accuracy:** The model achieved approximately **97.8% accuracy** on the test set.
- **GridSearchCV:** Hyperparameter tuning was applied using different values of `C` and `gamma`.
- **Performance Comparison:** The tuned GridSearch model produced similar results because the original SVM model was already highly accurate on the Iris dataset.

---

## Conclusion
The lab demonstrates how **Support Vector Machines** can be used for classification tasks. SVM performed very well on the Iris dataset because the classes, especially setosa, are clearly separable based on the flower measurements.

The lab also shows the importance of model evaluation and hyperparameter tuning using **GridSearchCV**. Even though the tuning did not significantly improve the result, it provided useful practice in optimizing machine learning models.

---

*ARTI308 Machine Learning Lab*
