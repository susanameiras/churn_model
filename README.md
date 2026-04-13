# Scope

This project was created in the academic year 2021-2022 as part of the Computational Statistics Modeling specialization course at the University of Porto.

# Telco Customer Churn Prediction

This project demonstrates a logistic regression model to predict customer churn for a telecommunications company using the IBM Telco Customer Churn dataset.

## Overview

The notebook `TelcoCustomerChurn_ExampleLogReg_R.ipynb` implements a complete machine learning pipeline including:
- Exploratory data analysis
- Data preprocessing and feature engineering
- Logistic regression model training
- Stepwise model refinement
- Model evaluation and interpretation


## Dataset

The dataset used is the [IBM Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn/data) from Kaggle, containing approximately 7,000 customer records with 20 features.

**Location:** `data/WA_Fn-UseC_-Telco-Customer-Churn.csv`

**Features include:**
- Customer demographics (gender, age range, partners, dependents)
- Services subscribed (phone, internet, security, etc.)
- Account information (tenure, contract type, payment method, charges)
- Churn status (target variable)

## Requirements

- R (version 4.0 or higher recommended)
- Jupyter Notebook or RStudio
- Required R packages:
  - caret
  - car
  - pROC
  - ggplot2
  - ggcorrplot
  - ggstatsplot
  - dplyr
  - tidyr
  - ResourceSelection

Install packages using:
```r
install.packages(c("caret", "car", "pROC", "ggplot2", "ggcorrplot", "ggstatsplot", "dplyr", "tidyr", "ResourceSelection"))
```

## Usage

1. Ensure the dataset is in the `data/` directory
2. Open `TelcoCustomerChurn_ExampleLogReg_R.ipynb` in Jupyter Notebook or VS Code
3. Run the cells sequentially to execute the analysis

## Results

The final logistic regression model achieves:
- **AUC: ~0.85** on the test set
- Key predictors of churn: contract type, tenure, internet service type, and monthly charges

## License

This project uses the IBM Telco Customer Churn dataset. Please refer to the original dataset license and terms of use.

## Author

Susana Meiras
