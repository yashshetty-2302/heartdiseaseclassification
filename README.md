# heartdiseaseclassification
# Heart Disease Classification Project

## Overview
This project analyzes heart disease data to predict whether a patient has heart disease using various machine learning models. The analysis includes exploratory data analysis (EDA), model training, and evaluation of different classification algorithms.

## Dataset
The dataset contains 303 patient records with 13 features including:
- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- And other medical indicators

## Key Findings
- Logistic Regression performed best with 88.5% accuracy
- Age and maximum heart rate showed strong correlation with heart disease
- Chest pain type 2 showed highest correlation with heart disease presence
- Male patients showed higher heart disease frequency

## Models Evaluated
1. Logistic Regression (88.5% accuracy)
2. Random Forest Classifier (83.6% accuracy)
3. K-Nearest Neighbors (68.9% accuracy)

## Tools & Technologies
- Python
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualization
- Scikit-learn for machine learning models

## Model Optimization
- Used GridSearchCV and RandomizedSearchCV for hyperparameter tuning
- Cross-validation metrics:
  - Accuracy: 92.1%
  - Precision: 82.1%
  - Recall: 92.1%
  - F1 Score: 86.7%

## Visualizations
The project includes various visualizations:
- Correlation heatmaps
- Feature importance plots
- ROC curves
- Confusion matrices
- Distribution plots for key features

## Future Improvements
- Collect more data for better model training
- Try additional machine learning algorithms
- Feature engineering for better predictions
- Deploy model as a web application

## How to Run
1. Clone this repository
2. Install required packages`
3. Open and run the Jupyter notebook

## Author
Yash Shetty
