# 🛍️ Customer Lifetime Value (CLV) Prediction  
**End-to-end Machine Learning project for predicting future customer spending using transactional retail data.**

---

## 📌 **Project Overview**

Customer Lifetime Value (CLV) is a critical metric that tells a business **how much revenue a customer will bring in the future**.  
This project builds a **90-day Future Spend Prediction Model** using:

- Transactional retail dataset  
- RFM-based features (Recency, Frequency, Monetary)  
- Temporal features  
- Machine learning models (Linear Regression, RandomForest, XGBoost)

The pipeline includes **data cleaning → feature engineering → modeling → evaluation → error analysis → model saving**.

This project is structured exactly like a **real IT industry ML pipeline**.

---

## 🧠 **Key Features of This Project**

✔ End-to-end **ML workflow** implemented  
✔ **RFM + behavior-based features**  
✔ Models trained:  
  - Linear Regression (baseline)  
  - RandomForest Regressor  
  - XGBoost Regressor  
✔ **Residual analysis & segmentation** (Recency / Frequency / Monetary segments)  
✔ **Model saving + inference-ready pipeline**  
✔ Clean, modular, scalable code structure  

---

🔍 Error Analysis

The notebook includes:

Residual plots

Predicted vs Actual chart

Customer segmentation error (based on RFM)

Top customers with highest prediction error

This section helps understand where the model struggles and why.

🛠️ Future Enhancements

Add Probabilistic CLV (BG/NBD + Gamma-Gamma)

Use sequence models (LSTM) for temporal CLV

Add Marketing features (campaign exposure, visit frequency)

Deploy using FastAPI

Add full Streamlit dashboard

👩‍💻 Author

Chandana Sree
GitHub: chandana-cham

