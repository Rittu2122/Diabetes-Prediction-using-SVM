# Diabetes-Prediction-using-SVM
Machine learning project for diabetes prediction using the PIMA dataset. Includes data cleaning, exploratory analysis, feature correlation, and SVM classification. Evaluates performance using accuracy, confusion matrix
# Diabetes Prediction using PIMA Dataset

## Overview
This project builds a machine learning model to predict diabetes using the PIMA Indians Diabetes Dataset. It includes data preprocessing, exploratory analysis, and classification using Support Vector Machine (SVM).

---

## Workflow
- Data Cleaning (handling zero/invalid values)
- Exploratory Data Analysis (EDA)
- Feature Correlation Analysis
- Model Training (SVM)
- Model Evaluation (Accuracy, Confusion Matrix)

---

## Results
- **Accuracy:** 83.12%
- **Confusion Matrix:**
- [[49 4]
  [ 9 15]]
  
### Interpretation:
- Correctly classified:
- 49 Non-diabetic cases  
- 15 Diabetic cases  
- Misclassified:
- 9 Diabetic cases (False Negatives)
- 4 Non-diabetic cases (False Positives)

---

## Limitations
- Small dataset size  
- Possible class imbalance  
- Linear SVM may not capture complex patterns  
- Some diabetic cases are still missed (False Negatives)

---

## Future Work
- Improve recall using hyperparameter tuning  
- Use advanced models (Random Forest, XGBoost)  
- Apply feature engineering  
- Use larger datasets for better generalization  

---


## Conclusion
The model achieves good performance with 83.12% accuracy. However, improvement is needed in detecting all diabetic cases, which is critical in medical applications.
