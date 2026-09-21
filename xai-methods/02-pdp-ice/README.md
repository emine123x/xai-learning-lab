# PDP vs ICE: Spotify Track Popularity Example

This project demonstrates how Partial Dependence Plot (PDP) and Individual Conditional Expectation (ICE) can be used to inspect model behavior in a music-related prediction task.

The main question of this project is:

**Does the average model behavior tell the whole story?**

## Project Goal

The goal is to train a simple machine learning model on Spotify track features and analyze how the model reacts to changes in the `tempo` feature.

This project is not focused on building the best possible popularity prediction model. Instead, it focuses on using explainable AI methods to understand model behavior.

## Dataset

The project uses a Spotify tracks dataset containing audio features such as danceability, energy, loudness, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration_ms, and popularity.

The target variable is `popularity`.

The raw dataset is not included in this repository. To reproduce the notebook, place the dataset file under:

`data/raw/dataset.csv`

## Model

A RandomForestRegressor model is trained to predict Spotify track popularity using numerical audio features.

Model performance:

- MAE: 15.857
- RMSE: 19.583
- R²: 0.223

The model has limited predictive performance, but it is sufficient for demonstrating PDP and ICE interpretation. The goal of this project is not prediction optimization, but model behavior analysis.

## XAI Methods Used

This project focuses on two explainable AI methods: Partial Dependence Plot and Individual Conditional Expectation.

PDP shows the average model response when a selected feature changes. In this project, PDP is used to ask:

**How does the model's average predicted popularity change when tempo changes?**

ICE shows how individual observations respond when a selected feature changes. In this project, ICE is used to ask:

**Does every track follow the same tempo-popularity pattern, or do individual observations behave differently?**

## Key Interpretation

PDP provides the general view.

ICE helps inspect whether that general trend is consistent across individual observations.

In this project, the PDP curve for tempo appears relatively stable and non-linear. The ICE curves show that individual observations are not identical, which reminds us that average model behavior may hide differences between individual cases.

## Figures

The project includes three visual outputs:

- PDP for tempo
- ICE curves for tempo
- Combined PDP and ICE plot for tempo

These figures are saved under the `figures/` folder.

## Related Article

This project supports the Medium article:

**PDP vs ICE: When the Average Hides the Story**

The article explains how PDP and ICE can be used to understand average and individual model behavior in explainable AI.