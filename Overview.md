# Retail Sales Prediction Model

**Author**: Baraa A. Hakawati  
**Last Updated**: May 5, 2025

## 📊 Overview
This machine learning project predicts product sales for retail stores using product attributes (weight, category, price) and store characteristics (size, location type, establishment year). The model helps retailers optimize inventory management and identify high-potential products.

## 🔍 Key Insights

### 1. Price Has Strongest Correlation with Sales
![Sales vs Price Correlation](![download](https://github.com/user-attachments/assets/b585b53a-cb92-4167-89cc-e16435b0f380)
)
- Item_MRP (price) shows 0.57 correlation with sales (highest among all features)
- Higher-priced items consistently generate more revenue
- **Business Implication**: Strategic pricing adjustments could boost profitability

### 2. Supermarket Type1 Outperforms Other Formats
![Sales by Outlet Type](images/outlet_type_performance.png)
- Supermarket Type1 achieves 2.1× higher sales than Grocery Stores
- Medium-sized stores show 18% better performance than small stores
- **Business Implication**: Expansion strategy should prioritize high-performing formats

## 🚀 Model Performance

### Tuned Random Forest Regressor (Best Model)

| Metric        | Training | Test    |
|---------------|----------|---------|
| **R²**        | 0.702    | 0.588   |
| **RMSE**      | $939     | $1,066  |
| **MAE**       | $662     | $740    |

**Key Takeaways**:
- Explains **58.8%** of sales variation in unseen data
- Average prediction error: **$740** per product
- Minimal overfitting (training vs test performance gap <12%)

## 📂 Repository Structure
