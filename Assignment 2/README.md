# CAP182 Assignment 2

## Student Information

| Field | Details |
|---------|---------|
| Student Name | Hileni Metaramo |
| Institution | STADIO Higher Education |
| Module | CAP182 – Data Science Capstone |
| Assignment | Assignment 2 |

## Project Overview

This repository contains the complete solution for Assignment 2. The project follows the end-to-end Data Science process including:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Machine Learning model development
- Model evaluation and comparison
- Results interpretation and reporting

The objective is to build predictive models using the provided dataset and evaluate their performance using appropriate metrics.

## Repository Structure

```text
CAP182-Assignment2/
│
├── data/
│   ├── raw/
│   └── processed/
│
├── notebooks/
│   ├── 01_eda.ipynb
│   ├── 02_preprocessing.ipynb
│   ├── 03_model_training.ipynb
│   └── 04_evaluation.ipynb
│
├── scripts/
│   ├── data_preprocessing.py
│   ├── exploratory_analysis.py
│   ├── model_training.py
│   └── model_evaluation.py
│
├── models/
│
├── results/
│   ├── figures/
│   ├── metrics/
│   └── reports/
│
├── requirements.txt
└── README.md
```

## Dataset

The dataset provided for Assignment 2 was used to develop and evaluate machine learning models.

### Data Preparation Steps

- Missing value treatment
- Duplicate removal
- Categorical encoding
- Feature scaling
- Data validation

## Exploratory Data Analysis (EDA)

EDA was performed to:

- Understand dataset characteristics
- Identify feature distributions
- Detect outliers
- Analyse correlations
- Discover patterns and trends

Visualisations were generated using Matplotlib and Seaborn.

## Machine Learning Models

The following workflow was followed:

1. Data preprocessing
2. Feature selection
3. Model training
4. Model evaluation
5. Performance comparison

Models were assessed using suitable evaluation metrics depending on the prediction task.

## Evaluation Metrics

### Classification

- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

### Regression

- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

## Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/CAP182-Assignment2.git
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Environment

**Windows**

```bash
venv\Scripts\activate
```

**Linux/Mac**

```bash
source venv/bin/activate
```

### Install 

