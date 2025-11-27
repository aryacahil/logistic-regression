---

<div align="center">

# **Logistic Regression – Student Graduation Prediction**

### *Machine Learning Project for Educational Purpose*

</div>

--- 

## 🤝 Contributors

Terima kasih kepada kontributor luar biasa ini yang telah membantu proyek ini!

* **[Arya Dwipa Mukti](https://github.com/aryacahil)** 
* **[Wisnu Adi Pradana](https://github.com/username-kontributor-lain)** *
* **[Daffa Samudra](https://github.com/daffasamudra)** 

---

## Overview

This project demonstrates how to use Logistic Regression to predict whether a student will **PASS (1)** or **FAIL (0)** based on study hours and midterm exam scores.
The project includes theory explanation, implementation, model training, and evaluation.

---

## Project Structure

```
project/
│── README.MD
│── dataset_siswa.csv
│── kerangka berpikir.png
│── logistic regression.mp4
│── logistic regression.pdf
│── logistic_regression.ipynb
```

---

## Dataset Description

| Column | Description                            |
| ------ | -------------------------------------- |
| x1     | Study hours per week                   |
| x2     | Midterm exam score (UTS)               |
| y      | Graduation result (0 = Fail, 1 = Pass) |

---

## Theory Summary

### 1. Linear Function

```
z = w1*x1 + w2*x2 + b
```

### 2. Sigmoid Function

```
h(x) = 1 / (1 + e^-z)
```

### 3. Cost Function

```
Cost = - [ y*log(h(x)) + (1 - y)*log(1 - h(x)) ]
```

### 4. Prediction Rule

* If h(x) ≥ 0.5 → PASS (1)
* If h(x) < 0.5 → FAIL (0)

---

## Tech Stack

* Python 3
* NumPy
* Pandas
* Scikit-Learn
* Matplotlib / Seaborn
* Jupyter Notebook

---

## How to Run

### 1. Install dependencies

```
pip install pandas numpy scikit-learn matplotlib seaborn
```

### 2. Launch Jupyter Notebook

```
jupyter notebook
```

### 3. Open the notebook file

```
logistic_regression.ipynb
```

---

## Notebook Workflow

1. Load dataset
2. Exploratory Data Analysis (EDA)
3. Preprocessing
4. Train logistic regression model
5. Evaluate performance
6. Make predictions

---

## Example Output

* Predicted probability: **0.87**
* Classification: **PASS**
* Accuracy: shown in notebook
* Confusion matrix: included in notebook

---

## Notes

This project is designed for beginner-friendly learning of Logistic Regression.

--- 
