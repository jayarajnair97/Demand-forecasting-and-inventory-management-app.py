# Demand-forecasting-and-inventory-management-app.py
# Demand Forecasting and Inventory Optimization

This project involves demand forecasting and inventory optimization using time series analysis. The aim is to predict demand and optimize inventory levels, which is crucial for businesses to efficiently allocate resources, manage inventory, and plan production. 

## Scope of the Project

Demand Forecasting involves predicting the quantity and pattern of customer orders, which is crucial for businesses to efficiently allocate resources, manage inventory, and plan production. Accurate demand forecasting enables companies to meet customer needs, avoid overstocking or understocking, and optimize their supply chain operations. Inventory Optimization aims to strike a balance between having sufficient stock to meet demand without carrying excess inventory that ties up capital and storage space. Effective inventory optimization helps businesses reduce carrying costs, improve cash flow, and enhance customer satisfaction. These concepts are especially relevant in retail, manufacturing, and distribution, where managing supply and demand dynamics is essential for profitability and customer satisfaction.

## Techniques/Tools Used

For demand forecasting, suitable forecasting models such as SARIMA (Seasonal Autoregressive Integrated Moving Average), and ARIMA (Autoregressive Integrated Moving Average) are used. After forecasting the demand, inventory levels are optimized using techniques such as safety stock, reorder points, and economic order quantity (EOQ) computations.

- **Demand Forecasting Techniques:**
    - SARIMA (Seasonal Autoregressive Integrated Moving Average)
    - ARIMA (Autoregressive Integrated Moving Average)
    - Exponential Smoothing

- **Inventory Optimization Techniques:**
    - Safety Stock
    - Reorder Points
    - Economic Order Quantity (EOQ) computations

## Steps in the Process

1. **Importing Libraries and Loading Dataset:**
    - Import necessary libraries such as pandas, numpy, plotly, matplotlib, and statsmodels.
    - Load the dataset containing demand and inventory data.

2. **Exploratory Data Analysis:**
    - Visualize demand and inventory trends over time using line plots.

3. **Demand Forecasting using SARIMA:**
    - Preprocess the time series data.
    - Plot ACF (Autocorrelation Function) and PACF (Partial Autocorrelation Function) to determine the orders of AR and MA terms.
    - Train the SARIMA model and forecast demand for future time periods.

4. **Inventory Optimization:**
    - Calculate optimal order quantity, reorder point, safety stock, and total cost based on the forecasted demand.

5. **Streamlit UI:**
    - Create a Streamlit app to display the dataset, demand forecasting results, and inventory optimization metrics.

## Findings

- **Optimal Order Quantity:** 236
- **Reorder Point:** 235.25
- **Safety Stock:** 114.45
- **Total Cost:** $561.80

The total cost is the sum of all the expenses related to inventory control. It includes holding costs and stockout costs. The optimal order quantity, reorder point, and safety stock calculated based on the forecasted demand help in efficiently managing inventory levels and ensuring customer satisfaction.
