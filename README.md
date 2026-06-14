# Startup Founder Burnout Prediction
## Data 515: Advanced Machine Learning - Willamette University

Predicting founder burnout and startup failure risk using machine-learning. 

## What This Project Is

Founder burnout is a real problem in the startup world, but it's rarely stuided with data. We used a dataset of 50,000+ startup founders (synthetic so we are not creating a PII issue) to build models that preict burnout severity, shutdown risk, and startup failure. 


## The Dataset

`startup_founder_burnout_2026.csv` - 50,000+ rows, 30 columns covering: 

- Founder background (age, experience, founder type)
- Work patterns (weekly hours, sleep, vacation days)
- Stress indicators (stress score, decision fatigure, investor pressure)
- Business context (funding stage, industry, runaway remaining)

In addition to these labels we will be creating our own such as:
- burnout level
- shutdown risk
- startup failure flag


## Models We're Comparing

- XGBoost
- LightGBM
- Random Forest

Hyperparameter tuning done with Optuna
