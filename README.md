# Product Demand Forecasting Project

## Intern Intelligence Data Analytics Task 1

This project implements a predictive analytics model to forecast future product demand based on historical data, as part of the Intern Intelligence internship program.

## Project Overview

The project follows a comprehensive data science workflow to analyze historical product demand patterns and build a machine learning model that can accurately predict future demand trends:

1. **Data Preparation & Cleaning**
   - Converting date formats to proper datetime objects
   - Handling missing values and outliers
   - Normalizing order demand values

2. **Feature Engineering**
   - Extracting time-based features (year, month, day)
   - Aggregating data at the monthly level for trend analysis
   - Creating temporal features to capture seasonality

3. **Exploratory Data Analysis**
   - Visualizing historical demand patterns
   - Identifying seasonal trends and patterns
   - Analyzing demand distribution across different warehouses and product categories

4. **Model Development**
   - Implementing a Random Forest Regressor for demand forecasting
   - Training on historical data with time-based features
   - Evaluating model performance with MAE and RMSE metrics

5. **Forecasting Results**
   - Predicting demand for the next 6 months (January to June 2024)
   - Visualizing forecasted trends against historical patterns
   - Providing business insights based on the predictions

## Dataset

This project uses the "Historical Product Demand" dataset from Kaggle:
- **Dataset**: [Product Demand Forecasting](https://www.kaggle.com/datasets/felixzhao/productdemandforecasting)
- **Features**: Product_Code, Warehouse, Product_Category, Date, Order_Demand
- **Size**: Over 1 million records of historical product demand data

## Results

The Random Forest Regressor model achieved:
- Mean Absolute Error (MAE): 6,044,362
- Root Mean Squared Error (RMSE): 7,302,280

The forecasted demand for the first half of 2024 shows varying monthly patterns:

| Month | Predicted Order Demand |
|-------|------------------------|
| Jan   | 21,133,733            |
| Feb   | 20,318,726            |
| Mar   | 23,267,449            |
| Apr   | 23,357,882            |
| May   | 21,546,516            |
| Jun   | 22,062,112            |

## Business Insights

1. **Seasonal Patterns**: March and April show the highest predicted demand, suggesting potential seasonal effects.
2. **Inventory Planning**: Businesses should prepare for increased inventory needs in Q1 2024.
3. **Resource Allocation**: Warehouse and logistics resources should be optimized for the forecasted demand fluctuations.

## Technologies Used

- **Python** for data processing and modeling
- **Pandas & NumPy** for data manipulation
- **Matplotlib & Seaborn** for data visualization
- **Scikit-learn** for machine learning implementation
- **Jupyter Notebook** for development and documentation

## How to Use

1. Clone this repository
2. Install required dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter notebook `upcoming-product-demand.ipynb`

## Future Improvements

- Implement more advanced time series models (ARIMA, Prophet)
- Incorporate external factors like promotions and holidays
- Develop product-specific forecasting models
- Create an interactive dashboard for real-time forecasting

## Author

- **Shohinur Pervez Shohan**

---

*This project was completed as part of the Intern Intelligence internship program.*