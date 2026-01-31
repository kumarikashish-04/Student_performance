Student Performance Prediction using Machine Learning


📌 Project Overview

This project focuses on predicting student academic performance using Machine Learning techniques.
We trained two different regression models on the same dataset with different feature sets to analyze how previous academic performance impacts prediction accuracy.

The goal is to:

Compare models with and without previous marks

Evaluate performance using R² Score

Visualize results and analyze errors

Understand feature importance in student performance prediction
📊 Features Used
Feature Name	Description
Study_Hours	Average hours studied per day
Attendance	Percentage of attendance
Parental_Education	Education level of parents
Internet_Access	Availability of internet
Extracurricular	Participation in activities
Sleep_Hours	Average daily sleep
Previous_Marks	Student's previous academic score (used only in Model 1)
Final_Score	Target variable (student performance)
🧠 Models Implemented
🔹 Model 1: Linear Regression (With Previous Marks)

Algorithm: Linear Regression

Features Used: All features including Previous_Marks

Purpose:
To observe how historical academic performance improves prediction accuracy.

📈 Result:

High R² Score

Strong correlation between predicted and actual values

Indicates previous marks are a strong predictor

🔹 Model 2: Linear Regression (Without Previous Marks)

Algorithm: Linear Regression

Features Used: All features excluding Previous_Marks

Purpose:
To evaluate model performance using only behavioral and environmental factors.

📉 Result:

Lower R² Score compared to Model 1

Still performs reasonably well

Shows model can generalize even without historical scores

📊 Model Comparison (R² Score)
Model	Features Used	R² Score
Model 1	With Previous Marks	Higher
Model 2	Without Previous Marks	Lower

✔️ Conclusion:
Both models are valid and useful, but:

Model 1 is more accurate

Model 2 is more practical when past marks are unavailable

🔍 Evaluation Metrics Used

R² Score – Measures how well the model explains variance

Mean Absolute Error (MAE) – Average prediction error

Confusion Matrix (after converting predictions into grade categories)

⚠️ Note: Confusion Matrix was added after discretizing continuous scores into performance classes (Low, Medium, High).

📌 Visualizations Included

📈 Actual vs Predicted Score Plot

📊 Feature Importance Analysis

📉 Error Distribution

🔲 Confusion Matrix Heatmap

These visualizations help in:

Understanding prediction quality

Identifying underperforming cases

Model interpretability

🛠️ Technologies Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

Jupyter Notebook

🚀 Key Learnings

Previous academic performance significantly improves prediction

Behavioral features still provide meaningful insights

Model evaluation is incomplete without proper metrics & visualization

Feature selection directly affects model performance
