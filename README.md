# Car Price Prediction with Machine Learning

## Project Overview
This project predicts the selling price of used cars using machine learning regression models. It follows a professional workflow with preprocessing, feature engineering, exploratory data analysis, model comparison, and final evaluation.

## Dataset
Used Cars dataset from Kaggle.

## Features Used
- Present Price
- Driven Kilometers
- Fuel Type
- Selling Type
- Transmission
- Owner
- Car Age

## Models Compared
- Linear Regression
- Random Forest Regressor
- Gradient Boosting Regressor

## Workflow
1. Load the dataset
2. Inspect and clean the data
3. Create `Car_Age`
4. Perform exploratory data analysis
5. Encode categorical features with One-Hot Encoding
6. Split the data into train and test sets
7. Train and compare models
8. Evaluate the best model
9. Test a sample prediction

## Files
- `car_price_prediction.ipynb`
- `car_data.csv`
- `README.md`
- `requirements.txt`

## How to Run
Install the dependencies:

```bash
pip install -r requirements.txt
```

Open the notebook:

```bash
jupyter notebook
```

Then run all cells in `car_price_prediction.ipynb`.