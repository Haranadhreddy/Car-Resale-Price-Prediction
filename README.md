# Car Resale Price Prediction

## Introduction
This project focuses on predicting the resale value of used cars by leveraging historical sales data with data science and machine learning techniques. It aims to revolutionize the used car market by offering accurate price predictions, benefiting both sellers and buyers, and fostering a transparent pricing environment.

## Project Significance
- **Transparency:** Provides clear, data-driven price estimations.
- **Informed Decisions:** Helps consumers make informed purchasing decisions through data insights.

## Data Overview
- **Total Observations:** 4345
- **Features:**
  - Categorical: Brand, Body Type, Engine Type
  - Continuous: Mileage, Engine Volume, Year of Manufacture
  - Response Variable: Price

## Methodology
- **Data Preprocessing:** Handling missing values, transforming continuous data, and converting categorical data into binary format.
- **Exploratory Analysis:** Investigating relationships between various features and their impact on car prices.
- **Model Building:** Implementing Regression Models including Linear Regression, Random Forest, and Gradient Boosting.

## Tools & Techniques
- **Programming Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn, scikit-learn
- **Machine Learning Techniques:** Regression algorithms like Linear Regression, Random Forest, and Gradient Boosting.

## Model Performance
- **Linear Regression:** R² = 0.8834, RMSE = 0.3066
- **Random Forest Regressor:** R² = 0.9187, RMSE = 0.2560
- **Gradient Boosting Regressor:** R² = 0.9189, RMSE = 0.2559
- The Gradient Boosting Regressor shows marginally better fit and accuracy.

## Conclusion
Gradient Boosting emerges as the most effective model, offering the highest accuracy for predicting the resale value of used cars.

## How to Use
To run this project, ensure you have Python installed along with the necessary libraries mentioned above. Clone this repository, navigate to the directory containing the project files, and execute the script via a Python IDE or the command line.
