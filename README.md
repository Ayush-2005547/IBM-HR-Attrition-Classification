# Attrition Prediction Using Logistic Regression

This project uses logistic regression to predict employee attrition using the IBM HR Analytics dataset. It involves binary classification, evaluation metrics, threshold tuning, and sigmoid function visualization.

## Objective

To build a binary classifier that predicts whether an employee is likely to leave the organization based on personal and workplace-related features.

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Dataset

IBM HR Analytics Employee Attrition Dataset (https://posit-academy.quarto.pub/data-gallery/academy-datasets/employee-attrition/index.htm) 
Contains 1,470 employee records with features like job role, satisfaction level, income, etc.  
Target column: `Attrition` (Yes/No)

## Project Workflow

1. **Data Cleaning & Preprocessing**
   - Handled missing values
   - Converted categorical features using one-hot encoding
   - Encoded the target variable

2. **Feature Scaling**
   - Standardized numerical columns using `StandardScaler`

3. **Train-Test Split**
   - 80% training and 20% testing

4. **Model Building**
   - Trained a logistic regression model

5. **Model Evaluation**
   - Used confusion matrix, precision, recall, F1-score, ROC-AUC
   - Explored precision-recall trade-offs by tuning thresholds

6. **Sigmoid Function Visualization**
   - Plotted and annotated the sigmoid function to explain decision boundaries

## Best Performing Threshold

After testing multiple thresholds, a value of **0.40** was found to give the best balance between precision and recall. Recall was prioritized due to the business context of avoiding false negatives.

## Key Concepts Demonstrated

- Binary Classification
- Logistic Regression
- Evaluation Metrics
- Threshold Tuning
- Sigmoid Function Behavior


