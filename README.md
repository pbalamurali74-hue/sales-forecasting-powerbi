# 📈 Sales Forecasting & Power BI Analytics

An end-to-end **Data Science and Business Intelligence** project developed during the Future Interns Machine Learning Internship.

The project uses the Sample Superstore dataset to analyze retail performance and forecast future sales while presenting the results through an interactive Power BI dashboard.

## What this project does
- Cleans and prepares 9,000+ transaction records.
- Performs exploratory sales analysis.
- Studies regional and category-level performance.
- Models monthly sales as a time series.
- Produces a 12-month sales forecast.
- Provides an executive Power BI dashboard with interactive filters.

## Architecture
```
Superstore Transactions
        ↓
Data Cleaning + EDA
        ↓
Monthly Time Series
        ↓
Forecasting Model
        ↓
Forecast Dataset
        ↓
Power BI Executive Dashboard
```

## Tech Stack
Python • Pandas • NumPy • Matplotlib • Seaborn • Prophet • Power BI

## Key business questions
- Which regions and categories generate the most sales?
- What seasonal patterns appear in historical demand?
- What sales levels can be expected over the next 12 months?
- How can forecasting support inventory planning?

## Run
```bash
pip install pandas numpy matplotlib seaborn prophet
jupyter notebook forecasting_model.ipynb
```

Open `Sales_Dashboard.pbix` with Power BI Desktop to explore the dashboard.

## Internship
**Future Interns — Machine Learning Internship, Task 1**

## Author
**Purushotham Balamurali**