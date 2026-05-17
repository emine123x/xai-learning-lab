# Model Card: Linear Regression for Exam Score Prediction

Model Details

Model name: Linear Regression

Model type: Supervised regression model

Library: scikit-learn

Task: Predicting exam score based on study hours

Intended Use

This model is used as a simple educational example to understand how Linear Regression works and how its predictions can be interpreted.

The purpose of this project is not to build a real exam prediction system. The purpose is to analyze the behavior of a basic interpretable machine learning model.

Input

The model uses one input feature:

study_hours: number of hours studied

Output

The model predicts:

exam_score: expected exam score

Model Interpretation

Linear Regression is an interpretable model because its prediction rule can be written as a simple equation.

The model learns the relationship between study_hours and exam_score.

The coefficient shows how much the predicted exam score changes when study_hours increases by one unit.

The intercept represents the model's baseline prediction when study_hours is zero.

In this project, the model decision can be explained directly through the coefficient, intercept, and residuals.

Explainability Method

The main explainability method used in this project is intrinsic interpretability.

This means that the model itself is understandable because its internal structure is simple.

The project focuses on:

coefficient interpretation
intercept interpretation
prediction explanation
residual analysis
error analysis
Limitations

This model has several limitations:

The dataset is very small.
The data is synthetic and simplified.
The model assumes a linear relationship between study hours and exam score.
The model uses only one feature.
Real exam performance depends on many other factors such as sleep, prior knowledge, stress, teaching quality, motivation, and exam difficulty.
The model should not be used for real educational evaluation.
Ethical Considerations

This model should not be used to judge a student's ability or future performance.

A real educational prediction system would require more data, careful validation, fairness analysis, and domain expertise.

Summary

This model is useful for learning how Linear Regression works and how a simple model can be explained.

However, it is not suitable for real-world decision-making.