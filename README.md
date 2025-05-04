# Customer Churn Prediction Project

## 📌 Overview

This project aims to predict customer churn using real-world data, focusing on identifying customers likely to leave so that targeted retention strategies can be implemented proactively. The predictive model was developed using multiple machine learning algorithms, including **XGBoost**, **Random Forest**, **CatBoost**, and **LightGBM**, on an imbalanced dataset, representing realistic business scenarios.

---

## 🚀 Objectives

* Develop robust churn prediction models.
* Identify key features influencing customer churn.
* Simulate the business impact of the predictive models.
* Provide actionable insights for improving customer retention.

---

## 🔍 Project Structure

1. **Data Exploration & Preprocessing**

   * Importing and initial exploration of data.
   * Handling missing values.
   * Analysis of categorical and numerical features.
   * Visual exploration.

2. **Feature Engineering**

   * Creation of new features (e.g., contract durations, time-based variables).
   * Encoding categorical variables.
   * Handling timedelta features and transformations.

3. **Statistical Testing & Feature Selection**

   * **Chi-square test** for categorical variable significance.
   * **Pearson and Augustino normality tests** to assess the normality of feature distributions.
   * **Spearman correlation** to identify and mitigate multicollinearity.
   * **Mann-Whitney U test** for comparing distributions between churners and non-churners.
   * **Benjamini-Hochberg procedure** for controlling the false discovery rate in multiple hypothesis testing.
   * **Cohen's d** for effect size measurement.


4. **Data Balancing**

   * Applied SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset for better model training.

5. **Model Development**

   * Machine learning models used:

     * XGBoost
     * Random Forest
     * CatBoost
     * LightGBM

   * Cross-validation on original imbalanced data to simulate real-world performance.

6. **Model Evaluation**

   * Metrics used: Recall, Precision, F1-score, ROC-AUC.
   * Detailed analysis of confusion matrix (false positives and negatives).

7. **Business Case Simulation**

   * Simulation on a test subset of 4357 customers.
   * Calculated expected churners, true positives, false positives.
   * Evaluated financial implications of the models (ROI and cost efficiency).

---

## ⚠️ Limitations & Challenges

* **Low precision** indicates many false positives, leading to unnecessary marketing interventions.

---

## 💡 Recommendations

* Enrich data with additional customer behavior features.
* Experiment with additional data and feature engineering approaches.


---
