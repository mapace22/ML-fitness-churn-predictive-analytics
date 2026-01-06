# 🏋️ Model Fitness: Customer Retention Strategy & Predictive Analytics

## 🎯 Project Objective
The goal of this project was to develop a data-driven strategy for **Model Fitness** to mitigate customer churn. By leveraging **Machine Learning**, I built models to predict the probability of cancellation for the following month and used **Unsupervised Learning** to segment customers into distinct behavioral profiles, allowing for personalized retention interventions.

## 🛠️ Technical Pipeline & Methodology
The analysis was executed through a comprehensive Machine Learning workflow:

1.  **Exploratory Data Analysis (EDA):** Analyzed a dataset of 4,000 customers with 14 behavioral and demographic features.
2.  **Predictive Modeling (Supervised Learning):**
    * Implemented and compared **Logistic Regression** and **Random Forest Classifier**.
    * **Performance Metrics:** Logistic Regression outperformed with **92.25% Accuracy** and **97.06% ROC AUC**.
3.  **Customer Segmentation (Unsupervised Learning):**
    * Applied **K-Means Clustering** to identify 5 distinct user profiles.
    * Used **Dendrograms** to determine the optimal number of clusters.
4.  **Feature Importance:** Identified that contract duration and visit frequency are the strongest predictors of retention.

## 📊 Key Findings & Model Performance

### Model Comparison Table:
| Metric | Logistic Regression | Random Forest |
| :--- | :--- | :--- |
| **Accuracy** | 92.25% | 91.50% |
| **Recall** | 82.83% | 81.31% |
| **ROC AUC** | 97.06% | 96.80% |

### Strategic Segmentation:
* **Cluster 3 (Critical Risk):** 51.4% Churn rate. Characteristics: Short-term contracts + Low engagement.
* **Cluster 0 (Loyal Core):** 2.8% Churn rate. Characteristics: Long-term commitment + High additional spending.

## 💡 Strategic Recommendations
* **Onboarding Optimization:** Focus resources on customers during their first 60 days, as this period is critical for long-term retention.
* **Incentivize Commitment:** Shift users from 1-month to 6/12-month contracts through targeted discounting.
* **Engagement Alarms:** Implement an automated system to trigger retention offers when a user's weekly visit frequency drops below their historical baseline.

## 📂 Project Structure
* `Sprint_Proyecto_13.ipynb`: Full analytical notebook including EDA, modeling, and conclusions.
* `gym_churn_us.csv`: Customer behavioral dataset.
* `Executive_Summary.pdf`: Strategic presentation for stakeholders.

## 🚀 Tech Stack
* **Python:** Pandas, NumPy.
* **Machine Learning:** Scikit-learn (LogisticRegression, RandomForestClassifier, KMeans).
* **Visualization:** Matplotlib, Seaborn.
* **Statistics:** SciPy (Dendrogram/Linkage).

---
**Author:** Marcel Andrés Palma Céspedes  
**Role:** Data Scientist / ML Analyst  
**Date:** 03/08/2025
