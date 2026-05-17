# Error Analysis: Linear Regression

Goal

The goal of this error analysis is to understand where the Linear Regression model makes prediction errors and whether these errors follow a systematic pattern.

Residual Definition

Residual is the difference between the actual value and the predicted value.

residual = actual_exam_score - predicted_exam_score

If the residual is positive, the model underpredicted the exam score.

If the residual is negative, the model overpredicted the exam score.

What I Looked For

In this analysis, I focused on the following questions:

Are the residuals randomly distributed around zero?
Does the model make larger errors for low or high study hours?
Is there any visible pattern in the residual plot?
Does the linear model seem appropriate for this data?
Observations

The model captures the general increasing relationship between study hours and exam score.

As study hours increase, the predicted exam score also increases.

The residual plot helps us check whether the model misses a pattern in the data.

If the residuals are scattered around zero without a clear pattern, the linear model is reasonably appropriate.

If the residuals show a curved or systematic pattern, this may indicate that a linear model is too simple.

Interpretation

In this project, residual analysis is important because explainability is not only about understanding the model's formula.

A model should also be evaluated by examining its mistakes.

Understanding where the model fails is part of understanding how the model behaves.

Limitations of the Error Analysis

This error analysis is limited because the dataset is very small.

With only a few data points, it is difficult to make strong conclusions about the model's reliability.

A larger and more realistic dataset would be needed for a stronger evaluation.

Summary

The model provides a simple and interpretable prediction rule.

However, residual analysis reminds us that even interpretable models can make errors.

A good model explanation should include both the decision logic and the error behavior.