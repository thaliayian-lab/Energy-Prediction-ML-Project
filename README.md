# Energy Consumption Forecasting using XGBoost

##  Project Overview
This project demonstrates a complete Machine Learning pipeline for forecasting energy consumption. Since public utility data can be restrictive, I developed a **synthetic data generator** that replicates real-world power grid patterns, including circadian rhythms and seasonal trends.

##  Key Features
- **Data Simulation:** Generated 4 years of hourly energy data with stochastic noise.
- **Feature Engineering:** Implemented lag features (24h/7d) and datetime embeddings (hour, day, month).
- **Model:** Utilized **XGBoost Regressor** with early stopping to prevent overfitting.
- **Evaluation:** Achieved a high R2 Score, visualizing the forecast against ground truth.

##  Technical Stack
- **Python** (Pandas, NumPy)
- **Machine Learning:** XGBoost, Scikit-Learn
- **Visualization:** Matplotlib

## Results
The model successfully captures peak demand periods and seasonal shifts, providing a robust framework for utility load forecasting.