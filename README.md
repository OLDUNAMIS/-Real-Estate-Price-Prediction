
# 🏠 Real Estate Price Prediction

A machine learning project that predicts the **median house value** using real estate data, including features like location, number of rooms, area, and more.

## 📂 Project Overview

This project utilizes a dataset of 5,000 real estate records to build and evaluate a regression model that predicts house values. It includes data preprocessing, exploratory data analysis (EDA), feature engineering, and regression modeling.

## 📊 Dataset

- **File**: `real_estate_5000_rows.csv`
- **Rows**: 5,000 entries
- **Target Variable**: `median_house_value`
- **Features Include**:
  - Longitude, latitude
  - Total rooms
  - Total bedrooms
  - Population
  - Households
  - Median income
  - Ocean proximity

## 🚀 Project Workflow

1. **Problem Definition**  
   Predict housing values based on known attributes to assist in real estate price estimation and investment analysis.

2. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Normalization/standardization

3. **Exploratory Data Analysis**
   - Correlation analysis
   - Univariate & bivariate plots
   - Distribution of features and target

4. **Model Building**
   - Linear Regression
   - Performance metrics:
     - Mean Absolute Error (MAE)
     - Mean Squared Error (MSE)
     - R² Score

5. **Model Evaluation**
   - Evaluation plots (residuals, predicted vs. actual)
   - Interpretation of model performance

6. **Conclusion**
   - Insights into predictive power
   - Possible directions for model improvement

## 📁 Files in Repository

| File Name | Description |
|-----------|-------------|
| `my_ML_project.ipynb` | Jupyter notebook containing full workflow |
| `real_estate_5000_rows.csv` | Dataset used for model training and analysis |
| `README.md` | Project documentation |

## 🛠️ Requirements

To run the notebook, install the following Python libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## 📈 Sample Results

- **MAE**: ~61,968  
- **MSE**: ~6,047,096,525  
- **R² Score**: ~-0.07 (Note: Indicates poor predictive performance — further tuning required)

## 📌 Future Work

- Try more advanced models (Random Forest, XGBoost)
- Hyperparameter tuning
- Incorporate geospatial analysis
- Address model underfitting/overfitting

## 🙌 Acknowledgments

This project is part of a learning initiative on supervised machine learning, regression analysis, and real-world data handling.
