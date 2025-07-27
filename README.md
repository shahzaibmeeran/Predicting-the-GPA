# Predicting-the-GPA
# 📚 Shahzaib_Assignment_Project_3

This project focuses on predicting students' GPA based on their academic performance data using multiple regression algorithms in Python.

---

## 📌 Objective

To build and evaluate machine learning models that can predict a student's GPA using input features such as study hours, attendance rate, extra-curricular activities, and previous grades.

---

## 🧠 Algorithms Used

The following regression models were applied:

- 🔹 Linear Regression
- 🔹 Support Vector Regressor (SVR)
- 🔹 Stochastic Gradient Descent (SGD)
- 🔹 Multi-layer Perceptron (MLP Regressor)
- 🔹 Decision Tree Regressor

---

## 🧼 Preprocessing Steps

- Handled missing values (if any)
- Encoded categorical variables (Gender, ExtraActivities)
- Feature scaling using `StandardScaler`
- Train-test split (80% training / 20% testing)

---

## 📊 Evaluation Metrics

Each model was evaluated using the following error metrics:

- **MAE (Mean Absolute Error)**  
- **MSE (Mean Squared Error)**  
- **RMSE (Root Mean Squared Error)**

> 📉 Models with the **lowest RMSE** were considered the most accurate.

---

## 📈 Visualizations

- Correlation Heatmap of all features
- Distribution plot of GPA
- Bar chart comparing performance (MAE, MSE, RMSE) across all models

---

## 🧪 Dataset Features

| Feature           | Description                         |
|------------------|-------------------------------------|
| Gender           | Male or Female                      |
| StudyHours       | Average study hours per week        |
| AttendanceRate   | Attendance percentage (50–100%)     |
| ExtraActivities  | Yes/No participation in activities  |
| PreviousGrades   | GPA from previous semester
