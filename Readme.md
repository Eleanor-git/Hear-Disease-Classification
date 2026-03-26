# Heart Disease Classification

## Project Overview
This project aims to build a machine learning model to predict whether a patient has heart disease based on clinical features.

---

## Dataset
- Source: UCI Heart Disease Dataset
- Features include age, cholesterol, blood pressure, etc.
- Binary classification: presence or absence of heart disease

---

## Methodology

### 1. EDA
- Correlation matrix
- data distribution

### 2. Modelling
- Logistic Regression
- Linear SVC
- K-Nearest Neighbors
- Random Forest

### 3. Evaluation Metrics
- Recall
- F1-score
- Accuracy
- ROC-AUC

### 4. Model Selection
- Evalutation metrics
- Cross Validation

### 5. Hyper parameters tuning
- Grid Search CV

### 6. Experiment
- Decision threshold adjustment according to ROC curve

---

## Results

- Logistic Regression and Linear SVC achieved the best overall performance
- Random Forest showed strong ROC performance but signs of overfitting (100% training accuracy)
- K-Nearest Neighbors performed the worst across multiple metrics

---

## Key Insights

- Recall is critical in medical diagnosis to minimize false negatives
- Logistic Regression provides a good balance between performance and interpretability
- Overfitting must be carefully monitored, especially in tree-based models

---

## Conclusion

Among all models, Logistic Regression is selected as the final model due to its strong performance, stability, and interpretability.

---

## Future Work

- Hyperparameter tuning can be applied to mitigate the overfitting issue in the Random Forest model.
- Exploring more advanced models (e.g., XGBoost)