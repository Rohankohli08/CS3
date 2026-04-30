# CS3 – Wildfire Prediction Case Study

This contains the material for the DS 4002 Wildfire Prediction Case Study

## Section 1: Case Study Overview

You are a data scientist working for the California Governor's Office of Emergency Services trying to determine whether historical weather patterns can predict wildfire occurrence. You will use California daily weather data from 1985–2022 to train two classification models: a logistic regression and a random forest. You will evaluate which model does a better job of flagging fire days, with a focus on recall, since missing a wildfire is far more costly than a false alarm. To test your models, you will see how well they predict real wildfire occurrence in 2023.

## Section 2: Map of Documentation

Folder: HOOK
- Hook.pdf

Folder: VARIOUS MATERIALS
- Logistic Regression Confusion Matrix.png
- ROC_Curve.png
- Random Forest Feature Importance.png
- fig_annual_fire_frequency.png
- fig_class_imbalance.png
- fig_correlation_heatmap.png
- fig_fires_by_season.png
- fig_fires_by_season_year.png
- fig_temp_trends.png
- max_temp_vs_avg_wind_speed.png
- maxtemp_fire_nofire.png
- precipitation_fire_nofire.png
- quantitative_variable_histograms.png
- windspeed_fire_nofire.png
- ECMWF_Wildlife_Forecasting.pdf
- Wildfire_Assessment_ML.pdf

Folder: VARIOUS MATERIALS/data
- CA_Weather_Fire_Dataset_1984-2025.csv
- cleaned_df.csv
- Data Appendix.pdf

Folder: VARIOUS MATERIALS/scripts
- EDA.ipynb
- Model.ipynb

LICENSE.txt  
README.md

## Section 3: Data

Navigate to the VARIOUS MATERIALS/data folder and download CA_Weather_Fire_Dataset_1984-2025.csv. This dataset contains daily weather observations for California including maximum temperature, minimum temperature, precipitation, average wind speed, and a binary FIRE_START_DAY column indicating whether a wildfire ignition was recorded that day. A full description of all columns is available in Data Appendix.pdf.

## Section 4: Instructions for Reproducing Results

1. Navigate to the VARIOUS MATERIALS/data folder and download CA_Weather_Fire_Dataset_1984-2025.csv
2. Upload the data into your environment (e.g. Google Colab or VS Code)
3. After uploading the file, navigate to the VARIOUS MATERIALS/scripts folder and upload EDA.ipynb to the same environment
4. Run EDA.ipynb to explore the dataset and generate all exploratory visualizations
5. Once EDA is complete, upload Model.ipynb to the same environment
6. Run Model.ipynb to preprocess the data, train the logistic regression and random forest models, and generate all evaluation metrics and figures
