# Credit Card Customer Segmentation Project - K-Means Clustering

### 👤 Author
- **Mohammed Abdullah Al Hashim**
- **ID:** 2240006236  
- **Major:** Cybersecurity & Digital Forensics  

---

## Overview
This lab focuses on applying **unsupervised machine learning** using the **K-Means clustering** algorithm. The goal is to segment credit card customers into different groups based on their usage behavior.

The project uses the **CC_GENERAL.csv** dataset, which contains customer-level credit card information such as balance, purchases, cash advance, credit limit, payments, and tenure. Since the dataset does not include a target label, clustering is used to discover hidden patterns and customer segments.

---

## Methodology
The workflow follows a standard unsupervised machine learning pipeline:

- **Data Loading:** Reading the `CC_GENERAL.csv` dataset into a dataframe called `df`.
- **Data Exploration:** Checking the first rows, dataset shape, basic information, and summary statistics.
- **Data Cleaning:** Removing the `CUST_ID` column because it is only an identifier and does not describe customer behavior.
- **Missing Value Handling:** Checking missing values and filling them using mean imputation.
- **Exploratory Data Analysis (EDA):** Understanding the dataset using:
  - Histograms for numerical columns.
  - Correlation heatmap to identify relationships between features.
  - Scatter plot between `BALANCE` and `PURCHASES`.
  - Scatter plot between `BALANCE` and `CASH_ADVANCE`.
- **Feature Scaling:** Applying `StandardScaler` because K-Means is distance-based and the features have different ranges.
- **Choosing K:** Comparing different K values using:
  - Elbow Method
  - Silhouette Score
- **Final K-Means Model:** Training the final K-Means model using `random_state=42` and `n_init=10`.
- **Cluster Analysis:** Adding cluster labels to the dataset and analyzing the mean values of each cluster.
- **Visualization:** Using PCA to reduce the data into two components and visualize the final clusters in 2D.

---

## Results
- **Missing Values:** The columns `CREDIT_LIMIT` and `MINIMUM_PAYMENTS` contained missing values.
- **Missing Value Treatment:** Missing values were filled using the mean value of each column.
- **Scaling:** Standardization was applied before clustering to prevent large-scale features from dominating the distance calculation.
- **Chosen K:** The final selected number of clusters was **K = 4**.
- **Cluster Interpretation:** The final clusters represented different types of credit card customers, such as:
  - Customers with moderate purchases and frequent purchase activity.
  - High-value customers with high purchases, high credit limits, and high payments.
  - Customers who rely more on cash advance services.
  - Lower-activity customers with lower purchases and lower credit limits.

---

## Conclusion
This lab demonstrates how **K-Means clustering** can be used to segment customers without having predefined labels. By analyzing customer behavior, the model grouped similar credit card users together based on their financial activity.

The results show that clustering can help companies understand different customer types and create better marketing strategies. For example, high-value customers can receive premium offers, cash-advance users can receive financial support plans, and low-activity customers can receive promotions to increase engagement.

---

*ARTI308 Machine Learning Lab*
