## Business Context & Problem Statement

### Business Context
Car dealers and automotive market analysts often need to assess the market value of vehicles. An accurate price prediction model allows faster decision-making for buying and selling, helps optimize revenue, and reduces financial risks. Additionally, understanding which features most influence car prices can provide insights for pricing strategies and inventory management.

### Problem Statement
The goal of this project is to build a linear regression model to predict the price of BMW cars based on historical sales data from 2010 to 2024. The model will take into account car features such as year of manufacture, model, engine size, transmission type, and other relevant attributes. By providing reliable price estimates, the model supports business and analytical decision-making for both dealers and buyers.

### Dataset Overview
The dataset used in this project is the **BMW Worldwide Sales Records (2010–2024)** from Kaggle. It contains approximately 50,000 records with features including:

- Car model and variant  
- Year of manufacture  
- Engine specifications  
- Transmission type  
- Country/region of sale  
- Sales price  

The target variable for prediction is:  
- **Price** — the sale price of the vehicle.  

The predictor variables (features) include year, model, engine size, transmission type, and other relevant car attributes.

### Evaluation Metrics
The model's performance will be evaluated using the following metrics:

- **Mean Absolute Error (MAE):** Measures the average absolute difference between predicted and actual car prices. Lower values indicate better accuracy and interpretability in euros.  
- **Root Mean Squared Error (RMSE):** Shows how much predictions deviate from actual prices in the same units, sensitive to large errors.  
- **R² (R-squared):** Indicates the proportion of variance in car prices explained by the model. Values closer to 1 indicate a better fit.  

**Optional metrics for additional analysis:**  
- **Adjusted R²:** Corrected for the number of features; useful to evaluate whether adding new variables improves the model meaningfully.  
- **Mean Absolute Percentage Error (MAPE):** Measures error in percentage terms; useful for understanding relative prediction errors.

### Assumptions & Limitations
- The dataset may not include all possible car features affecting price.  
- Market conditions and regional differences may influence prices but are not fully captured.  
- Linear regression assumes a linear relationship between features and car price.
