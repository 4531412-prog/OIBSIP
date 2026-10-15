# House Price Prediction Using Linear Regression

## Oasis Infobyte Data Analytics Internship

### Level 2 — Task 1

## Project Overview

This project develops and evaluates machine learning regression models for predicting house prices using property characteristics such as area, bedrooms, bathrooms, stories, parking, amenities and furnishing status.

The project demonstrates the complete predictive analytics workflow from exploratory data analysis through model evaluation and interpretation.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab

## Dataset Features

The housing dataset contains property information including:

- Price
- Area
- Bedrooms
- Bathrooms
- Stories
- Main road access
- Guest room
- Basement
- Hot water heating
- Air conditioning
- Parking
- Preferred area
- Furnishing status

## Project Workflow

The project includes:

- Initial data inspection
- Missing-value analysis
- Duplicate detection
- Descriptive statistics
- House-price distribution analysis
- Feature visualisation
- Correlation analysis
- Feature-selection discussion
- One-Hot Encoding
- 80/20 train-test split
- Multiple Linear Regression
- Prediction generation
- MSE evaluation
- RMSE evaluation
- R² evaluation
- Actual vs predicted visualisation
- Residual analysis
- Coefficient analysis
- Ridge Regression comparison
- Final model selection

## Linear Regression Results

- Training observations: 436
- Testing observations: 109
- R² Score: 0.6529
- RMSE: approximately 1,324,507
- MSE: approximately 1.754 trillion

The model explains approximately 65.29% of the variation in house prices within the test dataset.

## Feature Interpretation

The strongest positive model coefficient was:

**Bathrooms**

The strongest negative coefficient was:

**Unfurnished furnishing status**

These results indicate that property characteristics and furnishing conditions both contribute to predicted house values.

## Ridge Regression Comparison

Ridge Regression was tested as a regularised alternative.

### Ridge Regression

- R² Score: 0.6525
- RMSE: approximately 1,325,320

### Linear Regression

- R² Score: 0.6529
- RMSE: approximately 1,324,507

Linear Regression slightly outperformed Ridge Regression and was therefore selected as the preferred final model.

## Conclusion

The project demonstrates how regression modelling can be used to estimate property values and identify influential housing characteristics.

Although the model explains a meaningful proportion of house-price variation, additional features such as exact location, neighbourhood quality, property condition and wider market conditions could potentially improve future predictive performance.

## Author

Ty

## Internship

Oasis Infobyte — Data Analytics Internship
