# Car Price Prediction using Regression Models 🚗💰

## 📌 Overview
This project predicts car prices using three regression models:
- **Linear Regression**
- **Ridge Regression**
- **Lasso Regression**

## 📊 Results
| Model  | R² Score |
|--------|---------|
| Linear Regression | **0.91** |
| Ridge Regression | **0.91** |
| Lasso Regression | **0.91** |

### **🔍 Key Observations**
- Since all models have the same **R² score (0.91)**, it indicates that:
  - No overfitting is present.
  - No strong multicollinearity is affecting the model.
  - All features contribute to the predictions.
- The best choice is **Linear Regression** since it is simpler and performs the same as Ridge and Lasso.

## 📂 Dataset
- **Source**: Kaggle Car Price Dataset
- **Features Used**: Engine Size, Mileage, Doors, Owner Count, etc.
- **Target Variable**: Price
