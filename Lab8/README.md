# K-Nearest Neighbors (KNN) Project - Classification Modeling

### 👤 Author
- **Mohammed Abdullah Al Hashim**
- **ID:** 2240006236  
- **Major:** Cybersecurity & Digital Forensics  

---

##  Overview
This lab focuses on building a **Machine Learning classification model** using the **K-Nearest Neighbors (KNN)** algorithm. The goal is to classify anonymized data points into specific target classes based on their feature similarities.

---

##  Methodology
The workflow follows a standard ML pipeline with a focus on data scaling, which is critical for distance-based algorithms like KNN:

- **Data Exploration:** Checking the structure of the anonymized dataset, summary statistics, and target distributions.
- **Data Standardization:** Applying **StandardScaler** to normalize features, ensuring that all variables contribute equally to the distance calculations.
- **Train-Test Split:** Partitioning the data into training and testing sets (70/30) to evaluate model performance.
- **Choosing K Value (The Elbow Method):** Running iterations for different K values (from 1 to 40) to find the optimal value that minimizes the error rate.
- **Model Training:** Fitting the **KNeighborsClassifier** using the optimized K value.
- **Evaluation:** Measuring model accuracy using:
  - Confusion Matrix
  - Precision, Recall, and F1-score (Classification Report)

---

##  Results
- **Optimization:** Identified that **K=31** provided a low error rate and stable performance.
- **Performance:** The model achieved an overall **accuracy of 84%**.
- **Metrics:** Successfully balanced precision and recall for both target classes (0 and 1).
- **Standardization:** Confirmed that scaling data is a fundamental step for high-accuracy KNN models.

---

## Conclusion
The lab demonstrates the effectiveness of the **K-Nearest Neighbors** algorithm in handling classification tasks. By utilizing the **Elbow Method**, we were able to transition from a baseline model (K=1) to an optimized version (K=31) that significantly improved prediction reliability.

---

*ARTI308 Machine Learning Lab*
