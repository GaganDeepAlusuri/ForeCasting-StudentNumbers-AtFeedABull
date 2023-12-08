# Forecasting Student Numbers at Feed-A-Bull Pantry USF

## Abstract
This project aims to estimate the number of students visiting the USF Feed-a-Bull pantry using survey data from 2018-2022. We utilized time-series forecasting models and data visualization to analyze trends and improve the pantry's efficiency.

## Introduction
Feed-A-Bull is a USF initiative addressing student hunger. Our study identifies patterns in pantry usage, with a focus on changes due to COVID-19.

## Motivation
The COVID-19 pandemic exacerbated food insecurity, a significant issue for college students. This study explores the factors leading to food insecurity and compares pre-pandemic and pandemic-era data.

## Business Objective
1. Predict weekly student visits to Feed-A-Bull.
2. Provide insights by comparing pre and post-pandemic data.
3. Identify student categories most vulnerable to food insecurity.

## Data
Data collected includes variables like visit dates, first-time visits, employment status, and food sufficiency. Data from 2018-2022 was analyzed, focusing on key variables across this period.

## Methodology
### Exploratory Data Analysis
- Seasonality and weekly trends were examined using line graphs and calendar heatmaps.
- Data smoothing techniques (Triangular Moving Average, Kernel Smoothing) were applied for clearer trend interpretation.

### Time Series Analysis using Prophet
- Facebook's Prophet package was used for forecasting, given its effectiveness in handling seasonal data.
- Model fitting and forecasting for the next few months were conducted, revealing patterns in pantry usage.

## Results
- The Prophet model identified consistent trends and a significant increase in visits in 2022.
- Peak usage was observed on Wednesdays and Thursdays.
- Seasonal change points were crucial for model tuning.

## Model Evaluation
- Time series cross-validation was conducted.
- Root Mean Square Error (RMSE) was used to assess forecast accuracy, with an average prediction error of 4 students per day.

## Conclusions and Implications
- The model predicts a sharp rise in pantry usage.
- Recommends an additive trend with multiplicative seasonality for better forecasting accuracy.
- Identifies key seasonal change points to aid model accuracy.

## Authors
- Chandni Kumari
- Raghav Khurana
- Venkata Sai Gagan Deep Alusuri
- Lakshmi Preetam Gupta Dogiparthi

## Acknowledgments
[Add any acknowledgments here if necessary]

## References
[Add your references or any additional resources here]

---
