# House Price Prediction

## Project Overview

This project develops a machine learning regression model for predicting
property prices based on property characteristics, location, and available
amenities.

The project follows a structured machine learning workflow covering data
understanding, cleaning, exploratory data analysis, preprocessing, model
development, evaluation, and final conclusions.

## Dataset

The dataset contains information about residential properties, including:

- Property price
- Area
- Location
- Number of bedrooms
- Resale status
- Property amenities and facilities

The target variable is:

`Price`

Because price is a continuous numerical variable, this is a regression
problem.

## Machine Learning Workflow

The project follows these main steps:

1. Problem Definition
2. Data Understanding
3. Data Cleaning and Preparation
4. Exploratory Data Analysis
5. Data Preprocessing
6. Model Development
7. Model Evaluation
8. Model Improvement
9. Final Evaluation and Conclusion

## Models Evaluated

The following regression models were compared:

- Linear Regression
- Random Forest
- Gradient Boosting

Gradient Boosting produced the strongest overall cross-validation
performance and was selected as the final model.

## Final Results

The final Gradient Boosting model was evaluated on an untouched test set.

| Metric | Result |
|---|---:|
| MAE | $10.03M |
| RMSE | $22.61M |
| R² | 0.0679 |

The results indicate that the model has limited predictive power and
struggles particularly with the higher-priced properties.

## Project Structure

```text
house-price-prediction/
│
├── house_price_prediction.ipynb
├── README.md
├── pyproject.toml
├── uv.lock
└── .gitignore