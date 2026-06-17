# 🏠 Smart House Price Predictor

## Overview

Smart House Price Predictor is a Machine Learning web application that estimates house prices using a Random Forest Regressor trained on the California Housing Dataset.

The application provides a simple and user-friendly interface where users can enter house information and receive an estimated property value.

---

## Features

* House Price Prediction
* Random Forest Regressor
* Interactive Streamlit UI
* Feature Importance Visualization
* Actual vs Predicted Analysis
* House Price Distribution Analysis
* Indian Currency Display (₹)

---

## Dataset

California Housing Dataset

Features used include:

* Median Income
* Housing Age
* Total Rooms
* Total Bedrooms
* Population
* Households
* Geographic Information

Target:

* Median House Value

---

## Model Performance

* R² Score: 0.816
* MAE: ₹31,639 (approx.)

---

## Project Structure

smart-house-price-predictor/

├── app.py

├── model.pkl

├── housing.csv

├── requirements.txt

├── README.md

└── images/

---

## Visualizations

### House Price Distribution

![Price Distribution](images/price_distribution.png)

### Income vs House Price

![Income vs Price](images/income_vs_price.png)

### Actual vs Predicted

![Actual vs Predicted](images/actual_vs_predicted.png)

### Feature Importance

![Feature Importance](images/feature_importance.png)

---

## Installation

Clone the repository:

git clone https://github.com/yourusername/smart-house-price-predictor.git

Install dependencies:

pip install -r requirements.txt

Run the application:

streamlit run app.py

---

## Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib
* Joblib

---

## Future Improvements

* Advanced UI Design
* Dark Mode
* House Images
* Deployment on Streamlit Cloud
* More Accurate Feature Engineering

---

## Author

Built as a Machine Learning portfolio project to demonstrate data preprocessing, model building, evaluation, visualization, and deployment.
