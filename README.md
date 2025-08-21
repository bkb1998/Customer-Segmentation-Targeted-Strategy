# AdventureWorks Market Segmentation & Sales Analysis  

## 📌 Project Overview  
This project analyzes **AdventureWorks sales data** to extract insights on customer behavior, product performance, and profitability. Using **Python (machine learning + forecasting)** and **Power BI dashboards**, the project demonstrates how raw transactional data can be transformed into **strategic business intelligence**.  

## 🔑 Key Objectives  
- Segment customers based on **spending habits & regions**.  
- Identify drivers of **repeat purchases & loyalty**.  
- Understand **factors influencing purchase decisions**.  
- Forecast **future sales and profit** by category.  
- Deliver insights through **interactive Power BI dashboards**.  

---

## 📊 Power BI Dashboards  

## Executive Dashboard – KPIs (Revenue, Profit, Orders, Returns)
<img width="1462" height="820" alt="image" src="https://github.com/user-attachments/assets/5db43c0a-5917-4a80-8931-76fca92aafa2" />
  
## Customer Dashboard – Demographics, segmentation, loyalty
<img width="1462" height="824" alt="image" src="https://github.com/user-attachments/assets/58c51717-6b2a-4046-86c7-7646b167e02c" />
  
## Product Dashboard – Detailed analysis of top-selling products
<img width="1462" height="819" alt="image" src="https://github.com/user-attachments/assets/6ff1ede3-9b6c-4d4a-8a54-e473a32a1564" />
 
## Global Distribution Dashboard – Geographic customer base
<img width="1462" height="819" alt="image" src="https://github.com/user-attachments/assets/9e20a923-7cda-4ceb-9fd7-47a0156344a6" />
 

---

## 🛠 Methodology  

<img width="1462" height="819" alt="image" src="https://github.com/user-attachments/assets/fd7f9be9-5a4c-4109-b350-9e7dea784b61" />

### 1. Data Cleaning & Preprocessing  
- Handled missing values in **Gender, ProductStyle, ProductColor**.  
- Created features: **PurchaseFrequency, TotalSpend, DiscountMargin, ProfitMargin, Age, DistinctProducts**.  

### 2. Customer Segmentation (K-Means)  
- Used **Elbow method & Silhouette score** to determine optimal clusters.  
- Findings:
<img width="811" height="479" alt="image" src="https://github.com/user-attachments/assets/e544930d-29e8-4f55-842c-2bbafe542d72" />
  
  - **Cluster 0**
    - Higher total spend & purchase frequency compared to other groups.
    - Strong representation from Australia, Canada, and UK.
    - Customers purchase a broader range of products (diverse interests). 
  - **Cluster 1**
    - Lower spending & purchase frequency, more targeted purchases.
    - Dominated by regions like Southwest, Northwest, and France.
    - Tend to focus on specific products rather than variety.  

### 3. Repeat Purchase Prediction (Decision Tree)  
- Model achieved ~89% accuracy in predicting repeat buyers.
- Discounts & product variety are key drivers of loyalty.
- Strong precision in identifying non-repeat customers → useful for targeted retention campaigns. 

### 4. Factors Influencing Purchase (Gradient Boosting)
<img width="926" height="532" alt="image" src="https://github.com/user-attachments/assets/0618d803-67d6-4d19-b7d9-a3028cedbe38" />

- Target: **OrderQuantity**  
- Evaluation: MAE = 0.14 | R² = 0.65  
- Top drivers: **Discount Price, PriceDiscountRatio, ProductPrice, DiscountEffectiveness**.
- Discount Price is the strongest factor influencing order quantity.
- Price-to-Discount Ratio and Discount Effectiveness significantly affect purchase decisions.
- Demographics (age, income) play a smaller but measurable role.

### 5. Forecasting Sales & Profit (ARIMA)  
- Forecast horizon: **12 months**
- **Bikes**:: Strong, consistent growth — should remain a key focus.
- **Accessories**: Stable sales, but profit volatility suggests pricing strategy adjustments.
- **Clothing**: Emerging growth opportunity — requires inventory scaling & targeted marketing.
- Key Insight:  
  - Forecasting supports proactive inventory planning and category-specific marketing strategies for the next 12 months.

---

## 📈 Results & Recommendations  
1. **Segmented Marketing** – Premium offers for high-value clusters, discounts for low-value clusters.  
2. **Loyalty Programs** – Target repeat buyers with tailored campaigns.  
3. **Pricing Optimization** – Focus on effective discounts.  
4. **Category Growth** – Scale **Bikes & Clothing** ahead of demand.  
5. **Returns Management** – Address high return rates in **Clothing**.  

---

## 🛠 Tech Stack  
- **Python**: pandas, numpy, scikit-learn, matplotlib, statsmodels, joblib  
- **Power BI**: Dashboards for executives & product managers  
- **Machine Learning**: K-Means, Decision Tree, Gradient Boost Regressor, ARIMA  

---

