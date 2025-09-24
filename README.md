# Aviation Weather Forecasting Project

## Overview
This project focuses on predicting key aviation weather parameters, including visibility and fog probability, using machine learning models. The goal is to support aviation operations by providing accurate forecasts and probabilistic predictions of weather conditions that impact flight safety and efficiency.

## Features
- Predicts visibility and fog occurrence with confidence scores.
- Benchmarks multiple models, including:
  - **Random Forest (RF)**
  - **XGBoost (XGB)**
  - **LightGBM (LGBM)**
  - **Long Short-Term Memory (LSTM) networks**
- Compares model performance across different weather parameters.
- Provides probabilistic fog predictions for improved operational decision-making.
- Pipeline-based approach using historical weather data (last 12 hours) for forecasting.

## Potential Applications
- Enhancing flight planning and safety measures.
- Optimizing airport ground operations under low-visibility conditions.
- Personal project can serve as a prototype for aviation industry applications.

## Data
- Historical weather observations (temperature, humidity, wind, etc.) from relevant airport locations.
- Hourly records used for model input features.

## Model Workflow
1. Preprocess historical weather data.
2. Generate lag features based on the previous 12 hours.
3. Train and validate machine learning models.
4. Compare model performance and select the best model per parameter.
5. Output predicted values and confidence levels for fog.

## Requirements
- Python >= 3.8
- Libraries:
  - pandas
  - numpy
  - scikit-learn
  - xgboost
  - lightgbm
  - tensorflow / keras (for LSTM)
  - matplotlib / seaborn (for visualization)

## Results
- Comparative evaluation of models for each parameter.
- Probabilistic fog forecasts enabling confidence-based decisions.
- Sample visualizations of predictions included in `visualizations/`.

## Future Work
- Extend to other airports and weather parameters.
- Deploy as a real-time forecasting application.
- Experiment with ensemble or hybrid models for improved accuracy.

## Author
Tanish Chawla

## License
This project is licensed under the following terms:  
**All rights reserved. No part of this code may be used, copied, modified, or distributed without express written permission from the author.**
