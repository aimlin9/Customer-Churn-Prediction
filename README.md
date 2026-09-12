# Customer Churn Prediction

## Project Overview

This project is part of the NexAfrica Machine Learning Internship. It focuses on building a machine learning classification model that predicts whether a customer is likely to churn, meaning stop doing business with a company, based on demographic information, account details, subscription information, service usage, contract type, tenure, and billing information.

The project follows a complete end-to-end machine learning workflow, from business understanding through data preparation, exploratory data analysis, feature engineering, model development, evaluation, optimization, and business recommendations.

## Business Problem

Customer churn is the rate at which customers stop doing business with a company. Losing a customer costs more than it appears to on the surface, because replacing that customer requires marketing and sales expense, and the company also loses the future revenue that customer would have generated over time.

The goal of this project is to build a model that calculates a probability score showing how likely each customer is to churn, rather than a simple yes or no answer. With this score, a company can group customers into risk tiers. When a customer's churn probability crosses a high threshold, the company can proactively offer discounts or incentives to retain them, while lower risk customers can be monitored with less immediate intervention.

## Dataset

The dataset used is the Telco Customer Churn dataset, containing 7,043 customer records and 21 columns, including demographic details, account information, subscribed services, contract type, billing information, and the target variable, Churn.

Raw and processed versions of the dataset are stored in the `data/` directory.

## Tools and Technologies

- Python
- Pandas
- NumPy
- Jupyter Notebook
- Matplotlib and Seaborn (Week 2 onward)
- Scikit-learn (Week 3 onward)

## Project Workflow

Business Understanding, Data Collection, Data Cleaning, Exploratory Data Analysis, Feature Engineering, Model Training, Model Evaluation, Model Optimization, Feature Importance, Business Recommendations.

## Current Progress

**Week 1: Business Understanding, Data Collection and Data Preparation (Complete)**

- Defined the business problem and project objective
- Loaded and inspected the dataset (7,043 rows, 21 columns)
- Built a data dictionary describing every feature
- Identified and resolved a data quality issue in the TotalCharges column, where 11 rows contained blank values corresponding to customers with zero tenure, resolved by converting the column to numeric type and filling missing values with 0
- Confirmed no duplicate records exist in the dataset
- Confirmed all categorical columns are free of inconsistent values, typos, or formatting issues
- Analyzed the target variable distribution: 73.5 percent of customers did not churn, 26.5 percent did churn, indicating a moderate class imbalance that will be accounted for during model evaluation and training
- Saved the cleaned dataset for use in subsequent stages

**Week 2 onward:** To be completed and documented as the project progresses.

## Exploratory Data Analysis

To be added in Week 2.

## Machine Learning Models

To be added in Week 3.

## Evaluation Metrics

To be added in Week 3.

## Key Findings

To be added as analysis progresses.

## Business Recommendations

To be added in Week 5.

## How to Run the Project

1. Clone this repository: git clone https://github.com/aimlin9/Customer-Churn-Prediction.git

2. Install the required dependencies: pip install -r requirements.txt

3. Open the notebook in the `notebooks/` directory using Jupyter Notebook or Google Colab.

## Project Structure
Customer-Churn-Prediction/
├── data/
│ ├── raw_data/
│ └── processed_data/
├── notebooks/
│ └── Week1_Business_Model.ipynb
├── src/
├── visuals/
├── README.md
└── requirements.txt
