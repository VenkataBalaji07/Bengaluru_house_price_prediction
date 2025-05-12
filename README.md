
# 🏡 Bengaluru House Price Prediction

This project focuses on predicting house prices in Bengaluru using a dataset containing details like location, square footage, number of bedrooms, bathrooms, etc.

---

## 📌 Objective

To clean the data, analyze important features, and prepare it for accurate house price prediction.

---

## 📁 Files Included

- `bengaluru-house-price-prediction.ipynb` – Main Jupyter Notebook with step-by-step implementation.
- `Bengaluru_House_Data.csv` – Dataset used for analysis and prediction.

---

## 📊 Steps Performed

1. **Loaded the Dataset**  
   Used the Bengaluru house price dataset with features like `location`, `size`, `total_sqft`, `bath`, and `price`.

2. **Data Cleaning**  
   - Removed null and duplicate values.
   - Converted `size` column (e.g., 2 BHK, 3 Bedroom) into numerical format.
   - Handled ranges and non-numeric values in `total_sqft`.
   - Treated missing values in `bath`, `balcony`, and other columns.

3. **Feature Engineering**  
   - Extracted number of bedrooms (BHK) from the `size` column.
   - Calculated `price_per_sqft`.
   - Reduced unique values in the `location` column by grouping rare locations as “other”.

4. **Outlier Removal**  
   - Removed properties with abnormal `price_per_sqft`.
   - Filtered properties with unrealistic numbers of bathrooms or BHKs.

5. **Data Preparation**  
   - Final dataset was prepared with useful columns for prediction:
     - `location`, `total_sqft`, `bath`, `bhk`, `price`.

6. **Train-Test Split**  
   - Divided the data into training and testing sets.

7. **Prediction**  
   - Used a regression model to predict house prices based on input features.

---

## ✅ Final Output

- Cleaned dataset ready for prediction.
- Prediction function created that takes input features (location, sqft, BHK, bath) and returns the predicted house price.

---

## 📌 How to Use

1. Open the notebook: `bengaluru-house-price-prediction.ipynb`.
2. Follow each step to understand the data preparation and prediction process.
3. Use the final function to test with new input values.
"""

