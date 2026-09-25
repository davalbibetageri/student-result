🎓 Student Performance Analyzer — Streamlit App

This project converts the StudentsPerformance.csv exploratory-analysis notebook into an interactive Streamlit web app.
<img width="1448" height="760" alt="WhatsApp Image 2026-09-25 at 12 23 40 PM" src="https://github.com/user-attachments/assets/3aaa7c6e-0d11-44bc-b389-ad5dae3a19bd" />
<img width="1447" height="818" alt="WhatsApp Image 2026-09-25 at 12 23 41 PM" src="https://github.com/user-attachments/assets/b149537f-e4df-4324-82a5-a776c4851f98" />



Dataset

The app is based on the Kaggle Students Performance in Exams dataset used by the uploaded notebook.

The dataset contains student information such as:

gender

race/ethnicity

parental level of education

lunch

test preparation course

math score

reading score

writing score

The original notebook performs basic exploratory analysis, including data loading, distributions, correlation analysis, and scatter/density plots.

Features

1. Dataset Overview

Number of students

Number of columns

Missing-value count

Numeric feature count

Dataset preview

Column data types and unique-value information

2. Visual Analysis

Numeric score distribution

Correlation matrix

Scatter plot between selected numeric columns

3. Student Score Prediction

The original notebook does not train a machine-learning prediction model.
This Streamlit app adds a simple ML demonstration using:

Reading Score → Math Score

Algorithm:

Simple Linear Regression

Train/test split

R² score

Mean Squared Error

Predicted math score

Regression-line visualization

4. Data Explorer

View the complete dataset

Download the current dataset as CSV

Project Structure

student_streamlit_app/
│
├── app.py
├── StudentsPerformance.csv
├── requirements.txt
└── README.md


StudentsPerformance.csv
        ↓
Data Loading
        ↓
Data Cleaning
        ↓
Select Reading Score and Math Score
        ↓
Train/Test Split
        ↓
Simple Linear Regression
        ↓
Prediction
        ↓
R² Score + MSE
        ↓
Visualization

Technologies Used

Python

Streamlit

Pandas

NumPy

Matplotlib

Scikit-learn

Project Title

Student Result Prediction Using Machine Learning and Simple Linear Regression

Conclusion

This project demonstrates how student-performance data can be explored through an interactive Streamlit dashboard and how Simple Linear Regression can be used to demonstrate prediction of math scores from reading scores.
