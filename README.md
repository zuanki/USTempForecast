# Sub-Seasonal Temperature Forecasting

Welcome to the Awesome Weather Forecast repository! This project focuses on forecasting sub-seasonal temperatures (temperatures over a two-week period) within the United States. With the increasing frequency of extreme weather events worldwide, accurate long-term temperature forecasts are essential for preparedness and adaptation.

## Goal
The goal of this project is to improve sub-seasonal temperature forecasts by blending physics-based models with machine learning techniques. By leveraging meteorological data and advanced algorithms, we aim to provide more accurate predictions for weather and climate conditions, specifically within a lead time of 15 to 45 days. This will assist communities and industries in better understanding and adapting to the challenges posed by climate change.

## Dataset
We are using the data provided by the National Oceanic and Atmospheric Administration (NOAA) in collaboration with Climate Change AI (CCAI) for the WiDS Datathon 2023 competition. The dataset is available on Kaggle: [WiDS Datathon 2023](https://www.kaggle.com/competitions/widsdatathon2023/data). It includes the following files:

- `train_data.csv`: The training dataset containing observed temperature data over the next 14 days for each location and start date.
- `test_data.csv`: The test dataset for which we need to make predictions.

## Methodology
Our approach involves a combination of K-means clustering for weather condition classification and ensemble learning for temperature forecasting. The ensemble learning models used are XGBoost, LightGBM, CatBoost, and Linear Regression. By leveraging the strengths of these algorithms, we aim to achieve more accurate temperature predictions.

## Results
Our forecasting model achieved a bias of only 0.691 degrees Celsius, placing us in the top 1% of the competition. These results demonstrate the effectiveness of our approach in providing reliable sub-seasonal temperature forecasts.