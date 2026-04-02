# Heart Disease UCI Dataset

This repository contains my submission for a project based on the **UCI Heart Disease dataset**.  
The objective of the notebook is to apply a complete **data mining pipeline**, from **exploratory data analysis** to **predictive modeling**, **evaluation**, and **model explainability**.

## Project Objective

The goal is not only to build a predictive model for heart disease detection, but also to justify each methodological choice and interpret the model in a transparent way.

The notebook includes:

- Exploratory Data Analysis (EDA)
- Data cleaning and preprocessing
- Missing value handling
- Feature engineering
- Model comparison with cross-validation
- Hyperparameter tuning
- Final evaluation on a held-out test set
- Threshold analysis
- Calibration analysis
- Explainability with SHAP

## Dataset

Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)

The target variable was transformed into a **binary classification problem**:

- `0` = no heart disease
- `1` = presence of heart disease

## Notebook

Main notebook: `Heart_Disease.ipynb`

The notebook is designed to be read from top to bottom as a structured end-to-end workflow.

## Main Approach

Several machine learning models were compared, including:

- Logistic Regression
- Support Vector Machine (SVM)
- Random Forest
- XGBoost

The final selected model was chosen based on predictive performance, stability, and interpretability.

## Key Takeaways

- Careful preprocessing and validation are essential on small clinical datasets.
- Simpler models can remain highly competitive on structured tabular data.
- Explainability is important in healthcare-oriented machine learning settings.
- Predictive performance must be interpreted with caution due to dataset size and potential bias.

## Limitations

This analysis has several limitations:

- relatively small dataset
- possible sampling bias
- binary simplification of the original target
- limited external validity
- some features may reflect variables collected during a diagnostic workflow rather than pure early screening

## How to Run

You can open the notebook directly in **Google Colab** or run it locally in Jupyter.

Recommended workflow:

1. Open the notebook
2. Run all cells from top to bottom
3. Review outputs, figures, and interpretation sections

## Author

**Mohamed BADAGUE**
