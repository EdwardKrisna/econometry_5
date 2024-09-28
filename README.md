# Birth Weight Analysis

This repository contains code and data for analyzing factors influencing birth weight using statistical models. The analysis primarily focuses on identifying the most significant predictors of low birth weight and evaluating model performance using various statistical tests.

**Note**: For a detailed explanation of the analysis, please refer to the [Birth Weight Analysis.pdf](Birth%20Weight%20Analysis.pdf) file.

## Project Overview

The goal of this project is to investigate the relationship between various factors and birth weight. It includes:

- **Data Preparation**: Cleaning and processing of birth weight data.
- **Exploratory Data Analysis (EDA)**: Understanding data distribution and correlations.
- **Model Building**: Constructing multiple models to predict birth weight.
- **Classical Assumptions Testing**: Checking linearity, multicollinearity, homoscedasticity, and normality of residuals.
- **Model Selection**: Using stepwise regression and polynomial models to select the best model.

## Dataset

The dataset used in this project contains the following columns:

- `id`: Identification code
- `low`: Birth weight indicator (1 if birth weight < 2500g, 0 otherwise)
- `age`: Mother's age
- `lwt`: Mother's weight at last menstrual period
- `race`: Mother's race
- `smoke`: Whether the mother smoked during pregnancy (0=no, 1=yes)
- `ptl`: Number of premature labor occurrences
- `ht`: History of hypertension (0=no, 1=yes)
- `ui`: Presence of uterine irritability (0=no, 1=yes)
- `ftv`: Number of visits to the physician during the first trimester
- `bwt`: Actual birth weight in grams
