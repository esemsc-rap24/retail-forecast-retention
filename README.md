# Retail Forecast & Customer Retention Analysis

A data science project that helps retail businesses understand customer behavior, optimize inventory through demand forecasting, and improve customer retention using machine learning.

---

## What This Project Does

This analysis toolkit provides three core capabilities:

### **Business Intelligence Dashboard**
- Deep dive into retail performance metrics
- Customer segmentation and behavioral analysis  
- Product performance and profitability insights
- Year-over-year growth trends and seasonality patterns

### **Demand Forecasting**
- Predict sales for the next 6 months
- Identify which products need restocking
- Understand seasonal demand patterns
- Inventory optimization recommendations

### **Customer 360 & Retention**
- Identify high-value customers at risk of churning
- Personalized product recommendations
- Customer lifetime value prediction
- Targeted retention campaign strategies

---

## Quick Start

### Prerequisites
- [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- 4GB+ RAM recommended for ML models

### Setup

```bash
# 1. Navigate to project directory
cd /home/rap24/retail-forecast-retention

# 2. Create and activate environment (includes all ML dependencies)
conda env create -f environment.yml
conda activate retail-forecast-retention

# 3. Launch Jupyter Lab
jupyter lab
```

## 📁 Project Structure

```
retail-forecast-retention/
├──  retail_business_analysis.ipynb    # Main business intelligence analysis
├──  demand_forecast.ipynb             # Sales forecasting & inventory planning  
├──  customer_360_clean.ipynb          # Customer analytics & retention
├──  Project Brief.md                  # Original requirements & objectives
├──  datasets/                         # Your retail transaction data
├──  docs/                            # Documentation & reports
├──  environment.yml                   # Python environment setup
└──  README.md                        # This guide
```

---

## How to Use

### Step 1: Prepare Your Data
Download the datasets data here (`retail_transaction_data.csv` is required): https://drive.google.com/drive/folders/1RI-00NTO-bOvxTPbvdQJ2eINg5CPZwK3?usp=sharing

Place your retail transaction CSV files in the `datasets/` folder, in the root of repository. 

### Step 2: Run the Analysis
Open the notebooks in this order:

1. **`retail_business_analysis.ipynb`** - Start here for overall business insights
2. **`demand_forecast.ipynb`** - Generate sales forecasts and inventory recommendations  
3. **`customer_360_clean.ipynb`** - Analyze customer behavior and retention

### Step 3: Get Insights
