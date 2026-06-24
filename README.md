Housing Price Prediction Using Linear Regression

Project Overview

This project analyzes housing data and develops a Linear Regression model to predict house prices. The analysis includes data cleaning, exploratory data analysis, feature engineering, model training and performance evaluation.

Project Objectives

* Understand the factors that influence house prices

* Explore relationships between variables

* Identify important predictors of house value

* Build a Linear Regression model for price prediction

* Evaluate model performance using regression metrics
  

Data Preparation

The dataset was imported and inspected to understand its structure and variables.

Data cleaning was performed by checking for missing values and ensuring the dataset was suitable for analysis.


Additional features were created to improve the model:

* Rooms per Household

* Bedrooms per Room

* Population per Household

The selected features were normalized using StandardScaler before model training.


Exploratory Data Analysis

Variable Distributions

Histograms were used to understand the distribution of housing variables.

Some variables showed skewed distributions, while others were more evenly distributed across observations.

House Price Distribution

The distribution of median house values was analyzed using a histogram.

Most properties were concentrated within lower to mid-range price categories, while fewer properties appeared in the higher price range.

Scatter Plot Analysis

Scatter plots were created to examine relationships between predictor variables and house prices.

Key observations include:

* Median income showed a strong positive relationship with house prices.

* Housing median age showed a moderate relationship with house prices.

* Geographic variables such as longitude and latitude influenced property values.

* Population-related variables showed weaker relationships with house prices.

Correlation Analysis

A correlation heatmap was created to identify relationships between variables.

Key Insights

* Median income had the strongest positive correlation with house prices.

* Some housing-related variables were highly correlated with each other.
  
* Location variables contributed significantly to housing value differences.
  
* Engineered variables provided additional information about household characteristics.

Model Development

The dataset was divided into training and testing datasets using an 80:20 split.

A Linear Regression model was trained using the selected features.

The model learned relationships between housing characteristics and median house values to generate predictions.

Model Evaluation

The model was evaluated using:

* Mean Absolute Error
  
* Root Mean Squared Error
  
* R² Score

These metrics were used to measure prediction accuracy and overall model performance.

Prediction Results

An Actual vs Predicted scatter plot was generated to compare model predictions against actual house values.

The visualization showed how closely the predicted values aligned with the true values.

Feature Importance

Feature coefficients were analyzed to determine the influence of each variable on house prices.

Key Findings

* Median income was the strongest predictor of house prices.
  
* Location-related variables played an important role in determining housing value.
  
* Household and room-related features contributed to model predictions.
  
* The Linear Regression model successfully captured relationships between housing characteristics and property values.


Conclusion

The project successfully developed a Linear Regression model for predicting housing prices.

The analysis showed that median income, location and household characteristics have a significant impact on house values.

The model provides useful insights into housing price trends and serves as a foundation for more advanced predictive modeling techniques.
