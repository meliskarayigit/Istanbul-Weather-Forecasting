# Istanbul Weather Forecasting with LSTM & GRU
This project forecasts Istanbul’s daily average air temperature using deep learning–based time series models.
Dataset

5 years of Istanbul weather data
Temperature converted from Kelvin to Celsius
Daily resampling applied

Preprocessing

Time-based train / validation / test split (70 / 15 / 15)
Min-Max scaling
Sliding time window (10 days)

Models

LSTM as a baseline model
GRU with hyperparameter tuning using Keras Tuner (Random Search)
Hyperparameter Tuning (GRU)
Layers: 1–10
Units: 16–1024
Dropout: 0.0–0.5
Learning rate: 1e-5–1e-2

Evaluation

Metric: Mean Squared Error (MSE)
Performance evaluated on train, validation, and test sets
Actual vs predicted temperature plots

Tools & Libraries

Python, TensorFlow/Keras, Keras Tuner, Pandas, NumPy, Scikit-learn, Matplotlib
