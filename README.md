# Enefit-Energy-Forecasting-ML-Model
This repository contains the code for building a machine learning model for the Kaggle competition "Enefit - Predict Energy Behavior of Prosumers." The challenge is to predict the amount of electricity produced and consumed by Estonian energy customers who have installed solar panels. The dataset primarily consists of weather data, relevant energy prices, and records of installed photovoltaic capacity.

For more details about the competition and the dataset, or to download the data, please visit the official competition page: (https://www.kaggle.com/competitions/predict-energy-behavior-of-prosumers/data).

In the entire script, I use Polars (https://pola.rs/) instead of Pandas due to the large size of the data. The model is based on LightGBM, utilizing only 24 features, and its performance is evaluated using the Mean Absolute Error (MAE). Specifically, the model's performance is measured as a percentage reduction in MAE compared to a lag_7 prediction.

Please note that the model presented here is not the one I submitted on Kaggle, which was much more complex—as is often the case with Kaggle competitions. Instead, this is a model I would build in a business environment, where there is a trade-off between model accuracy and complexity.
