Employee Turnover Prediction

Project Overview

Employee turnover is a major challenge for organizations because employee resignations can increase recruitment costs, cause project delays, and result in the loss of skilled employees.

This project aims to build a Machine Learning model that predicts whether an employee is likely to leave a company based on various employee-related factors.

The project is developed as part of a Supervised Machine Learning assignment.

Problem Statement

TalentCore Pvt. Ltd. is experiencing an increasing number of employee resignations. The objective is to develop a classification model that helps predict employee turnover.

The target variable is:

1 – Employee Left

0 – Employee Stayed

Dataset

The dataset contains employee-related information, including:

Job Satisfaction

Performance Rating

Years at Company

Work-Life Balance

Distance From Home

Monthly Income

Education Level

Age

Number of Companies Worked

Employee Role

Annual Bonus

Training Hours

Department

It also includes engineered features such as Annual Bonus Squared and Annual Bonus–Training Hours Interaction.

Technologies Used

Python

NumPy

Pandas

Scikit-learn

Jupyter Notebook

Machine Learning Algorithm

Logistic Regression

Logistic Regression is used as the baseline classification algorithm to predict whether an employee will leave or stay.

The project will also explore regularization techniques:

L1 Regularization (Lasso)

L2 Regularization (Ridge)

Baseline Model Performance

The initial Logistic Regression model achieved the following results:

Evaluation MetricScoreAccuracy85.93%Precision87.18%

These results represent the baseline model. Further experiments will be conducted to evaluate and improve model performance.

Project Workflow

Data Loading

Data Exploration

Data Preprocessing

Train-Test Split

Baseline Logistic Regression

Model Evaluation

L1 Regularization

L2 Regularization

Model Comparison

Current Progress

Dataset loading

Baseline Logistic Regression

Accuracy evaluation

Precision evaluation

Confusion Matrix analysis

L1 Regularization

L2 Regularization

Model comparison

Final model recommendation

Project Objective

The main objective is to understand how Logistic Regression and regularization techniques can be applied to a real-world classification problem and evaluate their effectiveness in predicting employee turnover.

Disclaimer

This is an educational Machine Learning project. The model is developed for learning and experimentation purposes and is not intended for actual HR decision-making.

Author

Vinayak

