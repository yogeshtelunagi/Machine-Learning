# Machine-Learning
# Airbnb Price Prediction using Machine Learning

## Project Overview

This project aims to predict Airbnb listing prices in New York City using Machine Learning techniques. The project includes Exploratory Data Analysis (EDA), feature engineering, model building, model evaluation, and deployment using Streamlit.

The objective is to help hosts and customers understand the key factors that influence Airbnb pricing and provide accurate price predictions based on listing characteristics.

---

## Dataset

The dataset contains Airbnb listings with information such as:

* Neighbourhood Group
* Neighbourhood
* Room Type
* Latitude
* Longitude
* Price
* Minimum Nights
* Number of Reviews
* Reviews Per Month
* Availability (365 Days)
* Host Listings Count
* Listing Date

Additional engineered features include:

* Bedrooms
* Bathrooms
* Accommodates
* Property Type
* Amenities Count
* Review Score Rating
* Host Response Rate
* Instant Bookable

---

## Project Workflow

### 1. Data Cleaning

* Handled missing values
* Removed duplicates
* Converted date columns into datetime format
* Treated outliers in numerical features

### 2. Exploratory Data Analysis (EDA)

Performed various visualizations including:

* Price Distribution
* Room Type Distribution
* Average Price by Room Type
* Average Price by Borough
* Top Neighbourhood Analysis
* Monthly Listings Trend
* Availability vs Price
* Amenities vs Price
* Correlation Heatmap
* Price Distribution by Room Type (Boxplot)

### 3. Feature Engineering

Created additional features such as:

* Listing Month
* Listing Year
* Amenities Count
* Host Performance Indicators
* Property Attributes

### 4. Machine Learning Models

The following regression models were trained and evaluated:

* Linear Regression
* Decision Tree Regressor
* Random Forest Regressor

### Model Performance

| Model                   | R² Score |
| ----------------------- | -------: |
| Linear Regression       |     0.52 |
| Decision Tree Regressor |     0.21 |
| Random Forest Regressor |     0.56 |

Random Forest Regressor achieved the best overall performance and was selected as the final model.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-Learn
* Joblib
* Streamlit

---

## Streamlit Application

The project includes a Streamlit web application where users can:

* Enter listing information
* Predict Airbnb prices instantly
* Interact with a user-friendly interface

Run the application using:

```bash
streamlit run app.py
```

---

## Key Insights

* Location significantly influences Airbnb pricing.
* Entire homes/apartments are generally priced higher than private or shared rooms.
* Listings with better amenities and higher review scores tend to command higher prices.
* Availability and host-related factors also impact listing prices.

---

## Future Improvements

* Incorporate additional property-related features.
* Hyperparameter tuning for improved model performance.
* Deploy the application to Streamlit Cloud.
* Integrate real-time Airbnb listing data.

---

## Author

Yogesh Telunagi

Aspiring Data Analyst | Data Scientist

Machine Learning | SQL | Python | Data Visualization
