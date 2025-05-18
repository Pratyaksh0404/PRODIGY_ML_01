# 🏡 House Price Prediction using Linear Regression
## 🔍 Problem Statement

Predict the **SalePrice** of houses using the following features:

- GrLivArea (Above ground living area)
- BedroomAbvGr (Number of bedrooms above ground)
- FullBath (Full bathrooms)
- HalfBath (Half bathrooms)

---
## 📈 Model Details

- **Model Used**: Linear Regression
- **Feature Engineering**:
  - Log transformation of target
  - Polynomial features up to degree 3
  - Feature scaling (StandardScaler)
- **Evaluation Metrics**:
  - RMSE: `47,419.13`
  - R² Score: `0.7068`
  - MAE: `31,698.34`
  - MAPE: `19.25%`

---

## 📁 `requirements.txt`

```txt
pandas
numpy
scikit-learn
matplotlib
