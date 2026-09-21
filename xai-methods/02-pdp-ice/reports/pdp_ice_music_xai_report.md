## Model Performance

The RandomForestRegressor achieved a limited but usable performance for demonstration purposes:

- MAE: 15.857
- RMSE: 19.583
- R²: 0.223

This project is not focused on building the best possible popularity prediction model. The main goal is to demonstrate how PDP and ICE can be used to inspect model behavior.

## PDP and ICE Interpretation

The PDP curve for tempo shows the average model response when the tempo feature changes. In this dataset, the average effect of tempo on predicted popularity appears relatively limited and non-linear.

The ICE curves show how individual observations respond to changes in tempo. Although many curves appear relatively stable, they are not identical. This shows why looking only at the average behavior can hide differences between individual observations.

In this project, PDP provides the general view, while ICE helps inspect whether that general trend is consistent across different tracks.