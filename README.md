# Customer Churn Prediction

## Overview
This project predicts customer churn using machine learning techniques. The goal is to identify customers who are likely to stop using a service, enabling proactive retention strategies.

## Dataset
The dataset used is `ChurnCustomerPrediction.csv`, which contains customer information such as tenure, monthly charges, and churn status.

## Methodology
1. **Data Preprocessing:** Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Exploratory Data Analysis (EDA):** Visualizing data distributions and correlations.
3. **Model Training:** Using algorithms like Random Forest, Logistic Regression, and KNN.
4. **Evaluation:** Metrics include accuracy, precision, recall, and F1-score.

## Results
- Best model: **Random Forest** with 81% accuracy.
- Key features: **Tenure**, **Monthly Charges**, and **Contract Type**.

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/Frankly/Customer_Churn_Prediction.git


2. Install dependencies:
    ```bash:
    pip install -r requirements.txt
    
3. Open the Jupyter Notebook:
    ```bash:
    jupyter notebook notebooks/ChurnCustomerPrediction_prediction.ipynb
    