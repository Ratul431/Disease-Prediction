# Disease Prediction from Medical Data

This repository contains the code and resources for building a machine learning model to predict diseases based on medical data. The project emphasizes data preprocessing, feature selection, and the evaluation of predictive models to achieve accurate disease predictions.

## Features

- **Exploratory Data Analysis (EDA)**:
  - Handling missing values effectively.
  - Removal of rows with invalid or zero values (e.g., `trestbps` values of 0).
  
- **Feature Selection**:
  - Implementation of statistical tests to identify the most predictive features:
    - Chi-Square Test for categorical features.
    - ANOVA F-test for numerical features.

- **Model Building**:
  - Utilizes multiple machine learning algorithms for heart disease prediction.

## Requirements

- **Programming Language**: Python
- **Libraries**:
  - Data Analysis: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn
  - Statistical Testing: SciPy (optional)

