# California Housing Price Prediction

## Overview

This project aims to develop a predictive model for estimating housing prices in California using machine learning techniques. Utilizing the California housing dataset, which contains various features related to housing and demographics, the model will be trained to predict the median house values based on these attributes.

## Dataset

The California housing dataset consists of information about housing and population characteristics across various geographic locations in California. Key features include:

- **Medain House Value**: The target variable representing the median price of houses in each district.
- **Number of Rooms**: The total number of rooms in the house.
- **Number of Bedrooms**: The total number of bedrooms in the house.
- **Population**: The total population residing in the district.
- **Households**: The number of households in the district.
- **Geographic Features**: Features such as proximity to the ocean and average household income.

The dataset is available through the [California housing dataset](https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html) from the Scikit-Learn library.

## Methodology

1. **Data Preprocessing**:
   - Handling missing values using imputation.
   - Encoding categorical variables using one-hot encoding.
   - Normalizing numerical features to ensure they are on a similar scale.

2. **Feature Engineering**:
   - Creating additional features that may improve the model's performance, such as the ratio of bedrooms to rooms and the average number of rooms per household.

3. **Model Selection**:
   - Exploring various regression algorithms, including Linear Regression, Decision Trees, and Random Forests, to identify the best-performing model.
   - Utilizing cross-validation and hyperparameter tuning (Randomized Search) to optimize model performance.

4. **Evaluation Metrics**:
   - Evaluating model performance using metrics such as Mean Squared Error (MSE) and Root Mean Squared Error (RMSE) to gauge accuracy in predicting housing prices.

