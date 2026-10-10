# House Price Prediction Using Linear Regression

## Internship
**Organization:** Oasis Infobyte  
**Program:** Data Analytics Internship  
**Task:** Level 2 – Task 01  
**Project Type:** Machine Learning / Regression

## Project Overview
This project focuses on predicting house prices using Linear Regression, a supervised machine learning algorithm. The dataset contains housing-related features such as area, number of bedrooms, bathrooms, floors, year built, location, condition, and garage availability.

The objective is to explore the dataset, preprocess the features, train a regression model, and evaluate its performance on unseen data.

## Objectives
- Explore and understand the housing dataset.
- Check for missing values and duplicate records.
- Perform exploratory data analysis (EDA).
- Preprocess numerical and categorical features.
- Train a Linear Regression model.
- Evaluate model performance using regression metrics.
- Visualize actual versus predicted prices and analyze residuals.

## Dataset Description
The dataset contains **2,000 records and 10 columns**.

Key features include:
- `Area`
- `Bedrooms`
- `Bathrooms`
- `Floors`
- `YearBuilt`
- `Location`
- `Condition`
- `Garage`

**Target variable:** `Price`

The `Id` column is excluded from model training because it is an identifier rather than a meaningful housing feature.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Google Colab
- Jupyter Notebook

## Methodology
1. Load and inspect the dataset.
2. Check missing values, duplicates, and descriptive statistics.
3. Perform exploratory data analysis using charts and a correlation heatmap.
4. Split the data into training and testing sets using an 80:20 ratio.
5. Handle numerical and categorical features using preprocessing pipelines.
6. Train a Linear Regression model.
7. Evaluate predictions using MSE, RMSE, MAE, and R².
8. Visualize prediction results and examine model coefficients.
9. Compare the results with Ridge Regression.

## Model Evaluation
The notebook produced the following test-set results:

| Metric | Result |
|---|---:|
| Mean Squared Error (MSE) | 78,321,466,146.03 |
| Root Mean Squared Error (RMSE) | 279,859.73 |
| Mean Absolute Error (MAE) | 243,241.98 |
| R² Score | -0.0067 |

## Conclusion
The Linear Regression model was trained and evaluated using the available housing features. The negative R² score indicates that the model performed slightly worse than a baseline that predicts the mean price of the test set.

The limited predictive performance may be related to weak relationships between the available features and house prices. Further improvements could involve investigating the dataset, adding more informative features, and testing alternative regression models.

## Files
- `house_price_prediction.ipynb` — Notebook containing data analysis, preprocessing, model training, evaluation, and visualizations.
- `House Price Prediction Dataset.csv` — Dataset used for the analysis, if redistribution is permitted.

## Author
**Nithin Bharadwaj**

*Oasis Infobyte Data Analytics Internship – Level 2, Task 01*
