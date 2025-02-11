# Netflix-Pricing-Predictive-Model

Overview
This project explores Netflix's subscription pricing strategy across different markets by analyzing key socioeconomic factors such as GDP, population, and the freedom index. Using machine learning models in R, including LASSO regression and Random Forest, we predict optimal subscription pricing for new markets while ensuring competitiveness through benchmarking against competitors.

Project Workflow
1. Data Collection & Feature Engineering:
  Researched and engineered key socioeconomic features (GDP, population, freedom index) to enhance pricing predictions.
  Datasets and data processing file can be found under 'data cleaning' folder.
  Utilized R (dplyr, tidyr, readr) for data cleaning, transformation, and integration.
3. Model Development:
  Built LASSO regression using glmnet for feature selection and reducing multicollinearity.
  Developed a Random Forest model with randomForest to improve pricing prediction accuracy.
4. Model Validation & Benchmarking:
  Conducted horizontal benchmarking by comparing Netflix pricing with competitor streaming services across multiple countries.
  Ensured pricing competitiveness and market alignment based on model outputs.
