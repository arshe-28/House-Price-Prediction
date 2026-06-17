# House Price Prediction Using Machine Learning

## Project Overview

This project predicts house prices using machine learning techniques. The goal is to estimate the price of a house based on various property features like area, number of bedrooms, bathrooms, parking spaces, air conditioning, and furnishing status.

The project includes data exploration, cleaning, model building, evaluation, and visualization.

---

## Objective

* Explore and understand the housing dataset.
* Clean and process the data.
* Train machine learning models for price prediction.
* Compare the performance of different regression models.
* Visualize the data and model results.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Dataset

The project uses the **Housing.csv** dataset, which contains various house features and their corresponding prices.

Features include:

* Area
* Bedrooms
* Bathrooms
* Stories
* Main Road
* Guest Room
* Basement
* Hot Water Heating
* Air Conditioning
* Parking
* Preferred Area
* Furnishing Status

Target Variable:

* **Price**

---

## Machine Learning Models

Two regression models were implemented:

1. Linear Regression
2. Random Forest Regressor

The dataset was split into:

* **80% Training Data**
* **20% Testing Data**

---

## Model Performance

### Linear Regression

* MAE: **970,043.40**
* RMSE: **1,324,506.96**
* R² Score: **0.6529**

### Random Forest Regressor

* MAE: **1,021,546.04**
* RMSE: **1,400,565.97**
* R² Score: **0.6119**

Linear Regression performed better than Random Forest on this dataset.

---

## Visualizations

The project includes:

* Distribution of House Prices (Histogram)
* Correlation Heatmap
* Actual vs Predicted House Prices Scatter Plot

---

## Repository Structure

```text
House-Price-Prediction/
│
├── analysis.ipynb
├── Housing.csv
├── Summary.pdf
├── histogram.png
├── heatmap.png
├── actual_vs_predicted.png
```

---

## Conclusion

This project shows how machine learning can predict house prices based on property features. Data cleaning, feature engineering, model evaluation, and visualization were key in building an effective prediction model. Among the models used, **Linear Regression achieved better performance** on this dataset.

---

## Author

**Arshee Batliwala**
