# Advanced EDA and Feature Engineering

This project cleans and explores an online-orders dataset and prepares it for machine-learning work.

## Project work

- Inspected structure, data types, duplicates and missing values
- Imputed the missing categorical `CouponCode` values using the mode
- Detected numerical outliers with the IQR method
- Preserved all rows and capped extreme `TotalPrice` values in a separate column
- Created date, coupon, conversion, value-band and log-transformed features
- Added validation checks and saved the final prepared dataset

## Files

- `Advanced_EDA_and_Feature_Engineering.ipynb` — complete analysis with outputs
- `Dataset_for_Data_Analytics.xlsx` — original dataset
- `cleaned_orders_with_features.csv` — cleaned and feature-engineered dataset
- `requirements.txt` — Python libraries used

## How to run

1. Install Python and Jupyter Notebook.
2. Open a terminal in this project folder.
3. Run:

```bash
pip install -r requirements.txt
jupyter notebook
```

4. Open `Advanced_EDA_and_Feature_Engineering.ipynb` and run all cells.

## Main result

The final dataset has 1,200 rows, no remaining missing values, no duplicate rows, and seven newly engineered features. The original `TotalPrice` is retained for transparency, while `TotalPrice_Capped` is available for models sensitive to outliers.

## AUTHOR
Abubaker Imran

