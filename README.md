# House Sales Prediction

Online property companies leverage machine learning techniques to provide valuations of houses, aiding buyers and sellers in making informed decisions. This project predicts house sales in King County, Washington State, USA, using historical data of houses sold between May 2014 and May 2015. The goal is to achieve a prediction accuracy of at least 75-80% and understand the factors responsible for higher property values ($650K and above).

## Problem Statement
This report aims to predict house sales in King County and analyze the factors influencing property values above $650K. Two models, Adaboost and Gradient Boosting Machine (GBM), are employed for prediction.

## Dataset Overview
- **Source**: Historic data of houses sold in King County between May 2014 to May 2015.and
- **Features**: The dataset comprises various features describing each house, such as area, number of bedrooms, bathrooms, etc.
- **Target Variable**: The target variable is the sale price of the houses.

## Libraries Used
- **NumPy**: For numerical computations.
- **Pandas**: For data manipulation and analysis.
- **XGBoost**: For implementing the XGBoost model.
- **Seaborn and Matplotlib**: For data visualization.
- **Scikit-learn**: For implementing machine learning models and evaluation metrics.
- **SciPy**: For statistical functions.
- **Time**: For tracking execution time.

## Approach
1. **Data Preprocessing**:
   - Cleaning the data, handling missing values, and encoding categorical variables.
2. **Exploratory Data Analysis (EDA)**:
   - Analyzing the relationship between various features and house sale prices.
   - Identifying correlations and filtering out negatively correlated columns.
3. **Feature Engineering**:
   - Selecting relevant features and preparing data for modeling.
4. **Model Building**:
   - Implementing Adaboost and Gradient Boosting Machine (GBM) models for house sales prediction.
5. **Model Evaluation**:
   - Assessing model performance using metrics such as accuracy, R-squared score, and explained variance score.

## Findings
After conducting extensive EDA and building the prediction models, it was observed that the Gradient Boosting Machine (GBM) model outperformed Adaboost, achieving an accuracy of 89% compared to 65% with Adaboost. Additionally, the analysis revealed key factors contributing to higher property values above $650K.

## Conclusion
The predictive models developed in this project can assist online property companies in accurately estimating house sales in King County, Washington. By understanding the factors influencing property values, stakeholders can make informed decisions and optimize their strategies for better outcomes.

For detailed implementation and code, refer to the Jupyter notebook provided in this repository.

Feel free to explore further and contribute to the enhancement of the project!
