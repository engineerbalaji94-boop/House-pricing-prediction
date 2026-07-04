# 🏠 House Price Prediction using Machine Learning

## 📌 Project Overview
This project builds an end-to-end Machine Learning pipeline to predict house prices based on property characteristics. It covers the complete workflow from data preprocessing and exploratory data analysis (EDA) to feature engineering, model building, evaluation, and future improvement suggestions.

---

## 📂 Dataset
The dataset contains information about residential properties, including:

- Area Type
- Availability
- Location
- Society
- Total Square Feet
- Number of Bedrooms (BHK)
- Bathrooms
- Balconies
- Price (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Seaborn
- Matplotlib
- Scikit-learn
- Category Encoders

---

## 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Missing value handling
- Median imputation for numerical features
- Group-based imputation for balcony values
- Removal of remaining missing records
- IQR-based outlier removal
- Target Encoding for categorical variables
- Robust Scaling for numerical variables

---

## 📊 Exploratory Data Analysis

EDA includes:

- Distribution plots
- Count plots
- Box plots
- Violin plots
- Joint plots
- Correlation heatmap
- Relationship analysis between features and price

---

## 🤖 Machine Learning Pipeline

The project uses a complete Gradient Boosting Regression pipeline consisting of:

- Target Encoding
- Robust Scaling
- Column Transformer
- Gradient Boosting Regressor
- 5-Fold Cross Validation

---

## 📈 Model Performance

Evaluation Metrics:

- R² Score ≈ 0.70
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)

---

## 🚀 Future Improvements

- Hyperparameter tuning using GridSearchCV or RandomizedSearchCV
- Feature importance analysis
- Try advanced ensemble models such as XGBoost, LightGBM, and CatBoost
- Feature engineering using price per square foot and location-based statistics

---

## 📁 Project Structure

```
House-pricing-prediction/
│
├── House_Price_Prediction.ipynb
├── Housing.csv
├── README.md
```

---

## 👨‍💻 Author

**Balaji**

Machine Learning Enthusiast | Data Science | Python | AI