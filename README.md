# **🌞 Solar Flare Prediction with XGBoost (SFP-XGB)**

**This repository contains a comprehensive approach to predicting solar flare characteristics using machine learning, specifically the **XGBoost** model. The project focuses on analyzing solar flare data to forecast two key metrics:**
- **Duration from peak to end for individual solar flares.**
- **Daily frequency of solar flares.**

## **🛠️ Features**
- **Data Preprocessing: Cleaning, time transformation, and feature engineering for both categorical and temporal data.**
- **Feature Engineering:**
  - **Lagged feature creation for time-series data.**
  - **Computation of durations and time differences between solar flares.**
  - **One-hot encoding for categorical features.**
- **Model: Utilization of XGBoost for its robust handling of non-linear patterns and time-series dependencies.**
- **Evaluation: Performance measured using Mean Absolute Error (MAE) and visual comparisons of predictions against actual values.**

## **🚀 Objectives**
- **Understand and preprocess raw solar flare data.**
- **Predict the peak-to-end duration of solar flares based on engineered features.**
- **Forecast the daily frequency of solar flares using historical time-series data.**
- **Visualize and evaluate the model's performance to ensure reliability.**

## **📊 Data Visualization**
- **Number of Solar Flares vs. Time: A time-series plot showing the daily counts of solar flares.**
- **Autocorrelation Function (ACF): Insights into temporal dependencies in flare occurrences.**
- **Predicted vs. Actual Values: A comparative plot highlighting the model’s performance.**

  ### **Data Preprocessing**
    - **Cleaning and formatting time-related columns.**
    - **Creating lagged features and durations.**
    - **One-hot encoding for categorical data.**

  ### **Model Training**
    - **XGBoost model implementation with early stopping.**
    - **Evaluation using Mean Absolute Error (MAE).**

  ### **Visualization**
    - **Time-series and autocorrelation plots.**
    - **Comparison of actual and predicted solar flare values.**

## **📖 Results**
- **Mean Absolute Error (MAE):**
  - **Peak-to-End Duration Prediction: 371.53.**
  - **Daily Flare Frequency Prediction: 2.81.**
- **Visualizations confirm the model's ability to closely align with observed data.**

## **🤝 Contributing**
**Feel free to fork this repository and submit pull requests for enhancements or fixes. Contributions are welcome!**

## **📝 License**
**This project is licensed under the MIT License. See the `LICENSE` file for details.**

## **🙌 Acknowledgments**
- **The dataset for this project is courtesy of solar flare monitoring systems.**
- **XGBoost library for providing powerful machine learning capabilities.**
