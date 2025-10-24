# 🏡 California Housing Price Prediction

This project predicts median house prices in California using **Decision Tree** and **Random Forest** regressors.  
The model is trained on the classic **California Housing dataset** from Scikit-learn.

---

## 📊 Dataset
- Source: `fetch_california_housing()` from Scikit-learn  
- Features:
  - MedInc — Median income in the area  
  - HouseAge — Median age of houses  
  - Population — District population  
  - AveOccup — Average occupancy per household  
  - Latitude, Longitude — Geographic location  
- Target: Median house value (Price)

---

## 🧠 Models Compared
| Model | Validation MAE |
|--------|----------------|
| Decision Tree | ~0.4486 |
| Random Forest | ~0.3262 |

✅ **Random Forest outperformed the Decision Tree**, reducing the MAE by 27%.

---

## 🔍 Key Insights
- Median Income is the most important predictor of housing prices.
- Location (Latitude & Longitude) strongly influences pricing trends.

---

## ⚙️ Tech Stack
- Python
- Scikit-learn
- Pandas
- Matplotlib
- Google Colab

---

## 🚀 How to Run
1. Open the notebook in Google Colab.  
2. Run all cells sequentially.  
3. The trained model will be saved as `california_house_price_model.pkl`.

---

## 🌟 Future Improvements
- Hyperparameter tuning with GridSearchCV  
- Feature engineering (e.g., income per capita, distance from coast)  
- Deployment using Streamlit or Flask

---

📌 *Project by [Naresh Tallapaka]*
#MachineLearning #DataScience #RandomForest #Regression

