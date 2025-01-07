# Capstone-Project
# Using Machine Learning to Identify Predictors of Micronutrient Deficiencies in Children in Ethiopia

## Overview
This project leverages machine learning to identify key predictors of micronutrient deficiencies in children under five years old in Ethiopia, using data from the 2019 Demographic and Health Survey (DHS). The analysis aims to provide actionable insights for targeted interventions to improve child health and nutrition outcomes.

## Objectives
1. Identify the most significant predictors of micronutrient deficiencies, more specifically Vitamin A
2. Evaluate the predictive accuracy of machine learning models in identifying micronutrient deficiencies.
3. Develop an interactive dashboard to visualize insights and model performance.

## Features
- **Data Preparation**: Cleaning, transformation, and encoding of DHS data.
- **Exploratory Data Analysis (EDA)**: Univariate, bivariate, and multivariate analyses to uncover patterns and relationships.
- **Predictive Modeling**:
  - Logistic Regression
  - Random Forest Classifier
  - Gradient Boosting (XGBoost)
- **Performance Metrics**: Evaluation using accuracy, precision, recall, F1-score, and AUC-ROC.
- **Interactive Dashboard**: Visualizations for data insights and model performance using Plotly.

## Data Source
The dataset is sourced from the 2019 Ethiopia Demographic and Health Survey (DHS). Access it here: [DHS Data](https://dhsprogram.com/methodology/survey/survey-display-551.cfm).

## Requirements
- Python 3.7+
- Required Libraries:
  - `pandas`
  - `numpy`
  - `seaborn`
  - `matplotlib`
  - `scikit-learn`
  - `xgboost`
  - `plotly`

Install dependencies using:
```bash
pip install -r requirements.txt
```

## Project Structure
```
├── data
│   └── path_to_dhs_data.csv    # Placeholder for the dataset
├── src
│   ├── data_preprocessing.py   # Data loading and preprocessing scripts
│   ├── eda.py                  # Exploratory Data Analysis scripts
│   ├── modeling.py             # Machine learning models
│   └── dashboard.py            # Interactive dashboard preparation
├── main.py                     # Entry point for the project
├── requirements.txt            # List of dependencies
├── README.md                   # Project documentation
```

## Usage
1. **Prepare the Dataset**: Place the DHS dataset in the `data` folder.
2. **Run the Project**:
    ```bash
    python main.py
    ```
3. **Explore the Dashboard**: Visualize insights and model performance in an interactive Plotly dashboard.

## Key Insights
- Significant predictors include child age, dietary diversity, maternal education, wealth index, and health interventions (e.g., Vitamin A supplementation).
- Machine learning models, particularly Random Forest and XGBoost, achieved high accuracy in predicting Vitamin A deficiencies.

## Results and Visualizations
Key findings and visualizations are accessible through the interactive dashboard, providing:
- Summary statistics and distributions.
- Correlations between predictors and deficiencies.
- Model performance metrics.

## Contribution
Contributions are welcome! Please submit a pull request or open an issue to suggest improvements or report bugs.

---
Developed by Essa Chanie Mussa, PhD
