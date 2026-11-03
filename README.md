# Retail Inventory & Demand Forecasting System

An end-to-end data analytics and machine learning project designed to analyze retail sales, forecast future product demand, and optimize inventory management using historical sales data.

## 1. Project Overview

The Retail Inventory & Demand Forecasting System helps businesses make data-driven inventory decisions by analyzing historical sales patterns and predicting future demand.

The project combines SQL-based data processing, Python-based machine learning, demand forecasting, inventory risk analysis, and Power BI visualization into one integrated analytics solution.

### Key Objectives
- Analyze historical retail sales data.
- Identify sales trends and demand patterns.
- Forecast product demand for the next 30 days.
- Compare actual sales with predicted demand.
- Identify inventory risks and potential stock shortages.
- Support better inventory planning and decision-making.

## 2. Project Architecture

```text
                 RETAIL SALES DATA
                        |
                        v
              DATA COLLECTION
                 (CSV Files)
                        |
                        v
              DATA CLEANING
               (SQL + Python)
                        |
                        v
             FEATURE ENGINEERING
          (Demand & Sales Features)
                        |
                        v
             DEMAND FORECASTING
               (Machine Learning)
                        |
              +---------+---------+
              |                   |
              v                   v
       DEMAND PREDICTION     MODEL EVALUATION
              |                   |
              v                   v
       30-DAY FORECAST       PERFORMANCE METRICS
              |
              v
        INVENTORY ANALYSIS
              |
              v
       INVENTORY RISK ANALYSIS
              |
              v
        POWER BI DASHBOARD
              |
              v
       BUSINESS INSIGHTS &
       DECISION SUPPORT
```

## 3. Technology Stack

| Technology | Purpose |
|---|---|
| Python | Data processing and machine learning |
| Pandas & NumPy | Data cleaning and analysis |
| Scikit-learn | Machine learning and model evaluation |
| SQL | Data cleaning and business analysis |
| Jupyter Notebook | Model development and experimentation |
| Power BI | Interactive dashboard and visualization |
| CSV | Dataset storage and data exchange |

## 4. Project Structure

```text
retail-inventory-demand-forecasting/
│
├── dashboard/
│   ├── Demand Drivers & Forecasting.PNG
│   ├── Inventory Health & Risk.PNG
│   └── inventory_analysis_dashboard.pbix
│
├── data/
│   ├── sales_data.csv
│   ├── sales_data_final.csv
│   ├── actuals_vs_predicted.csv
│   ├── forecast_30day.csv
│   ├── model_metrics.csv
│   └── risk_table.csv
│
├── notebook/
│   └── InventoryOptimizationAndDemandForecasting.ipynb
│
├── sql_queries/
│   ├── DataCleaning 1.sql
│   ├── FeatureEngineering 2.sql
│   └── Analysis 3.sql
│
└── README.md
```

## 5. Key Features

### A. Data Cleaning and Preparation
- Handle missing values and inconsistent records.
- Prepare historical retail sales data.
- Organize data for analysis and forecasting.

### B. Demand Forecasting
- Analyze historical demand patterns.
- Develop machine learning-based demand forecasting.
- Generate 30-day future demand predictions.

### C. Inventory Optimization
- Analyze inventory health and demand patterns.
- Identify potential inventory risks.
- Generate inventory risk reports to support stock planning.

### D. Model Evaluation
- Compare actual and predicted values.
- Evaluate forecasting performance using model metrics.
- Analyze prediction accuracy.

### E. Power BI Dashboard
- Demand drivers and forecasting visualization.
- Inventory health and risk analysis.
- Interactive business insights and performance monitoring.
 ## 6. Model Performance & Evaluation

The demand forecasting model was evaluated using multiple regression performance metrics to measure prediction errors and model effectiveness.

### Evaluation Results

| Evaluation Metric | Result |
|---|---:|
| Mean Absolute Error (MAE) | 17.92 |
| Root Mean Squared Error (RMSE) | 24.60 |
| R-Squared (R²) | 0.6897 |
| Mean Absolute Percentage Error (MAPE) | 26.02% |

### Performance Interpretation

- **MAE – 17.92:** Predictions differ from actual demand by approximately 17.92 units on average.
- **RMSE – 24.60:** Indicates the magnitude of prediction errors, with larger errors receiving more weight.
- **R² – 0.6897:** The model explains approximately 68.97% of the variance in the evaluated demand data.
- **MAPE – 26.02%:** Indicates an average absolute percentage error of approximately 26.02%, subject to the limitations of percentage-based evaluation.

### Model Assessment

The model demonstrates meaningful demand forecasting capability. However, further improvements in feature engineering, model selection, and hyperparameter tuning could improve prediction performance.

*Note: These results represent the current evaluation output and should be interpreted in the context of the dataset and validation methodology.*

## 7. Dashboard Preview

### Demand Drivers & Forecasting

![Demand Forecasting Dashboard](dashboard/Demand%20Drivers%20%26%20Forecasting.PNG)

### Inventory Health & Risk

![Inventory Risk Dashboard](dashboard/Inventory%20Health%20%26%20Risk.PNG)

## 8. Dataset Description

The project uses retail sales data containing historical transaction information.

The processed datasets include:

- `sales_data.csv` – Original sales dataset.
- `sales_data_final.csv` – Processed sales dataset.
- `forecast_30day.csv` – Future demand predictions.
- `actuals_vs_predicted.csv` – Actual and predicted demand comparison.
- `model_metrics.csv` – Model evaluation results.
- `risk_table.csv` – Inventory risk analysis.

## 9. Installation and Execution

### Step 1: Clone the Repository

```bash
git clone https://github.com/bhargavgopu-git/retail-inventory-demand-forecasting.git
```

### Step 2: Navigate to the Project

```bash
cd retail-inventory-demand-forecasting
```

### Step 3: Create a Virtual Environment

```bash
python3 -m venv .venv
```

Activate it on macOS:

```bash
source .venv/bin/activate
```

### Step 4: Install Dependencies

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Step 5: Run the Notebook

```bash
jupyter notebook
```

Open:

`notebook/InventoryOptimizationAndDemandForecasting.ipynb`

### Step 6: View the Dashboard

Open `dashboard/inventory_analysis_dashboard.pbix` using Microsoft Power BI Desktop.

## 10. Expected Outcomes

- Better understanding of retail sales and demand patterns.
- Data-driven demand forecasting.
- Early identification of inventory risks.
- Improved inventory planning and stock management.
- Clear business insights through interactive dashboards.

## 11. Future Enhancements

- Real-time inventory monitoring.
- Integration with live retail databases.
- Advanced forecasting models such as XGBoost and LSTM.
- Automated stock replenishment recommendations.
- Deployment as a web-based inventory analytics application.

## 12. Author

**Bhargav Gopu**

B.Tech – Data Science

Sreenidhi Institute of Science and Technology (SNIST)

- GitHub: https://github.com/bhargavgopu-git
- LinkedIn: https://www.linkedin.com/in/bhargav-gopu/

---

**Project:** Retail Inventory & Demand Forecasting System

**Domain:** Data Science | Retail Analytics | Machine Learning | Business Intelligence
