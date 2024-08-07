# EPL Match Winner Prediction for 2024-25 Season

## Project Overview

This project aims to predict the winners of English Premier League (EPL) matches for the 2024-25 season. Utilizing historical data from the 2022-2024 seasons, a prediction model was built to forecast match outcomes with a focus on accuracy.

## Data Collection

The data was scraped from FBref using Beautiful Soup and extracted from HTML. The dataset encompasses various performance metrics and statistics from the previous two EPL seasons.

## Data Processing

1. **Data Collection:** Historical match data (2022-2024) was collected using Beautiful Soup and Pandas.
2. **Data Cleaning:** The raw data was cleaned and pre-processed with Pandas to ensure consistency and accuracy for modeling.
3. **Feature Engineering:** Additional predictor variables were introduced to enhance the model's performance.

## Model Building

The prediction model was developed using Scikit-Learn with the following classifiers:
- **Decision Tree Classifier**
- **Random Forest Classifier**

Initially, the model achieved an accuracy of 60% in predicting match outcomes, with a specific winner prediction accuracy of 47%.

## Model Improvement

To improve the prediction of specific match winners, the following steps were undertaken:
1. **Error Analysis:** Measurement of model errors to identify areas for improvement.
2. **Data Enhancement:** Further cleaning and addition of new predictor variables.
3. **Model Refinement:** Adjustments to the model to boost performance.

After these improvements, the model's accuracy in predicting specific match winners increased to 60%.

## Results

- **Overall Match Outcome Prediction Accuracy:** 60%
- **Specific Match Winner Prediction Accuracy:** 60%