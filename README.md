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

- **Executive Dashboard** – KPIs (Revenue, Profit, Orders, Returns)
<img width="1462" height="820" alt="image" src="https://github.com/user-attachments/assets/5db43c0a-5917-4a80-8931-76fca92aafa2" />
  
- **Customer Dashboard** – Demographics, segmentation, loyalty
<img width="1462" height="824" alt="image" src="https://github.com/user-attachments/assets/58c51717-6b2a-4046-86c7-7646b167e02c" />
  
- **Product Dashboard** – Detailed analysis of top-selling products
<img width="1462" height="819" alt="image" src="https://github.com/user-attachments/assets/6ff1ede3-9b6c-4d4a-8a54-e473a32a1564" />
 
- **Global Distribution Dashboard** – Geographic customer base
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
  - **Cluster 0** – High-value customers (frequent, higher spend, diverse products).  
  - **Cluster 1** – Lower-value customers (targeted purchases, lower frequency).  

### 3. Repeat Purchase Prediction (Decision Tree)  
- Accuracy: **~89%**  
- Key insight: Discounts & varied product choices strongly affect repeat purchases.  

### 4. Factors Influencing Purchase (Gradient Boosting)  
- Target: **OrderQuantity**  
- Evaluation: MAE = 0.14 | R² = 0.65  
- Top drivers: **Discount Price, PriceDiscountRatio, ProductPrice, DiscountEffectiveness**.  

### 5. Forecasting Sales & Profit (ARIMA)  
- Forecast horizon: **12 months**  
- Insights:  
  - **Bikes**: strong, consistent growth.  
  - **Accessories**: stable sales, pricing improvements needed.  
  - **Clothing**: emerging opportunity for marketing & inventory push.  

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

