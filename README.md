📘 Logistic Regression – Student Graduation Prediction

This project implements Logistic Regression to predict whether a student will PASS (1) or FAIL (0) based on several features from the dataset.
The model is created for learning purposes, focusing on understanding the basic theory and implementation of Logistic Regression.

📂 Project Structure
📁 project/
│── logistic_regression.ipynb
│── dataset_siswa.csv
│── README.md

📊 Dataset Description

The file dataset_siswa.csv contains:

x1 → Study hours per week

x2 → Midterm exam score (UTS)

y → Graduation status (0 = Fail, 1 = Pass)

The goal is to train a model that predicts y.

🔍 Project Objectives

Understand the concept of Logistic Regression

Implement the sigmoid function and cost function

Train a binary classification model

Perform prediction and evaluate the model

🧠 Logistic Regression Theory
1. Linear Function
𝑧
=
𝑤
1
𝑥
1
+
𝑤
2
𝑥
2
+
𝑏
z=w
1
	​

x
1
	​

+w
2
	​

x
2
	​

+b
2. Sigmoid Function (Hypothesis)
ℎ
(
𝑥
)
=
1
1
+
𝑒
−
𝑧
h(x)=
1+e
−z
1
	​


The sigmoid outputs a probability between 0 and 1.

3. Cost Function
𝐶
𝑜
𝑠
𝑡
=
−
[
𝑦
log
⁡
(
ℎ
(
𝑥
)
)
+
(
1
−
𝑦
)
log
⁡
(
1
−
ℎ
(
𝑥
)
)
]
Cost=−[ylog(h(x))+(1−y)log(1−h(x))]

Used to measure model error — lower cost means better performance.

🛠️ Technologies Used

Python 3

Jupyter Notebook

Pandas

NumPy

Scikit-Learn

Matplotlib / Seaborn (optional)

▶️ How to Run the Project

Install dependencies:

pip install pandas numpy scikit-learn matplotlib seaborn


Launch Jupyter Notebook:

jupyter notebook


Open:

logistic_regression.ipynb


Run each cell step-by-step.

📈 Notebook Workflow

Load dataset

Perform Exploratory Data Analysis (EDA)

Preprocess data

Train Logistic Regression model

Evaluate performance (accuracy & confusion matrix)

Make predictions

🎯 Main Outputs

Predicted probability of passing

Pass / Fail classification

Evaluation metrics and visualization

📌 Notes

This project is designed for educational purposes, helping students understand how Logistic Regression works both mathematically and programmatically.
