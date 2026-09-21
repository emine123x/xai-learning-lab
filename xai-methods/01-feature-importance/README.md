# Feature Importance in XAI

This mini project demonstrates how feature importance can change across different machine learning models.

Using the Breast Cancer Wisconsin dataset, I trained two models:

- Random Forest Classifier
- Gradient Boosting Classifier

The goal is to show that feature importance is not an absolute truth. It depends on the model, dataset, and calculation method.

## Key idea

Feature importance helps us understand which signals a model relies on, but it does not prove causality.

## Outputs

The generated figures are stored in the `figures/` folder:

- `random_forest_feature_importance.png`
- `gradient_boosting_feature_importance.png`
- `feature_importance_comparison.png`