# Sales Forecasting Dashboard - Retail Analytics

## Project Overview
A predictive analytics dashboard for retail sales forecasting using Prophet ML model and Power BI visualization.

## 🎯 Objective
Build an interactive dashboard to help retail businesses forecast future sales, identify seasonal patterns, and make data-driven inventory decisions.

## 🛠️ Technologies Used
- **Python**: pandas, Prophet (Facebook's time series forecasting)
- **Power BI**: Interactive dashboard creation
- **Google Colab**: Data processing and model training
- **Data Source**: Superstore sales dataset (2014-2017)

## 📊 Key Features
- Historical sales trend analysis (2014-2017)
- 12-month sales forecast with confidence intervals
- Top product category breakdown
- Interactive year filtering
- Business recommendations based on insights
- Prophet model with cross-validation (MAE: 11,161, RMSE: 12,220)

## 📁 Project Structure
- `data/`: Raw and processed datasets
- `notebooks/`: Python notebooks for data analysis and forecasting
- `dashboard/`: Power BI dashboard file (.pbix)
- `screenshots/`: Dashboard visualizations

## 🚀 How to Run

### Prerequisites
- Python 3.8+
- Power BI Desktop
- Google Colab (optional)

### Steps
1. Clone this repository
2. Open `Task1.ipynb` in Jupyter/Colab
3. Run all cells to generate forecast data
4. Open `"Sales_Forecast_Dashboard_Priya.pbix"` in Power BI Desktop
5. Refresh data sources if needed

## 📈 Dashboard Pages

### Page 1: Executive Summary
- 3 KPI cards (Total Sales, Avg Monthly Sales, Forecast)
- Historical sales trend chart
- 12-month forecast with confidence intervals
- Interactive year filter

### Page 2: Detailed Analytics
- Key business insights
- Business recommendations
- Model performance metrics
- Top product categories visualization

## 🔍 Key Insights
- Strong seasonal patterns with Q4 peaks (holiday season)
- Prophet model forecasts continued upward growth trend
- Technology category leads in sales (0.84M)
- Moderate forecast uncertainty indicated by confidence intervals

## 📊 Model Performance
- **MAE (Mean Absolute Error)**: 11,161
- **RMSE (Root Mean Squared Error)**: 12,220
- **Model**: Facebook Prophet with cross-validation

## 🎓 Business Recommendations
1. Increase inventory 2-3 months before Q4 holiday season
2. Plan targeted promotions during off-peak months (Feb-Apr)
3. Use forecast confidence bounds for risk-adjusted planning
4. Monitor actual sales vs forecast to refine predictions

## 📸 Screenshots

## 👩‍💻 Author
**Priyanka Juttu**
- Internship: Future Interns - Machine Learning
- Date: October 2025

## 📝 License
This project is for educational/internship purposes.
