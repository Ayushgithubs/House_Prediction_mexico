# Mexico House Price Prediction

## Project Overview

This project aims to predict residential property prices in Mexico using machine learning techniques. The dataset contains information about properties such as location, area, number of bedrooms, bathrooms, parking spaces, and other housing characteristics. The goal is to identify the key factors affecting house prices and build an accurate predictive model that can estimate property values.

---

## Objectives

* Perform data cleaning and preprocessing on real estate data.
* Conduct Exploratory Data Analysis (EDA) to discover trends and patterns.
* Engineer relevant features to improve model performance.
* Build and evaluate multiple machine learning models for price prediction.
* Identify the most influential factors affecting property prices.
* Visualize insights through charts and dashboards.

---

## Dataset Information

* **Dataset:** Mexico City Real Estate Dataset
* **Source:** Kaggle
* **Records:** 7,000+ property listings
* **Features:** 10+ housing attributes including:

  * Location (City/State)
  * Latitude & Longitude
  * Property Type
  * Area (Square Meters)
  * Bedrooms
  * Bathrooms
  * Parking Spaces
  * Price (Target Variable)

---

## Technology Stack

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Jupyter Notebook
* Power BI (Optional)

---

## Project Workflow

### 1. Data Collection

* Imported the Mexico real estate dataset from Kaggle.
* Loaded data using Pandas.

### 2. Data Cleaning

* Handled missing values.
* Removed duplicate records.
* Treated outliers in price and area columns.
* Converted data types where necessary.

### 3. Exploratory Data Analysis (EDA)

* Analyzed price distributions.
* Studied relationships between property features and prices.
* Visualized trends using histograms, box plots, heatmaps, and scatter plots.

### 4. Feature Engineering

* Encoded categorical variables.
* Selected important features.
* Created derived features where applicable.

### 5. Model Building

The following models were implemented:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor
* XGBoost Regressor

### 6. Model Evaluation

Models were evaluated using:

* R² Score
* Mean Absolute Error (MAE)
* Mean Squared Error (MSE)
* Root Mean Squared Error (RMSE)

---

## Key Insights

* Property location significantly influences house prices.
* Larger properties generally command higher prices.
* Number of bedrooms and bathrooms positively impacts valuation.
* Geographic coordinates help improve prediction accuracy.
* Ensemble models outperform basic linear regression models.

---

## Results

* Achieved strong predictive performance using ensemble learning techniques.
* Random Forest/XGBoost provided the highest accuracy.
* Successfully identified the most important features affecting property prices.

---

## Future Enhancements

* Deploy the model using Flask or Streamlit.
* Integrate live property listings.
* Develop an interactive dashboard for users.
* Implement advanced feature engineering techniques.
* Explore deep learning approaches for prediction.

---

## Repository Structure

```text
Mexico-House-Price-Prediction/
│
├── data/
│   └── mexico_housing.csv
│
├── notebooks/
│   └── house_price_prediction.ipynb
│
├── visuals/
│   └── charts_and_graphs
│
├── models/
│   └── trained_model.pkl
│
├── README.md
│
└── requirements.txt
```

---

## Conclusion

This project demonstrates the end-to-end machine learning workflow for real estate price prediction, including data preprocessing, exploratory analysis, feature engineering, model development, and performance evaluation. The insights generated can assist buyers, sellers, and real estate professionals in understanding market trends and estimating property values more effectively.
