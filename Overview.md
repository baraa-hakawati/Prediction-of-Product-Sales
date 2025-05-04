# Product Sales Prediction

## 📊 Overview
This project focuses on building a machine learning model to predict retail product sales using historical transactional data. The goal is to help retail businesses optimize inventory planning and make informed sales forecasts.

The notebook includes end-to-end data science workflow: data cleaning, exploratory analysis, feature engineering, model selection, and evaluation. This project follows the CRISP-DM methodology.

## 🔍 Key Insights
### 1. Sales Trends Vary by Product Category
Certain product categories such as **Household** and **Grocery** consistently show higher sales volume, indicating demand stability. This trend can inform stocking priorities.

![Sales by Category](images/sales_by_category.png)

### 2. Store Type A Generates Highest Revenue
Analysis revealed that **Store Type A** accounts for the highest sales, likely due to its size or location. This insight can guide future investments and marketing strategies.

![Sales by Store Type](images/sales_by_store_type.png)

## 🧠 Model Summary
We tested multiple regression models, and the best-performing model was a **Random Forest Regressor**, which provided robust predictions with good generalization.

### 📈 Evaluation Metrics:
- **R² Score**: 0.59 (on test data)
- **RMSE**: 1131.5  
- **MAE**: 890.4

These results suggest the model is moderately accurate and could be improved with more granular features (e.g., promotions, holidays, weather).

---

For a full technical overview and to explore the code, refer to the [Jupyter Notebook](sales_prediction_model.ipynb).
