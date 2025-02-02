# Capstone-Project
# Using Machine Learning to Identify Predictors of Vitamin A Supplementation in Children Under Five in Ethiopia

## Overview
This project applies machine learning to analyze the 2019 Ethiopia Demographic and Health Survey (DHS) dataset to identify key predictors of Vitamin A supplementation in children under five. By leveraging advanced predictive models, the study aims to provide data-driven insights for policymakers, healthcare practitioners, and researchers to improve child nutrition outcomes in Ethiopia.

## Objectives
1. Identify significant predictors of Vitamin A supplementation in children under five.
2. Develop and compare the performance of machine learning models in predicting the likelihood of receiving 
   Vitamin A.
3. Provide insights to support policy decisions and targeted interventions.
4. Build an interactive dashboard to visualize data and model performance.

## Features
**1. Data Preparation**
- **Data Source**: 2019 Ethiopia DHS dataset
- **Cleaning**: Handled missing values, removed outliers, and standardized numerical features.
- **Feature Engineering**:
Encoded categorical variables (e.g., place of delivery, wealth index, and region).
Data Splitting: 80% training and 20% testing to ensure robust model evaluation
- **Exploratory Data Analysis (EDA)**: Univariate, bivariate, and multivariate analyses to uncover patterns and relationships.
**2. Exploratory Data Analysis (EDA)**

**3. Predictive Modeling**:
Developed and evaluated multiple machine learning models:
- Logistic Regression (Baseline Model)
- Decision Tree Classifier
- Random Forest Classifier (Best Performing Model)
- K-Nearest Neighbors (KNN)
- Support Vector Machine (SVM)
- Extreme Gradient Boosting (XGBoost)
- Light Gradient Boosting Machine (LightGBM)
- **Performance Metrics**: Evaluation using accuracy, precision, recall, F1-score, and AUC-ROC.
- **Interactive Dashboard**: Visualizations for data insights using Plotly.

## Data Source
The dataset is sourced from the 2019 Ethiopia Demographic and Health Survey (DHS). Access it here: [DHS Data](https://dhsprogram.com/methodology/survey/survey-display-551.cfm).

## Requirements
Install dependencies using:
```bash
pip install -r requirements.txt
```

## Project Structure
```
├── data
│   └── path_to_dhs_data.csv        # Placeholder for the dataset
├── src
│   ├── VitaminA_Supplement.ipynb   # Data loading and preprocessing scripts, EDA, and ML Models
│   ├    
│   ├            
│   └── Dashboard.ipynb            # Interactive dashboard preparation
├── requirements.txt               # List of dependencies
├── README.md                      # Project documentation
```

## Usage
1. **Prepare the Dataset**: Place the DHS dataset in the `data` folder.
2. **Run the Project**:
    ```bash
    python VitaminA_Supplement.py
    ```
3. **Explore the Dashboard**: Visualize insights and model performance in an interactive Plotly dashboard.

## Key Insights
- Significant predictors include child age, age of the mother, age of head, birth order and number of ANC visits, 
- Best Model Selection: Random Forest
Justification:
Highest accuracy (69%), ensuring correct classification in most cases.
Balanced tradeoff between precision (62%) and recall (51%).
Best AUC-ROC score (0.66), indicating good class discrimination.

- Feature importance analysis showed that child age, maternal age, and antenatal care visits were the most influential factors.
- 
**Results and Visualizations**
The interactive dashboard provides:
✅ Summary statistics and distributions of Vitamin A supplementation.
✅ Correlations between predictors and supplementation status using heatmaps.
✅ Machine learning model performance metrics (Accuracy, Precision, Recall, AUC-ROC).
✅ Feature importance rankings to highlight key variables affecting supplementation.

---
Developed by Essa Chanie Mussa, PhD
