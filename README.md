# Demand Forecasting System

## Project Description
The **Demand Forecasting System** is designed to predict the future demand for a company's top-selling products based on historical sales data. The system aims to optimize inventory management and improve supply chain efficiency by accurately forecasting demand for the next 15 weeks. By leveraging various statistical and machine learning techniques, including time series models and regression analysis, this system assists businesses in making informed inventory decisions to meet customer demands effectively.

## Technologies Used
- **Python**: The primary programming language for data manipulation and analysis.
- **Pandas**: A library for data manipulation and analysis, essential for handling datasets.
- **NumPy**: A library for numerical computations and handling arrays.
- **Matplotlib** and **Seaborn**: Libraries for data visualization to understand trends and patterns in data.
- **Statsmodels**: A library for estimating statistical models, particularly time series models.
- **Facebook Prophet**: An open-source forecasting tool designed to handle time series data.
- **TensorFlow**: A deep learning library used for building LSTM models for demand forecasting.
- **XGBoost**: A powerful machine learning algorithm for regression tasks.
- **Streamlit**: A framework for creating interactive web applications to visualize forecasts and insights.

## Data Sources
This project utilizes the following datasets:
1. **Transactional Data**: Contains details of sales transactions, including stock codes, transaction dates, quantities sold, and prices.
2. **Customer Demographics**: Provides information about customers, such as age, income, and purchase frequency.
3. **Product Info**: Includes details about the products, such as category, price, and descriptions.

*Note: The datasets can be found in the `data/` folder.*