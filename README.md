# House Price Prediction using Machine Learning

1. Project Overview

This project focuses on predicting house prices based on property features such as area, number of bedrooms, bathrooms, floors, year built, location, condition, and garage availability.
A regression-based machine learning model is trained to estimate house prices using housing data.

3. Objectives
* Perform data preprocessing and feature engineering
* Train a regression model for price prediction
* Evaluate model performance using standard metrics
* Visualize predicted vs actual prices
* Test the model with custom input data

3. Dataset
The dataset contains the following features:
* Area (square footage)
* Bedrooms
* Bathrooms
* Floors
* YearBuilt
* Location (categorical)
* Condition (categorical)
* Garage (categorical)
* Price (target variable)

4. Technologies Used
* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

5. Workflow

1. Data Preprocessing
* Handling missing values
* Encoding categorical variables using One-Hot Encoding
* Feature scaling using StandardScaler

2. Model Training
* Gradient Boosting Regressor
* Train-test split (80/20)

3. Evaluation Metrics
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)

4. Visualization
* Scatter plot of actual vs predicted prices

6. Results
The model was evaluated using MAE and RMSE.
It successfully learned patterns between property features and house prices.
Example prediction:
Predicted House Price: 421,550

7. Sample Prediction

Input:

* Area: 2500
* Bedrooms: 3
* Bathrooms: 2
* Floors: 1
* Year Built: 2015
* Location: Urban
* Condition: Excellent
* Garage: Yes

Output:
Predicted Price ≈ 421,550

8.Future Improvements

* Use advanced models (XGBoost, Random Forest)
* Hyperparameter tuning
* Deploy model using Flask or Streamlit
* Add more real-world features
