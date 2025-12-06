# 🍕 Pizza Sales Analysis Using SQL  
This project presents an end-to-end **SQL-based exploratory analysis** of a pizza store’s sales data. The objective is to uncover trends, revenue patterns, customer behavior, and performance metrics using structured SQL queries.

---

## 📊 Project Overview

Through SQL queries, this project answers key business questions such as:

- Total orders and total revenue generated  
- Most and least popular pizzas  
- Revenue contribution by each pizza  
- Most common pizza size  
- Hourly and daily order distribution  
- Category-wise sales insights  
- Cumulative revenue trends over time  

All insights are derived from SQL outputs presented in the full PDF report.

---

## 📁 Dataset Structure

Tables used in this analysis:

- **orders** — Contains order timestamp & order_id  
- **order_details** — Contains quantity, pizza_id, order_id  
- **pizzas** — Contains pizza_id, size, price  
- **pizza_types** — Contains name, category  

*(Structure inferred from report content.)*

---

# 🔍 Key Insights

## ✅ 1. Total Number of Orders  
**21,350 orders** were placed in the dataset.  
*(Source: Page 2)*

---

## 💰 2. Total Revenue Generated  
The total revenue from all pizza sales is approximately:  
**$3,130,020**  
*(Source: Page 3)*

---

## 🍕 3. Highest Priced Pizza  
The costliest pizza found in the dataset is:  
**The Greek XXL — $35.95**  
*(Source: Page 4)*

---

## 📈 4. Revenue Contribution by Pizza Type  
Each pizza type was analyzed to compute its percentage contribution to total revenue.  
*(Source: Page 5)*

---

## 📏 5. Most Common Pizza Size  
The most frequently ordered pizza size is:  
**S (Small)**  
*(Source: Page 6)*

---

## 🏆 6. Top 5 Most Ordered Pizzas  
Based on total quantities ordered:  
1. The Big Meat Pizza — **1483 orders**  
2. The Barbecue Chicken Pizza — **867 orders**  
3. The Barbecue Chicken Pizza (other size) — **798 orders**  
4. The Five Cheese Pizza — **731 orders**  
5. The Four Cheese Pizza — **639 orders**  
*(Source: Page 7)*

---

## 🍽️ 7. Category-Wise Quantity Sold  
| Category | Total Quantity Sold |
|----------|---------------------|
| Classic  | 6112 |
| Chicken  | 5490 |
| Veggie   | 3812 |
| Supreme  | 3634 |

*(Source: Page 8)*

---

## ⏰ 8. Distribution of Orders by Hour  
Peak ordering times occur around:  
**12 PM – 1 PM** and **5 PM – 7 PM**  
*(Source: Page 9)*

---

## 📅 9. Average Orders Per Day  
The average daily order count is:  
**59.63 orders/day**  
*(Source: Page 10)*

---

## 💵 10. Top 3 Revenue-Generating Pizzas  
Top pizzas based on revenue earned:  
1. **bbq_chkn_l — $17,990.25**  
2. **big_meat_s — $17,796**  
3. **five_cheese_l — $13,523.5**  
*(Source: Page 11)*

---

## 📊 11. Cumulative Revenue Over Time  
Revenue consistently increases across the timeline, showing strong and stable performance.  
*(Source: Page 12)*

---

# 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| **SQL** | Data analysis & queries |
| **MySQL / SQL Server** | Query execution |
| **Excel / PDF** | Visualization & reporting |

---

# 🧠 SQL Techniques Used

- Aggregate functions (`SUM`, `COUNT`, `AVG`)  
- CTEs (Common Table Expressions)  
- Joins (INNER JOIN)  
- Grouping & sorting (`GROUP BY`, `ORDER BY`)  
- Window calculations (for cumulative revenue)  
- Subqueries  

---

# 📑 Project Files

This repository includes:

- 📄 **SQL scripts** for all analysis steps  
- 📊 **PDF report** with visualized results  
- 🖼️ **Screenshots** of SQL outputs  
- 📘 **README.md** (this document)  

---

# 🎯 Conclusion

This project demonstrates how SQL can effectively transform raw transactional data into meaningful business intelligence. The insights gained support decisions related to:

- Menu optimization  
- Order forecasting  
- Inventory planning  
- Customer behavior analysis  
- Revenue growth strategies  

---



⭐ *If you found this project valuable, please consider giving the repository a star!*

