# AI-Powered Sales Forecasting Dashboard
**Internship Project – Future Interns | Machine Learning Task 1**

---

## 🔹 Project Overview
This project is a predictive analytics dashboard designed for **retail businesses** to forecast future sales trends.  
Using historical transaction data, I built a **time series forecasting model** and created a **Power BI dashboard** to provide insights into sales trends, seasonality, and growth opportunities.

The dashboard helps business decision-makers answer questions like:
- What will be the monthly sales for the next year?
- Which months have peak sales and low seasons?
- How can we prepare for seasonal demand fluctuations?

---

## 🔹 Dataset
I used the **Superstore Sales Dataset** (or similar retail sales dataset from Kaggle).  
- File included: `data/sales_data.csv`  
- Aggregated sales **monthly** for forecasting
- Cleaned and processed for missing values, duplicates, and date formatting

---

## 🔹 Tools & Technologies
- **Programming Language:** Python
- **Libraries:** pandas, numpy, matplotlib, seaborn, prophet (Facebook)
- **Dashboard Tool:** Power BI Desktop
- **IDE:** Jupyter Notebook

---

## 🔹 Approach

1. **Data Cleaning & Preprocessing**
   - Removed duplicates
   - Filled missing values
   - Converted order dates to datetime
   - Aggregated sales monthly

2. **Feature Engineering**
   - Added Month & Year
   - Calculated rolling averages for trend smoothing
   - Added seasonal indicators (for holidays or peak months)

3. **Forecasting Model**
   - Used **Facebook Prophet** for time series forecasting
   - Trained model on historical monthly sales
   - Generated forecasts for next 12 months
   - Visualized trend, seasonality, and forecasted values

4. **Export for Dashboard**
   - Forecast results exported to `outputs/forecast.csv` for Power BI
   - Forecast plot saved as `outputs/forecast_plot.png`

---

## 🔹 Power BI Dashboard
The dashboard includes:
- **Line Chart:** Actual vs Forecasted Sales
- **KPI Cards:** Total Sales, Forecasted Growth (%)
- **Filters / Slicers:** Date, Category, Region
- **Insights Section:** Peak and Low Season Months

---

## 🔹 Folder Structure

