Zelestra Solar Power Prediction - Practice Model
Project Overview
This project is a practice model for predicting solar power output based on sunlight hours and temperature, inspired by the Zelestra x AWS ML Ascend Challenge. It demonstrates basic data exploration, linear regression modeling, and evaluation using real-world-inspired data.

Dataset
Synthetic dataset with features:

sunlight_hours: Number of sunlight hours per day

temperature_celsius: Average daily temperature in Celsius

Target variable:

solar_power_kw: Solar power output in kilowatts (kW)

Approach
Explored data using descriptive statistics and correlation analysis.

Built a simple Linear Regression model using scikit-learn.

Visualized actual vs predicted solar power outputs.

Evaluated model performance with Mean Absolute Error (MAE) and R² score.

Results
MAE: ~1 kW (average error between predicted and actual solar power)

R² Score: ~0.99 (indicating a strong fit between model predictions and actual data)

Future Work
Improve the model by exploring additional features or algorithms.

Test model performance on real-world solar energy datasets.

Implement cross-validation and other advanced evaluation techniques.
