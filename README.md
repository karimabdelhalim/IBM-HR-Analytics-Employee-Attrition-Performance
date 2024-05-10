# IBM HR Analytics - Employee Attrition and Performance

## Overview
This project aims to uncover the factors that lead to employee attrition using the IBM HR Analytics Employee Attrition & Performance dataset. The dataset contains various features related to employees, such as job role, distance from home, education, monthly income, and whether they have left the company (attrition).

## Contents
1.  The dataset contains employee information from the [IBM HR Analytics Employee Attrition & Performance dataset](https://www.kaggle.com/pavansubhasht/ibm-hr-analytics-attrition-dataset).

2. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
3. [Statistical Tests](#statistical-tests)
4. [Modeling](#modeling)
5. [Results and Insights](#results-and-insights)

## Dataset Description
- The dataset contains employee information from the IBM HR Analytics Employee Attrition & Performance dataset.
- Features include job role, distance from home, education, monthly income, years at company, etc.
- The target variable is 'Attrition', indicating whether the employee has left the company (Yes/No).

## Exploratory Data Analysis (EDA)
- Explored the distribution of features such as distance from home by job role and attrition.
- Investigated relationships between average monthly income, education, and attrition.
- Identified key factors contributing to employee attrition through visualizations and summary statistics.

## Statistical Tests
- Conducted statistical tests (chi2, ANOVA) to analyze the significance of various factors on employee attrition.
- Tested hypotheses regarding the impact of different variables on attrition rates.

## Modeling
- Applied machine learning models (catboost and neural network) to predict employee attrition.
- Evaluated model performance using metrics such as accuracy, precision, recall, and F1 score.
- Tuned hyperparameters to improve model performance.

## Results and Insights
- Found that distance from home and job role have a significant impact on employee attrition.
- Discovered that employees with lower education levels tend to have higher attrition rates.
- Identified key features contributing to employee attrition and provided actionable insights for management.

## Dependencies
- Python 3
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- catboost
- pytorch
- StatsModels



