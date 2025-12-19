# Diabetes-Prediction-Model

## Project Overview
This project predicts diabetes using a dataset from Kaggle. The goal is to classify patients as diabetic or non-diabetic based on several health-related features.


## Key Steps

1. **Data Preprocessing & Feature Engineering**
   - Handled missing/zero-like values.
   - Added new feature: `BMI_Age = BMI * Age`.

2. **Handling Imbalanced Data**
   - Applied **SMOTE** to balance the diabetic class.

3. **Model Training**
   - Models trained:
     - Logistic Regression
     - K-Nearest Neighbors (KNN)
     - Decision Tree
     - Random Forest
     - XGBoost

4. **Evaluation Metrics**
   - Accuracy
   - Recall for diabetic class (Class 1)
   - Confusion Matrix
   - Feature Importance

5. **Feature Importance**
   - Visualized which features contributed most to predictions.

---

## Final Model

**Random Forest** was selected as the final model based on its performance.

- **Accuracy:** 77.9%  
- **Recall (Diabetic class):** 76%  
