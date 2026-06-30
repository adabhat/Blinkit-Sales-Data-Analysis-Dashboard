# Blinkit Sales & Inventory Analytics Dashboard
This project presents an interactive Excel dashboard built using Blinkit's retail sales dataset containing over 8,500 records. The dashboard analyzes sales performance, outlet performance, customer ratings, and product categories while extending the analysis through ABC Inventory Classification to support inventory planning and replenishment decisions.

---

## 📂 Project Files:
- 📊 **[Dashboard Excel File](./Blinkit_Dashboard-Sales_&_Inventory_Analytics.xlsx)**  
- 🗂 **[Dataset](./blinkit_dataset.xlsx)**  
- 🎥 **[Demo Video](./blinkit_dasboard_demonstration.mp4)**  

---
## ✔️ Business Requirements:
- Understand the impact of **Outlet Location (City Tiers)** on sales  
- Identify **underperforming outlet categories** (by Location, Type, and Size)  
- Analyze **rating patterns** to flag low-rated product groups  
- Study how **outlet establishment year** impacts sales performance  
- Identify **underperforming product types**  
- Analyze how **food fat content** is preferred across regions  
- Uncover insights to **optimize outlet distribution strategy**
- Prioritize product categories for **inventory planning using ABC Inventory Classification**

---

## ✅ Key Insights:
1️⃣ **High-size outlets**, though the fewest in number, bring in the highest average sales.  
Medium-sized outlets, despite being the most common, generate the lowest average sales.  

2️⃣ **Tier-2 cities**, although having fewer stores, have the highest average sales across all city tiers.  

3️⃣ A **shift in demand for items with fat content** — declining in Tier-1 and Tier-2 cities but steady or rising in Tier-3 — could reflect growing fitness or vegan lifestyle trends reaching Tier-1/2 before Tier-3.  

4️⃣ A **spike in sales in 2018** was mainly due to a Tier-3 Medium Supermarket 3 store ($130K in sales).  

5️⃣ **ABC Inventory Classification showed that just 8 of the 16 product categories generated nearly 80% of total sales**, highlighting clear priorities for inventory allocation and replenishment.

---
## 💡Business Recommendations:
1) **Re-assess outlet allocation** — expand High-Size outlets in Tier-2 cities (high sales despite fewer locations).  
2) **Re-evaluate Medium-Size outlets**, especially in Tier-1 and Tier-2 where they’re most common but least efficient.  
3) **Tailor product offerings by fat content** based on regional health trends.  
4) **Investigate anomalies** like the 2018 Tier-3 spike to replicate success.
5) Allocate inventory budgets based on ABC classification by **prioritizing Category A products, maintaining balanced stock for Category B, and reducing excess inventory for Category C products** to improve inventory efficiency.

---

## 📊 KPIs Designed:
- **Total Sales** by Outlet Size, Type, and Location  
- **Average Sales** per Outlet Category  
- **Store Count** by Outlet Location and Size Classification  
- **Average Product Rating** per Item Type  
- **Dynamic Star-Based Rating Visualization**  
- **Emoji-Based Sentiment Scoring** by Product Category  
- **Sales Distribution** by Year of Store Establishment  
- **Regional Preferences** by Fat Content Classification  
- **Peak Sales Year Identification** across All Outlets
- **ABC Inventory Classification** for inventory prioritization and replenishment planning

---

## 🛠 Tools Used:
- Excel (Pivot Tables, Pivot Charts, Conditional Formatting, Dynamic Formulas, Dashboard Design, ABC Inventory Classification, Custom Data Labels & Auto-updating Emoji/Star System)

---

## 📚 What I Learned:
- Designing a **visually dynamic Excel dashboard** that balances aesthetics, automation, and business value — even without VBA.  
- Implemented a **dynamic, auto-updating star rating system** and **emoji-based sentiment indicator** by item type.  
