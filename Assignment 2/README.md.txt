# CAP182 Part B: Predictive Modelling for Hospital Capacity Planning

## Student Information

Name: Hileni Metaramo

Student Number: 21820531

Module: CAP182 – Capstone Project

Project Title: Predicting Patient Length of Stay Using Machine Learning

--------------------------------------------------

## Project Overview

This project uses the MIMIC-IV healthcare dataset to predict patient Length of Stay (LOS). Accurate LOS prediction can help hospitals improve capacity planning, bed allocation, workforce scheduling, and resource utilisation.

The project follows a structured machine learning workflow consisting of:

1. Data Preprocessing
2. Feature Engineering
3. Random Forest Regression
4. XGBoost Regression

--------------------------------------------------

## Documentation

Detailed documentation is provided in the following files:

Preprocessing.MD

FeatureEngineering.MD

Model1.MD

Model2.MD

--------------------------------------------------

## Documentation Links

Data Preprocessing

See Preprocessing.MD

This file explains:

- Data cleaning
- Duplicate removal
- Missing value handling
- Feature scaling
- How to run preprocessing.py

--------------------------------------------------

Feature Engineering

See FeatureEngineering.MD

This file explains:

- Length of Stay calculation
- Time-based feature generation
- One-Hot Encoding
- Creation of engineered variables
- How to run feature_engineering.py

--------------------------------------------------

Model 1

See Model1.MD

Random Forest Regression

This file explains:

- Model purpose
- Hyperparameters
- Training process
- Evaluation metrics
- How to run train_random_forest.py

--------------------------------------------------

Model 2

See Model2.MD

XGBoost Regression

This file explains:

- Model purpose
- Hyperparameters
- Training process
- Evaluation metrics
- How to run train_xgboost.py

--------------------------------------------------

## Repository Structure

CAP182_Project/

README.md

Preprocessing.MD

FeatureEngineering.MD

Model1.MD

Model2.MD

scripts/

    preprocessing.py

    feature_engineering.py

    train_random_forest.py

    train_xgboost.py

data/

    raw/

    processed/

models/

requirements.txt

--------------------------------------------------

## Workflow

mimic_admissions.csv

↓

preprocessing.py

↓

cleaned_data.csv

↓

feature_engineering.py

↓

engineered_data.csv

↓

Random Forest Regression

↓

XGBoost Regression

--------------------------------------------------

## Installation

Install all required libraries:

pip install -r requirements.txt

--------------------------------------------------

## Script Execution Order

Step 1

python scripts/preprocessing.py

Output:

data/processed/cleaned_data.csv

--------------------------------------------------

Step 2

python scripts/feature_engineering.py

Output:

data/processed/engineered_data.csv

--------------------------------------------------

Step 3

python scripts/train_random_forest.py

Output:

models/random_forest_model.pkl

--------------------------------------------------

Step 4

python scripts/train_xgboost.py

Output:

models/xgboost_model.pkl

--------------------------------------------------

## Evaluation Metrics

The models are evaluated using:

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score

These metrics are appropriate for the regression task of predicting patient Length of Stay.

--------------------------------------------------

## Addressing Lecturer Feedback

The previous submission received feedback regarding:

- Lack of One-Hot Encoding
- Feature engineered variables not being used by the models
- Incorrect file paths
- Documentation not matching implementation

These issues have been corrected by:

✓ Applying One-Hot Encoding using pd.get_dummies()

✓ Saving engineered features to engineered_data.csv

✓ Training both models using engineered_data.csv

✓ Using consistent file paths across all scripts

✓ Aligning documentation with the implemented workflow

--------------------------------------------------

## Conclusion

This project demonstrates the application of machine learning techniques to healthcare analytics. By predicting patient Length of Stay, hospitals can make more informed decisions regarding staffing, bed allocation and operational planning.

Random Forest Regression and XGBoost Regression are implemented and compared using the same processed and engineered dataset to determine the most effective predictive model.