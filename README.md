# 🏠 House Price Prediction using Linear Regression

## 📌 Project Overview

This project implements a complete **Machine Learning Regression Pipeline** to predict house prices using the California Housing dataset.

The objective is to build a professional end-to-end Linear Regression model including:

- Data preprocessing
- Feature engineering
- Model training
- Evaluation
- Visualization
- Automated output saving

This project demonstrates practical implementation of supervised learning in a real-world scenario.

---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Google Colab

---

## 📊 Dataset Information

The dataset used is the **California Housing Dataset**.

Target Variable:
- `median_house_value`

Features include:
- Median income
- House age
- Average rooms
- Average bedrooms
- Population
- Households
- Latitude
- Longitude
- Ocean proximity (categorical)

Preprocessing performed:
- One-Hot Encoding for categorical column
- Missing value handling
- Feature scaling using StandardScaler

---

## ⚙️ Project Workflow

1. Create output directory
2. Load dataset
3. Perform preprocessing
4. Split dataset (Train/Test)
5. Apply feature scaling
6. Train Linear Regression model
7. Generate predictions
8. Evaluate using:
   - MAE (Mean Absolute Error)
   - RMSE (Root Mean Squared Error)
   - R² Score
9. Plot Predicted vs Actual values
10. Save all results automatically

---

## 📈 Model Evaluation Metrics

- **MAE** → Measures average absolute prediction error  
- **RMSE** → Penalizes large errors  
- **R² Score** → Measures goodness of fit  

Expected approximate results:

- MAE ≈ 40,000  
- RMSE ≈ 69,000  
- R² Score ≈ 0.65 – 0.70  

(Results may slightly vary)

---

## 📂 Output Files Generated

Inside the `outputs/` folder:

- `predictions.csv` → Actual vs Predicted values  
- `evaluation_report.txt` → Model performance report  
- `predicted_vs_actual.png` → Scatter plot  
- `feature_importance.csv` → Coefficient analysis  

All files are generated automatically — no manual screenshots required.

---

## 📌 Key Learning Outcomes

- Understanding regression modeling
- Importance of feature scaling
- Model evaluation techniques
- Interpretation of coefficients
- Structuring ML projects professionally
- Version control readiness (GitHub)

---

## 🧠 Feature Importance Interpretation

Positive coefficient → Increases house price  
Negative coefficient → Decreases house price  

The model identifies the most impactful factors influencing housing prices.

---

#Outputs
<img width="786" height="534" alt="Image" src="https://github.com/user-attachments/assets/608a28c4-c289-407b-8a9b-0546560cd471" />
<img width="981" height="702" alt="Image" src="https://github.com/user-attachments/assets/3a8fd512-7ba1-46a6-a209-d8e6f2964f55" />
