"# PredictionModelDhruv" 

For GitHub README, keep it short and professional. Use something like this:

# 🏠 House Price Prediction Model

A Machine Learning project that predicts house prices using **Random Forest Regression** based on house features such as living area, bedrooms, bathrooms, house age, distance from the city, and quality score.

---

## 📌 Workflow

### 1. Import Required Libraries

* NumPy
* Pandas
* Scikit-Learn

### 2. Load Dataset

* Read the `house_prices.csv` dataset using Pandas.

### 3. Data Cleaning

* Remove duplicate records.
* Handle missing values using median imputation.
* Remove extreme price outliers using the IQR method.

### 4. Data Preprocessing

* Separate features (`X`) and target (`price`).
* Apply feature scaling using `StandardScaler`.

### 5. Train-Test Split

* Split data into:

  * 80% Training Data
  * 20% Testing Data

### 6. Model Training

* Train a **Random Forest Regressor** with optimized parameters.

### 7. Model Evaluation

Evaluate model performance using:

* R² Score
* Mean Absolute Error (MAE)
* Root Mean Squared Error (RMSE)
* 5-Fold Cross Validation

### 8. Prediction

* Predict house prices for new/unseen house data.

---

## 🚀 How to Run

### Install Dependencies

```bash
pip install numpy pandas scikit-learn
```

### Run the Project

```bash
python house_price_prediction.py
```

---

## 📊 Features Used

* sqft_living
* bedrooms
* bathrooms
* floors
* house_age
* dist_to_city_km
* quality_score

### Target Variable

* price

---

## 🎯 Model

* Algorithm: Random Forest Regressor
* Feature Scaling: StandardScaler
* Validation: 5-Fold Cross Validation

---

## 📈 Output

The model provides:

* House Price Prediction
* Training R² Score
* Testing R² Score
* MAE
* RMSE
* Cross Validation Score

This is the level of detail generally expected in a professional GitHub README for an ML project.

