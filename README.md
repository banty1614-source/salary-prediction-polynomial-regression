# 💰 Salary Prediction using Polynomial Regression

A Machine Learning project built using **Python** and **Scikit-learn** to understand and implement **Polynomial Regression** for modeling non-linear relationships between years of experience and salary.

---

## 📌 Project Overview

This project demonstrates how Polynomial Regression can be used when a simple linear relationship is insufficient to describe the data.

Using a dataset containing employees' years of experience and corresponding salaries, the model learns a polynomial relationship to predict future salaries more accurately.

---

## 🎯 Problem Statement

In many real-world scenarios, the relationship between variables is not always linear.

As employees gain more experience, salary growth may accelerate rather than increase at a constant rate.

The objective of this project is to build a model capable of capturing such **non-linear patterns**.

---

## 📂 Dataset Information

For learning purposes, a small dataset was used.

| Experience (Years) | Salary |
| ------------------ | ------ |
| 1                  | 45     |
| 2                  | 50     |
| 3                  | 60     |
| 4                  | 80     |
| 5                  | 110    |
| 6                  | 150    |

### Features

* Experience (Years)

### Target Variable

* Salary

---

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Jupyter Notebook

---

## 🧠 Machine Learning Concepts Used

* Polynomial Regression
* Feature Engineering
* Polynomial Features
* Model Training
* Salary Prediction
* Overfitting
* Non-linear Relationships

---

## 📈 Why Polynomial Regression?

Linear Regression assumes a straight-line relationship between features and the target variable.

However, salary growth often follows a curved trend.

Polynomial Regression addresses this limitation by introducing higher-degree terms such as:

* x²
* x³

This allows the model to capture more complex relationships.

---

## ⚙️ Project Workflow

```text
Create Dataset
      ↓
Define Features and Label
      ↓
Generate Polynomial Features
      ↓
Train Linear Regression Model
      ↓
Make Predictions
      ↓
Interpret the Polynomial Equation
      ↓
Understand Overfitting
```

---

## 🤖 Algorithm Used

### Polynomial Regression (Degree = 2)

Polynomial Regression transforms the original features into polynomial features and then applies Linear Regression.

The general form of the model is:

```
y = b₀ + b₁x + b₂x²
```

---

## 📊 Model Results

### Predicted Salary for 7 Years of Experience

```
197.5
```

### Learned Polynomial Equation

```
Salary = 52.5 − 11.16 × Experience + 4.55 × Experience²
```

---

## 🔍 Key Observations

* Salary growth was not linear.
* Polynomial Regression captured the accelerating salary trend effectively.
* Higher polynomial degrees can increase model complexity.
* Choosing an excessively large degree may lead to overfitting.

---

## 📚 What I Learned

Through this project, I learned:

* The limitations of Linear Regression
* How Polynomial Regression works
* How to generate polynomial features using `PolynomialFeatures`
* Why Polynomial Regression is still considered a linear model
* How to extract and interpret polynomial equations
* The concept of overfitting and its impact on model performance

---

## ⚠️ Limitations

* The dataset used is very small and intended primarily for educational purposes.
* Results obtained from this model should not be used for real-world salary predictions.
* A larger dataset would be required to build a production-level system.

---

## 🔮 Future Improvements

* Use a larger, real-world salary dataset
* Compare Degree 2 and Degree 3 models
* Visualize Linear vs Polynomial Regression curves
* Evaluate the model using regression metrics
* Experiment with regularization techniques

---

## 📁 Project Structure

```text
salary-prediction-polynomial-regression/
│
├── Salary_Prediction.ipynb
├── README.md
└── requirements.txt
```

---

## 📦 Requirements

```
pandas
numpy
scikit-learn
jupyter
```

---

## 👨‍💻 Author

**Banty Kumar**

Electrical Engineering Undergraduate at NIT Patna.

Currently learning Machine Learning through practical projects and hands-on implementation.

---

## ⭐ Acknowledgement

This project was developed as part of my Machine Learning learning journey to strengthen my understanding of regression techniques and feature engineering.

Feedback and suggestions are always welcome.
