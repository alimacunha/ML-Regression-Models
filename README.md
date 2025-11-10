# Machine Learning Models: Regression & Classification

This repository contains two machine learning projects implemented in separate notebooks:

1. **USA Housing Price Prediction** – predicting housing prices using **Linear Regression** and **Polynomial Regression (Degree 2)**.  
2. **Heart Attack Classification Prediction** – predicting the likelihood of heart attack occurrence using **Logistic Regression**.

---

## 1. USA Housing Price Prediction

This project focuses on predicting housing prices in the USA using regression techniques.  
The dataset contains various housing features such as average area income, house age, number of rooms, number of bedrooms, and area population.  

### Project Overview
- Implemented **Linear Regression** and **Polynomial Regression (Degree 2)**.  
- Evaluated models using standard regression metrics:
  - Mean Absolute Error (MAE)  
  - Mean Squared Error (MSE)  
  - Root Mean Squared Error (RMSE)  
  - R² Score  

### Results

#### Linear Regression
**Testing Set Evaluation**
- MAE: `0.0319`  
- MSE: `0.0016`  
- RMSE: `0.03996`  
- R² Score: `0.9227`  

**Training Set Evaluation**
- MAE: `0.0335`  
- MSE: `0.0017`  
- RMSE: `0.04153`  
- R² Score: `0.9168`  

#### Polynomial Regression (Degree 2)
**Testing Set Evaluation**
- MAE: `0.03185`  
- MSE: `0.00160`  
- RMSE: `0.03998`  
- R² Score: `0.9226`  

### Conclusion
- Both Linear and Polynomial Regression models achieved **very similar performance**, with R² scores above **0.92** on the testing set.  
- Linear Regression performed slightly better on the training set, while Polynomial Regression was comparable but did not significantly improve prediction accuracy.  
- Given the small difference, **Linear Regression is sufficient** for this dataset, as it is simpler and less prone to overfitting.  

---

## 2. Heart Attack Classification Prediction

This project applies **Logistic Regression** to classify whether a patient is at risk of a heart attack based on clinical and lifestyle features.  
The dataset includes attributes such as age, sex, chest pain type, resting blood pressure, cholesterol levels, fasting blood sugar, resting ECG results, maximum heart rate achieved, exercise-induced angina, ST depression, slope of ST segment, number of major vessels, and thalassemia status.

### Project Overview
- Implemented **Logistic Regression** for binary classification (heart attack risk: yes/no).  
- Evaluated model performance using classification metrics:
  - Accuracy  
  - Precision  
  - Recall  
  - F1 Score  
  - Confusion Matrix  

### Results
- The logistic regression model achieved strong performance, with balanced precision and recall across both classes.  
- Confusion matrix analysis showed the model correctly identified a high proportion of positive cases (patients at risk), while maintaining good accuracy on negative cases.  
- Overall, the model demonstrates that logistic regression is effective for medical risk prediction tasks where interpretability and simplicity are important.  

### Conclusion
- Logistic Regression provided a clear and interpretable model for heart attack risk classification.  
- The model’s performance metrics indicate it can serve as a baseline for further exploration of more complex classifiers (e.g., Random Forest, SVM, Neural Networks).  
- For practical applications, logistic regression remains valuable due to its transparency and ease of deployment.  

---

## Repository Structure
- `USA-Housing-Price-Prediction.ipynb` – Notebook for regression models on housing dataset.  
- `Logistic-Regression-Heart-Attack-Prediction.ipynb` – Notebook for classification model on heart attack dataset.  

