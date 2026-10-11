# AI-Driven Logistics and Shipment Analytics

**Author:** Vaibhavi Kadam  
**Internship:** AICTE | IBM SkillsBuild Data Analytics with AI | BharatCares

## Overview
Shipment data cleaning, exploratory analysis, visualization, and a baseline Random Forest regression model for delivery delay.

## Dataset
Suggested source: [DataCo SMART Supply Chain Dataset (Kaggle)](https://www.kaggle.com/datasets/shashwatwork/dataco-smart-supply-chain-for-big-data-analysis). Download a permitted copy and prepare it as `logistics_data.csv`. The notebook expects a target column called `Delivery_Delay_Days`.

**Important:** Without that CSV, the notebook creates synthetic demo data only so the code can run. Do not report demo results as real-world findings.

## Technologies
Python, pandas, NumPy, Matplotlib, scikit-learn, Jupyter Notebook.

## Run
1. Install Python 3.10+.
2. Run `pip install -r requirements.txt`.
3. Place prepared data as `logistics_data.csv` in this folder (optional for demo).
4. Open `Vaibhavi_Logistics_Analytics.ipynb` in Jupyter and run all cells.

## Outputs
`cleaned_logistics_data.csv` and `model_evaluation_summary.csv`.

## Methods
Data quality checks, cleaning, EDA, visualizations, train/test split, imputation, scaling, one-hot encoding, Random Forest regression, MAE/RMSE/R² evaluation.

## Limitations
This is a learning template. Validate with real data, check for leakage, and update the report with actual results before submission.
