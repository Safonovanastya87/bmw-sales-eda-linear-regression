# BMW Price Prediction Project

## Business Context
Car dealers and automotive market analysts often need to assess the market value of vehicles. Having an accurate price prediction model allows faster decision-making for buying and selling, helps optimize revenue, and reduces financial risks. Additionally, understanding which features most influence car prices can provide insights for pricing strategies and inventory management.

## Problem Statement
The goal of this project is to build a linear regression model to predict the price of BMW cars based on historical sales data from 2010 to 2024. The model will take into account car features such as year of manufacture, model, engine size, and other relevant attributes. By providing reliable price estimates, the model supports business and analytical decision-making for both dealers and buyers.

## Dataset Overview
The dataset used in this project is the **BMW Worldwide Sales Records (2010–2024)** from Kaggle. It contains detailed information on BMW car sales across different regions and years, including features like:

- Car model and variant
- Year of manufacture
- Engine specifications
- Transmission type
- Country/region of sale
- Sales price

This dataset allows us to explore relationships between car attributes and their market prices, making it suitable for building and evaluating a predictive linear regression model.

## Evaluation Metrics
The model's performance will be evaluated using the following metrics:

- **Mean Absolute Error (MAE):** Measures the average absolute difference between predicted and actual car prices. Lower values indicate better accuracy.  
- **Root Mean Squared Error (RMSE):** The square root of the mean squared error, showing how much predictions deviate from actual prices in the same units (e.g., euros). Sensitive to large errors.  
- **R² (R-squared):** Indicates the proportion of variance in car prices explained by the model. Values closer to 1 indicate a better fit.  
- **Optional metrics:**  
  - **Adjusted R²:** Corrected for the number of features; useful to evaluate whether adding new variables improves the model meaningfully.  
  - **Mean Absolute Percentage Error (MAPE):** Measures error in percentage terms; useful for understanding relative prediction errors.

## Project Workflow
The project follows a standard machine learning workflow:

1. **Data collection:** Downloading and loading BMW Worldwide Sales dataset.  
2. **Exploratory Data Analysis (EDA):** Understanding feature distributions, relationships, missing values, and outliers.  
3. **Data preprocessing:** Handling missing values, encoding categorical features, scaling if necessary.  
4. **Modeling:** Building and training a linear regression model.  
5. **Evaluation:** Measuring performance using MAE, RMSE, and R².  
6. **Interpretation:** Analyzing feature importance and understanding which factors most influence BMW prices.  
7. **Conclusion:** Summarizing findings, limitations, and potential improvements.
