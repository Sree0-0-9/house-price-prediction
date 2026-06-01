# House Price Prediction

This project builds a regression workflow for predicting residential house prices from imperfect real-world style housing data.

## Business Problem

Accurate house price prediction supports property valuation, lending decisions, market analysis, and investment planning. This project focuses on preparing messy housing data, selecting a regression model, and interpreting the features that influence predicted sale price.

## What This Project Demonstrates

- Data preprocessing for missing values and inconsistent feature quality
- Train/test splitting and model evaluation
- Cross-validation for model selection
- Hyperparameter tuning using `GridSearchCV`
- Prediction visualisation and feature-importance interpretation

## Key Findings

- Data quality and feature preparation are central to reliable house price prediction.
- Cross-validation and tuning provide a more robust model selection process than relying on a single train/test split.
- Feature-importance review helps translate model output into property and lending-relevant interpretation.

## Business Recommendation

Use regression models to support valuation and risk review, but pair model estimates with market context, property-specific judgement, and data-quality checks before using predictions in lending or investment decisions.

## Tools Used

- Python
- pandas
- NumPy
- scikit-learn
- Matplotlib

## Repository Structure

```text
.
├── data/
│   └── house_prices.csv
├── notebooks/
│   └── house_price_prediction.ipynb
└── README.md
```

## Portfolio Note

This is a public portfolio version prepared from academic analytics work. Student IDs and course-submission wording have been removed.
