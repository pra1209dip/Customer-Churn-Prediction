# Customer Churn Prediction using Logistic Regression

## Project Overview

This machine learning project predicts whether a telecom customer is likely to discontinue their subscription using Logistic Regression.

The objective is to identify customers at risk of leaving and support data-driven customer retention strategies.

## Dataset

- Source: IBM Telco Customer Churn (Kaggle)
- Original records: 7,043
- Records after cleaning: 7,032
- Original features: 20
- Target variable: Churn (Yes/No)

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook

## Project Workflow

1. Data Collection
2. Exploratory Data Analysis
3. Data Cleaning
4. One-Hot Encoding
5. Train-Test Split
6. Feature Scaling
7. Logistic Regression Model Training
8. Model Evaluation
9. Customer Churn Prediction
10. Model Serialization

## Model Performance

| Metric | Result |
|---|---|
| Algorithm | Logistic Regression |
| Accuracy | 80.38% |
| ROC-AUC Score | 0.8357 |
| Training Data | 80% |
| Testing Data | 20% |

## Visualizations

- Customer Churn Distribution
- Confusion Matrix
- ROC Curve
- Feature Importance

## Prediction System

The model estimates customer churn probability based on customer attributes, including tenure, monthly charges and total charges. Remaining features use representative median values for demonstration purposes.

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open the Jupyter Notebook.
4. Run all cells sequentially.
5. Enter customer details to generate a prediction.

## Future Improvements

- Hyperparameter tuning
- Handling class imbalance
- Comparison with other classification algorithms
- Deployment using Streamlit

## Conclusion

The Logistic Regression model achieved 80.38% test accuracy and a ROC-AUC score of 0.8357, demonstrating good ability to distinguish between churn and non-churn customers.