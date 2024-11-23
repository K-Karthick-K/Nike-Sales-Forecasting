# Nike Sales Forecasting

**Objective:** Predict future sales for Nike products using time-series forecasting models.  
**Dataset:** Nike sales data with attributes such as `Invoice Date`, `Product`, `Region`, `Sales Method`, and `Total Sales`.  
**Tools Used:** Python, Google Colab, ARIMA, Prophet, matplotlib.  

## Key Steps
1. **Data Preprocessing:**
   - Aggregated sales data by `Invoice Date`.
   - Cleaned and transformed the data for analysis.
   - Visualized trends, seasonality, and residuals using decomposition.

2. **Modeling and Forecasting:**
   - Applied ARIMA to forecast sales for the next 30 days.
   - Used Prophet to capture seasonality and predict future trends.

3. **Evaluation:**
   - Evaluated models using RMSE and visualized actual vs. predicted sales.

Results
- **ARIMA RMSE:** [Insert Value].  
- **Prophet Analysis:** Effectively modeled seasonality and provided actionable forecasts.  

---

Files
- `Nike_Sales_Data.xlsx`: Original dataset.
- `Nike_Sales_Forecasting.ipynb`: Colab notebook with preprocessing, modeling, and evaluation.
- `Nike_Sales_Forecast.csv`: Forecasted sales data (next 30 days).


## Insights
- **Seasonality:** Identified peaks in sales around specific months.
- **Predicted Growth:** Forecasted consistent growth trends over the next 30 days.

## About
This project demonstrates time-series forecasting expertise using real-world data and statistical models. It highlights skills in Python, time-series analysis, and business forecasting.
