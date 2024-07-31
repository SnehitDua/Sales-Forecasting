# Sales Forecasting

This repository contains a project focused on sales forecasting using time series analysis techniques. The goal is to predict future sales values based on historical data.

## Project Structure

### 1. **Time Series Analysis**
The project begins with exploratory data analysis (EDA) to understand the data structure, trends, and patterns.

### 2. **Exploratory Data Analysis (EDA)**
- **Data Loading and Preprocessing:** The dataset is loaded and preprocessed, including conversion of date columns and extraction of additional features like year, month, and day.
- **Grouping and Aggregation:** Data is grouped by different time periods and regions to analyze sales trends.
- **Visualizations:** Various visualizations are created to explore sales trends over different periods and regions.

### 3. **Sales Forecasting**
- **Data Transformation:** The time series data is resampled to a monthly frequency to align with the forecasting goal.
- **Modeling:** The SARIMAX model is employed for forecasting. The model considers both seasonal and non-seasonal components.
- **Evaluation:** The model's performance is evaluated using the Root Mean Squared Error (RMSE).

### 4. **Model Deployment**
- **Training on Full Dataset:** The model is retrained on the full dataset for deployment purposes.
- **Model Saving:** The trained model is saved using `pickle` for future use.

## Results and Conclusion
The forecasting model provides reasonable predictions, with an RMSE of 100. The project demonstrates a complete pipeline from data exploration to model deployment.
