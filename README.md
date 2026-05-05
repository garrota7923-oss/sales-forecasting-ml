# Sales Forecasting & Customer Analytics

## Overview
Advanced sales analytics project implementing machine learning models for revenue forecasting, customer retention analysis, and market basket analysis. Built using Python with pandas, scikit-learn, and Plotly for interactive visualizations.

## Features

### 1. Sales Forecasting
- **Linear Regression Model**: Baseline prediction model
- **Random Forest Regressor**: Enhanced accuracy with ensemble learning
- **Performance Metrics**: MAE, RMSE, R² Score evaluation
- **6-Month Forward Forecast**: Predictive insights for future periods

### 2. Cohort Analysis
- Customer retention tracking across 12-month periods
- Heatmap visualization of retention rates
- Month-over-month retention metrics
- Actionable insights for customer reactivation strategies

### 3. Market Basket Analysis
- Product affinity analysis
- Cross-selling opportunity identification
- Bundle recommendation engine
- Support and confidence metrics for product pairs

## Technical Stack
- **Python 3.x**
- **Libraries**: pandas, numpy, scikit-learn, plotly
- **Models**: Linear Regression, Random Forest
- **Visualization**: Plotly (interactive charts and heatmaps)

## Dataset
Analysis based on 4-year sales data (2015-2018) containing:
- 9,800+ transactions
- Customer purchase history
- Product categories and sub-categories
- Order dates and shipping information

## Key Findings
- Random Forest model achieved **59.1% R² score** (outperforming Linear Regression)
- Average **16% customer retention** in first month
- Identified high-affinity product pairs for cross-selling strategies
- Estimated **$475K annual revenue opportunity** from improved bundling

## Usage
1. Load sales data in CSV format
2. Run preprocessing cells to clean and transform dates
3. Execute model training cells
4. Review visualizations and metrics
5. Adjust parameters as needed for different datasets

## Business Impact
- **Revenue Optimization**: Data-driven forecasting for inventory planning
- **Customer Retention**: Targeted reactivation campaigns based on cohort insights
- **Cross-Selling**: Strategic product bundling based on affinity analysis

## References
- [scikit-learn Documentation](https://scikit-learn.org/)
- [Plotly Python](https://plotly.com/python/)
- [pandas Documentation](https://pandas.pydata.org/)

---

**Author**: Data Science Student | UOC
**Last Updated**: 2026
