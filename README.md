Logistic Regression – Student Graduation Prediction
Machine Learning Project for Educational Purpose
Overview

This project demonstrates how to use Logistic Regression to predict whether a student will PASS (1) or FAIL (0) based on study hours and midterm exam scores.
The project includes theory explanation, implementation, model training, and evaluation.

Project Structure
project/
│── logistic_regression.ipynb
│── dataset_siswa.csv
│── README.md

Dataset Description
Column	Description
x1	Study hours per week
x2	Midterm exam score (UTS)
y	Graduation result (0 = Fail, 1 = Pass)
Theory Summary
1. Linear Function
z = w1*x1 + w2*x2 + b

2. Sigmoid Function
h(x) = 1 / (1 + e^-z)

3. Cost Function
Cost = - [ y*log(h(x)) + (1 - y)*log(1 - h(x)) ]

4. Prediction Rule

If h(x) ≥ 0.5 → PASS (1)

If h(x) < 0.5 → FAIL (0)

Tech Stack

Python 3

NumPy

Pandas

Scikit-Learn

Matplotlib / Seaborn

Jupyter Notebook

How to Run
1. Install dependencies
pip install pandas numpy scikit-learn matplotlib seaborn

2. Launch Jupyter Notebook
jupyter notebook

3. Open the file
logistic_regression.ipynb

Notebook Workflow

Load dataset

Exploratory Data Analysis (EDA)

Preprocessing

Build logistic regression model

Evaluate model performance

Predict student graduation

Example Output

Predicted probability: 0.87

Classification: PASS

Accuracy and confusion matrix included in notebook

Notes

This project is created for educational purposes and aims to make Logistic Regression easy to understand for beginners.
