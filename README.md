# Retail Sales Forecasting & Business Insights System

## 📌 Project Overview
This project focuses on forecasting weekly retail sales using historical Walmart data and machine learning models. The objective is to generate accurate sales predictions and transform them into actionable business insights through structured data processing and visualization-ready outputs.

The system follows an end-to-end analytics workflow including data cleaning, feature engineering, model training, evaluation, and export of final predictions for BI tools such as Power BI.

---

## 📂 Dataset Description
The project uses Walmart sales data consisting of:
- Store information
- Historical weekly sales
- Economic and seasonal features such as holidays and promotions

**Key files:**
- `train.csv` – Historical weekly sales data  
- `features.csv` – Additional economic and seasonal indicators  
- `stores.csv` – Store-level metadata  

---

## ⚙️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib  
- **Modeling:** Regression & Tree-based ML models  
- **Visualization:** Power BI (downstream consumption)  

---

## 🔄 Project Workflow
1. **Data Ingestion**
   - Loaded multiple CSV datasets and merged them using store and date keys.

2. **Data Cleaning & Preprocessing**
   - Handled missing values and data type inconsistencies.
   - Converted date fields for time-series analysis.
   - Scaled numerical features where required.

3. **Feature Engineering**
   - Created time-based features (year, month, week).
   - Integrated store and external economic indicators.
   - Prepared model-ready datasets.

4. **Model Development**
   - Trained multiple regression-based ML models.
   - Performed hyperparameter tuning using cross-validation.
   - Evaluated models using RMSE and R² score.

5. **Model Evaluation**
   - Compared models to select the best-performing estimator.
   - Ensured predictions were stable and generalizable.

6. **Final Output**
   - Generated weekly sales predictions.
   - Exported final predictions to Excel for Power BI dashboarding.

---

## 📊 Model Evaluation Metrics
- **RMSE (Root Mean Squared Error)**
- **R² Score (Coefficient of Determination)**

These metrics were used to compare model performance and select the optimal forecasting model.

---

## 📁 Output Files
- `final_predictions.xlsx` – Cleaned, model-predicted sales data ready for BI reporting.

---

## 🚀 Future Enhancements
- Incorporate deep learning models (LSTM) for time-series forecasting.
- Automate data pipelines using orchestration tools.
- Deploy the model as an API for real-time predictions.

---

## 👤 Author
Developed by Sagar Kumar 
Role: Data Analyst / Data Scientist / Data Engineer
