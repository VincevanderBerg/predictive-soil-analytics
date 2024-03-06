# Predictive Soil Analytics: Titratable Acidity Modeling Ensemble

## Introduction

This comprehensive R workbook delves into a modeling workflow aimed at identifying and constructing the most accurate predictive model for titratable acidity using commonly analyzed soil attributes. Through meticulous analysis and model evaluation, this project showcases advanced skills in machine learning and data science.

## Exploratory Data Analysis (EDA)

The initial stage of this project involved a thorough Exploratory Data Analysis (EDA) to gain insights into the dataset. Notably, a comprehensive correlation analysis was conducted to understand the relationships between various soil attributes. Additionally, Principal Component Analysis (PCA) and Partial Least Squares (PLS) were employed to discern the most influential predictors within the dataset.

## Evaluated Models

The predictive models considered in this analysis include:

1. **Linear Regression:**
    - Standard linear regression model to establish a baseline performance.

2. **Decision Tree:**
    - A non-linear model that captures complex relationships within the data.

3. **Random Forest:**
    - Ensemble learning technique for improved predictive accuracy.

4. **MARS (Multivariate Adaptive Regression Splines):**
    - A sophisticated non-linear model that adapts to complex data patterns.

## Model Evaluation Results

After a rigorous evaluation process, the MARS model emerged as the top-performing model for predicting titratable acidity in soils. This result underscores the effectiveness of advanced modeling techniques in extracting meaningful patterns from the dataset. The detailed analysis and selection process showcased in this workbook demonstrate a mastery of machine learning methodologies and their application to real-world data challenges.

## Repository Contents

1. **Code:**
    - R-Markdown file detailing the entire modeling workflow.
    - Comprehensive visualizations including correlation matrices, PCA plots, and model performance graphs.
    - PDF report generated from the R-Markdown file.

2. **Data:**
    - Dataset used for training and evaluation. The original dataset was omitted as I am not the owner.  

3. **Documentation:**
    - This workbook was part of the initial process to publish an article in the South African Journal of Plant and Soil. The article can be found at the following link: https://www.tandfonline.com/doi/full/10.1080/02571862.2023.2212191.

## Next Steps

### Model Expansion

Planning to evaluate additional models to further enhance predictive accuracy. Potential models include:

- Support Vector Machines (SVM)
- Gradient Boosting Machines (GBM)
- Neural Networks

### Shiny Dashboard

Developing an interactive Shiny dashboard for users to engage with the project. This will provide a user-friendly interface for exploring the data, visualizations, and model predictions.

## Conclusion

Explore this repository to witness a meticulous journey through data exploration, model evaluation, and the ultimate selection of the MARS model for predicting titratable acidity in soils. This project serves as a testament to advanced skills in data science, showcasing a nuanced understanding of modeling techniques and their application to real-world environmental challenges.
