# Argus Risk Analytics

## Probability of Default (PD) Modeling Framework

Argus Risk Analytics is an end-to-end quantitative finance project that estimates the Probability of Default (PD) of corporate borrowers using financial statement fundamentals and machine learning.

Inspired by institutional credit risk workflows, the project replicates the major stages of a modern PD modeling pipeline, including data ingestion, feature engineering, default labeling, model development, probability calibration, risk scoring, and performance evaluation.

## Key Features

 Financial data ingestion using Financial Modeling Prep (FMP) and SEC EDGAR
 Financial ratio engineering from corporate fundamentals
 Default labeling using Altman Z-Score and financial distress indicators
 Logistic Regression baseline model
 Gradient Boosting classifier for nonlinear risk prediction
 Probability calibration using Platt Scaling
 Corporate risk band classification
 Performance evaluation with ROC-AUC, KS Statistic, Brier Score, and Calibration Curves

## Technologies

 Python
 pandas
 NumPy
 scikit-learn
 SciPy
 Matplotlib
 Requests
 Joblib

## Models

The project evaluates multiple credit risk modeling approaches, combining traditional financial risk methods with machine learning techniques:

Altman Z-Score Benchmark — industry-standard financial distress indicator used as a baseline comparison
Logistic Regression — interpretable baseline model for Probability of Default estimation
Gradient Boosting Classifier — captures nonlinear relationships between financial variables
XGBoost Classifier — advanced boosting model for predictive risk classification
Probability Calibration — converts model outputs into reliable PD estimates for credit risk applications

## Project Workflow

1. Collect corporate financial statement data.
2. Clean and preprocess financial information.
3. Engineer financial ratios and risk features.
4. Generate default labels using credit risk methodologies.
5. Train and evaluate predictive models.
6. Calibrate predicted probabilities.
7. Score companies by estimated default probability.
8. Produce visualizations and risk reports.

## Applications

This project demonstrates concepts used in:

 Commercial and corporate banking
 Credit underwriting
 Basel III/IV Internal Ratings-Based (IRB) frameworks
 Expected Loss (EL) estimation
 Portfolio credit risk management
 Quantitative financial analysis


## Future Improvements

 Incorporate historical bankruptcy datasets
 Add macroeconomic variables
 Implement XGBoost and SHAP explainability
 Develop an interactive Streamlit dashboard
 Deploy as a FastAPI scoring service


## Disclaimer

This project was developed for educational and portfolio purposes to demonstrate quantitative finance, machine learning, and credit risk modeling techniques. It is not intended for production or investment decision-making.

## Results and Model Evaluation

The model evaluates corporate credit risk using multiple approaches, including statistical and machine learning-based methods
Key Outputs include:
- Financial ratio analysis and feature engineering
- PD scoring
- Corporate risk band classification (AAA-D)
- MOdel Comparision using
    -ROC-AUC
    -Gini coefficient
    -KS statistic
    -Calibration metrics

  The pipelines generates:
  - Firm level PD scores
  - Risk category assignments
  - Model validation reports
  - Credit risk distribution analysis
 
## Example Outputs
The notebook produces
- Credit Risk feature analysis
- Model classification reports
- Risk banded firm scoring
- PD distribution analysis
- Validation comparisions between Altman Z-score benchmark, logistic regression, gradient boosting and XGBoost.
