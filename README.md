# personality-classification-ml
Predicting personality types (Introvert vs Extrovert) from lifestyle traits using logistic regression, SVM, and XGBoost etc.

---

## 📌 Overview

This project aims to classify individuals as **Introverts** or **Extroverts** based on behavioral traits using supervised machine learning models. It walks through the entire ML pipeline: from data cleaning and exploratory analysis to model training and evaluation.

---

## 🧠 Problem Statement

Can personality type be predicted based on lifestyle habits like time spent alone, social event attendance, and social media activity?

---

## 🗃️ Dataset

- **Size:** 2,900 records  
- **Source:** This dataset was provided by my university professor in its raw, unprocessed form for academic purposes. It is based on the publicly available Kaggle Extrovert vs. Introvert Behavior Data.
- **Features:**
  - Time_spent_Alone
  - Stage_fear
  - Social_event_attendance
  - Going_outside
  - Friends_circle_size
  - Post_frequency
  - Drained_after_socializing
  - Personality (Target)

---

## Workflow

1. **Data Cleaning**
   - Handled missing values using median (numeric) and mode (binary)
   - Label and one-hot encoding for categorical data

2. **Exploratory Data Analysis**
   - Count plots, boxplots, and histograms to compare introverts and extroverts
   - Correlation heatmaps to explore feature relationships

3. **Modeling & Evaluation**
   - Trained and tested 6 ML models:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - K-Nearest Neighbors (KNN)
     - Support Vector Machine (SVM)
     - XGBoost

4. **Evaluation Metrics**
   - Accuracy
   - Precision
   - Recall
   - F1-score
   - Cross-validation (for SVM)

---

## Best Performing Model

- **SVM** delivered the best results with:
  - **F1-score:** 0.925
  - **Accuracy:** 92.4%

---

## Visuals

The project includes various plots to showcase differences in behavior across personality types:
- Distribution plots
- Cross-tab heatmaps
- Feature correlation heatmap
- Boxplots for numeric traits

---

## Future Improvements

- Add SHAP-based feature importance visualization
- Test on real-world social behavior data (e.g., social media activity logs)
- Build a web-based personality profiler using Streamlit
