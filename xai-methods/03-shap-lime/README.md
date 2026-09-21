# SHAP vs LIME

This folder contains practical work for comparing SHAP and LIME as local explanation methods in Explainable AI.

The main goal is to explain the same machine learning prediction with both methods and compare how their explanations differ.

## Project Structure

- `data/`: Dataset-related notes or files. In this project, the dataset is loaded directly from scikit-learn.
- `notebooks/`: Main Jupyter notebooks for model training and explanation.
- `figures/`: Saved explanation plots used in the article.
- `reports/`: Article outline and interpretation notes.
- `src/`: Optional helper scripts if the project grows.

## Methods Used

- Random Forest Classifier
- LIME
- SHAP
- Local prediction explanation
- Feature contribution analysis

## Dataset

This project uses the Breast Cancer Wisconsin dataset from scikit-learn for educational purposes.

The goal is not to build a medical diagnosis system.  
The goal is to understand how two XAI methods explain the same model prediction.