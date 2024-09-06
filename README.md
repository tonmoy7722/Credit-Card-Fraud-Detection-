<div align="center"><img src="https://github.com/tonmoy7722/Credit-Card-Fraud-Detection-/blob/main/credit%20card.jpg"></div>

 # Credit Card Fraud Detection

This project aims to build a predictive model to detect fraudulent credit card transactions using machine learning techniques. The dataset used in this project contains transaction details, and the target is to classify transactions as either fraud or non-fraud.

## Project Workflow

1. **Data Loading and Preprocessing**
   - Load the dataset and clean the data.
   - Convert date and time fields to appropriate formats.
   - Encode categorical variables using Label Encoding and WOE Encoding.

2. **Data Balancing**
   - Address class imbalance through downsampling of the majority class.

3. **Feature Scaling**
   - Standardize the features using `StandardScaler`.

4. **Model Training**
   - Train multiple machine learning models:
     - Logistic Regression
     - Decision Tree
     - Random Forest
     - Gaussian Naive Bayes
     - Support Vector Machine (SVC)
     - XGBoost Classifier

5. **Evaluation**
   - Compare the models using accuracy and visualize the results in bar charts.

## Visualizations

- Gender distribution of fraud and non-fraud cases.
- Fraud distribution across transaction hours.
- Original vs. downsampled class distributions.
- Model accuracy comparison.

## Libraries Used

- `pandas`
- `numpy`
- `seaborn`
- `matplotlib`
- `category_encoders`
- `scikit-learn`
- `xgboost`

## How to Run

1. Install required dependencies:
   ```bash
   pip install category_encoders scikit-learn xgboost
   ```
2. Load the dataset and follow the workflow outlined in the code.

## Author

Developed by [Tonmoy Day Sarkar](https://tonmoy7722.github.io/Tonmoy-Portfolio/) as part of a machine learning project on fraud detection.
