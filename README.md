
# SalesSight AI – Sales Forecasting & Customer Churn Intelligence Dashboard

An interactive, AI-powered business intelligence application that combines time-series sales forecasting and machine learning-based customer churn prediction to help businesses explore historical trends, anticipate future sales and understand customer retention risks.

## Project Overview

SalesSight AI is a Python and Streamlit application designed to turn business datasets into actionable analytical insights.

The application brings together two analytical capabilities:

- **Sales Forecasting:** Uses Prophet time-series forecasting to analyse historical sales data and estimate future sales trends.
- **Customer Churn Prediction:** Uses an XGBoost classification model to analyse customer data and predict churn outcomes.

The goal is to make predictive analytics more accessible through an interactive dashboard.

## Key Features

### 1. Sales Forecasting
- Upload historical sales data in CSV format.
- Analyse historical sales trends.
- Generate future sales forecasts using Prophet.
- Visualize forecast trends and confidence intervals.
- Explore future sales patterns using the selected forecast horizon.

### 2. Customer Churn Prediction
- Upload customer datasets in CSV format.
- Train and evaluate a churn prediction model using XGBoost.
- Predict customer churn using a binary target variable.
- Explore model insights and feature importance.
- Understand factors associated with customer churn.

### 3. Interactive Dashboard
- Separate tabs for sales forecasting and churn prediction.
- Interactive data visualizations.
- CSV-based data input.
- Model performance insights.
- User-friendly Streamlit interface.

## Technology Stack

| Category | Technologies |
|---|---|
| Programming Language | Python |
| Dashboard | Streamlit |
| Sales Forecasting | Prophet |
| Machine Learning | XGBoost, Scikit-learn |
| Data Processing | Pandas |
| Visualization | Matplotlib |
| Data Input | CSV |

## Application Workflow

1. Upload the required business dataset.
2. Validate and prepare the input data.
3. Select the sales forecasting or churn prediction workflow.
4. Execute the corresponding analytical model.
5. Explore predictions, visualizations and model insights.
6. Interpret the outputs to support business decisions.

## Dataset Requirements

### Sales Forecasting Dataset

Upload a CSV file containing:

| Column | Description |
|---|---|
| Date | Historical sales date |
| Sales | Numeric sales value |

Example:

```csv
Date,Sales
2023-01-01,1234.56
2023-01-02,1300.45
2023-01-03,1450.20
```

Dates should follow the `YYYY-MM-DD` format.

### Customer Churn Dataset

Upload a CSV file containing customer features and a target column named `Churn`.

Example structure:

```csv
CustomerID,Feature1,Feature2,Churn
1001,Value1,Value2,0
1002,Value3,Value4,1
```

The target column uses:
- `0` – Customer retained
- `1` – Customer churned

The actual feature columns should be appropriate for the trained model and dataset.

## Installation & Setup

### Prerequisites

- Python installed
- pip package manager
- Git

### Step 1: Clone the repository

```bash
git clone "https://github.com/rayeesa163/SalesSight-AI-Forecasting-Churn-Intelligence-Dashboard..git"
```

### Step 2: Navigate to the project directory

```bash
cd "SalesSight-AI-Forecasting-Churn-Intelligence-Dashboard."
```

### Step 3: Install dependencies

```bash
pip install streamlit prophet xgboost scikit-learn pandas matplotlib
```

### Step 4: Run the application

```bash
python -m streamlit run notebooks/streamlit_app/sales_forecasting_suite_all.py
```

### Step 5: Open the dashboard

Open the local URL displayed in your terminal, usually:

```text
http://localhost:8501
```

## Demo Video

Watch the project demonstration:

[SalesSight AI – Project Demo](https://www.loom.com/share/0cd95c3e1ca94c36a97887b21d811590)

## Business Applications

SalesSight AI demonstrates how predictive analytics can support:

- Sales trend analysis and forecasting.
- Business planning and revenue estimation.
- Customer churn risk identification.
- Customer retention analysis.
- Data-driven business decision-making.

## Future Enhancements

- Interactive KPI and business performance dashboards.
- Advanced forecasting model comparisons.
- Customer segmentation and retention recommendations.
- Automated data quality checks.
- Cloud deployment and database integration.
- More detailed model evaluation and explainability.

## Author

**S. Rayeesa Tabasum Shaik**

B.Tech – Computer Science and Engineering (Artificial Intelligence)

GitHub: [rayeesa163](https://github.com/rayeesa163)

LinkedIn: [S. Rayeesa Tabasum](https://www.linkedin.com/in/s-rayeesa-tabasum-3b2526351/)

---

*Built with Python, Streamlit, Prophet and XGBoost.*


