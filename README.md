# 🛒 Retail Price Optimization using Python

## 📌 Overview
This project focuses on **optimizing product prices** in a retail/cafe setting by analyzing **price elasticity of demand**.  
Using historical sales data, the project identifies how changes in price impact demand and helps determine **optimal pricing strategies** to maximize revenue and profit.

The analysis is entirely **data-driven**, leveraging Python for exploration, modeling, and simulation.

---

## 🎯 Business Objective
Retail businesses often struggle with:
- Setting prices that balance demand and profitability  
- Understanding how sensitive customers are to price changes  
- Making pricing decisions without quantitative backing  

This project aims to:
- Measure **price elasticity of demand**
- Identify **price-sensitive vs inelastic products**
- Recommend prices that **maximize profit**

---

## 🛠️ Tech Stack
- **Python**
- **Pandas & NumPy** – Data manipulation
- **Matplotlib / Seaborn** – Data visualization
- **Statsmodels** – Regression (OLS)
- **Jupyter Notebook**

---

## 📂 Dataset
- **Size:** 2,000+ sales records  
- **Features include:**
  - Product name  
  - Price  
  - Quantity sold  
  - Revenue / sales metrics  

Products analyzed include items such as burgers, coffee, coke, and lemonade.

---

## 🔍 Methodology

### 1️⃣ Exploratory Data Analysis (EDA)
- Analyzed sales distribution across products
- Studied price vs quantity trends
- Identified outliers and data inconsistencies

### 2️⃣ Price Elasticity Modeling
- Built **OLS regression models** of the form:  

 Quantity Sold = β₀ + β₁ × Price

- Interpreted regression coefficients to determine:
- Price sensitivity
- Elastic vs inelastic demand

### 3️⃣ Profit Simulation
- Simulated demand at different price points
- Evaluated revenue and profit outcomes
- Identified **optimal price ranges** for maximum profitability

---

## 📈 Key Insights
- Certain products (e.g., burgers) showed **high price sensitivity**, where small price increases significantly reduced demand  
- Other items were relatively **price inelastic**, allowing higher margins  
- Optimal pricing is **product-specific**, not one-size-fits-all  

📌 *Example:*  
Burger demand showed high elasticity (price coefficient ≈ **-9.33**, R² ≈ **0.486**), indicating strong customer sensitivity to price changes.

---
### Price vs Quantity Relationship
This graph shows how demand changes with price for different retail products.
It helps visually identify price-sensitive items.
<img width="964" height="810" alt="image" src="https://github.com/user-attachments/assets/e04e12b5-562a-428b-ab5c-7fcab879a869" />

### Product Price Prediction
This image shows the price prediction for the burgers, coke , lemonade and coffee.
<img width="964" height="810" alt="Screenshot 2025-12-25 212040" src="https://github.com/user-attachments/assets/03e19c0a-e47b-4b73-ba64-15f0e298678f" />


## 🚀 Business Impact
- Enables **data-backed pricing decisions**
- Helps maximize profit without blindly increasing prices
- Demonstrates how analytics can directly influence revenue strategy

---

## 📌 What I Learned
- Applying regression analysis to real business problems  
- Translating statistical outputs into actionable insights  
- Using simulations to support decision-making  
- Understanding real-world pricing strategy in retail

---

## ▶️ How to Run the Project
1. Clone the repository
2. Open the Jupyter Notebook:
 ```bash
 jupyter notebook Retail_price_optimization.ipynb
```
3. Run cells sequentially to view analysis and results
 
