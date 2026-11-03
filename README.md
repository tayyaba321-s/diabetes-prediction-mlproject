
# Diabetes Prediction Using Machine Learning

## Project Overview
This project focuses on predicting diabetes using machine learning techniques based on patient health indicators. The objective is to explore health-related factors associated with diabetes and evaluate different classification models.

## Dataset Description
The dataset contains patient health information, including:

- Gender
- Age
- Hypertension
- Heart disease
- Smoking history
- Body Mass Index (BMI)
- HbA1c level
- Blood glucose level

A subset of 3,000 records was used for the analysis in this notebook.

## Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Project Workflow

### 1. Data Exploration and Preprocessing
- Dataset inspection
- Exploratory Data Analysis (EDA)
- Data visualization
- Categorical feature encoding using One-Hot Encoding
- Numerical feature scaling
- Train-test split (80:20)

### 2. Machine Learning Models
The following classification models were evaluated:

- Logistic Regression
- Random Forest
- Gradient Boosting

### 3. Model Evaluation
Model performance was evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC
  ### 4. Training and Testing

The dataset was divided into training and testing sets:

- Training set: 2,400 records (80%)
- Testing set: 600 records (20%)
- Number of features: 12

Feature scaling was performed before model training.

## 5. Results and Observations

- Random Forest achieved the highest accuracy (96.67%).
- Random Forest achieved the highest precision (94.74%) and F1-score (78.26%).
- Gradient Boosting achieved the highest ROC-AUC score (97.55%).
- Logistic Regression achieved an accuracy of 95.50%.

Based on these evaluation metrics, Random Forest showed the strongest balance of precision and F1-score, while Gradient Boosting achieved the best ROC-AUC.

## Model Performance

Model	Accuracy	    Precision	Recall	F1-score	ROC-AUC
Logistic Regression	95.50%	  84.62%	61.11%	  70.97%	96.26%
Random Forest     	96.67%	  94.74%	66.67%	  78.26%	95.87%
Gradient Boosting  	96.50%	  92.31%	66.67%	  77.42%	97.55%
The reported results show that Random Forest achieved the highest accuracy, while Gradient Boosting achieved the highest ROC-AUC of 97.55%.

## Conclusion
This project demonstrates how machine learning classification techniques can be applied to diabetes prediction using patient health indicators. The evaluated models provide a comparison of predictive performance and highlight the potential usefulness of health-related features in diabetes risk prediction.

## Repository Structure

```text
Diabetes-Prediction-ML/
│
├── Data/
│   └── diabetes_prediction_dataset.csv
│
├── TnT.ipynb
└── README.md
```

## Disclaimer
This project is for educational and research purposes only. It is not intended to replace professional medical advice or clinical diagnosis.
