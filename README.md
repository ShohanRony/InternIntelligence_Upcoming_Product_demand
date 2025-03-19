# Product Demand Forecasting Project

This project focuses on analyzing historical product demand data and building a machine learning model to forecast future demand patterns.

## Dataset

This project uses the "Historical Product Demand" dataset from Kaggle:
- **Dataset**: [Product Demand Forecasting](https://www.kaggle.com/datasets/felixzhao/productdemandforecasting)
- **Description**: Contains historical product demand data for different products across various warehouses and product categories
- **Features**: Product_Code, Warehouse, Product_Category, Date, Order_Demand

## Project Overview

The project follows a standard data science workflow:

1. **Data Loading & Cleaning**
   - Converting date formats
   - Handling missing values
   - Converting order demand values to numeric format

2. **Feature Engineering**
   - Extracting time-based features (year, month, day)
   - Aggregating data at the monthly level for analysis

3. **Exploratory Data Analysis**
   - Visualizing historical demand patterns
   - Identifying seasonal trends

4. **Model Training**
   - Using RandomForest Regressor for demand forecasting
   - Training on historical data with time-based features

5. **Forecasting**
   - Predicting demand for the next 6 months
   - Evaluating model performance with MAE and RMSE metrics

## Results

- The model achieved a Mean Absolute Error (MAE) of approximately 6,044,362 and Root Mean Squared Error (RMSE) of about 7,302,280
- The forecasted demand for the first half of 2024 shows varying monthly patterns, with March and April having the highest predicted demand

## Technologies Used

- Python
- Pandas for data manipulation
- Matplotlib and Seaborn for visualization
- Scikit-learn for machine learning (RandomForest Regressor)

## How to Use

1. Clone this repository
2. Install required dependencies:
   ```
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Run the Jupyter notebook `upcoming-product-demand.ipynb`

## Author

- **Shohinur Pervez Shohan**