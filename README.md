# Retail Forecast Retention Analysis

A comprehensive retail business analysis project focused on understanding customer behavior, product performance, and revenue optimization opportunities.

## Environment Setup

This project uses conda for environment management. The `environment.yml` file contains all necessary dependencies.

### Prerequisites

- [Anaconda](https://www.anaconda.com/products/distribution) or [Miniconda](https://docs.conda.io/en/latest/miniconda.html)
- Python 3.10+

### Installation

1. **Clone or navigate to the project directory:**
   ```bash
   cd /home/rap24/retail-forecast-retention
   ```

2. **Create the conda environment:**
   ```bash
   conda env create -f environment.yml
   ```

3. **Activate the environment:**
   ```bash
   conda activate retail-forecast-retention
   ```

4. **Launch Jupyter Lab (optional):**
   ```bash
   jupyter lab
   ```

### Key Dependencies

The environment includes:

- **Data Science Core**: pandas, numpy, scipy
- **Visualization**: matplotlib, seaborn, plotly
- **Machine Learning & NLP**: scikit-learn, transformers, torch
- **Jupyter Environment**: jupyterlab, ipykernel, ipywidgets
- **API Integration**: openai for LLM-based product categorization
- **Data Processing**: xlsxwriter, openpyxl for Excel files

### Deactivation

To deactivate the environment:
```bash
conda deactivate
```

## Project Structure

- `retail_business_analysis.ipynb` - Main analysis notebook
- `datasets/` - Data files directory
- `environment.yml` - Conda environment specification
- `README.md` - This file

## Usage

1. Ensure your data files are in the `datasets/` directory
2. Activate the conda environment
3. Open and run the Jupyter notebook
4. Follow the analysis sections for comprehensive retail insights

## Features

- **Data Quality Assessment**: Comprehensive data cleaning and validation
- **Customer Analysis**: Cohort analysis, segmentation, and retention metrics  
- **Product Categorization**: AI-powered product classification using Hugging Face transformers
- **Business Performance**: KPI tracking, YoY analysis, and trend identification
- **Seasonality Analysis**: Demand patterns and forecasting insights
- **Visualization Dashboard**: Professional charts and business intelligence views
