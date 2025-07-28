# sql-ecommerce-analytics-case-study

# 📊 Target SQL Analysis – Brazil E-Commerce Business Case

This project presents an end-to-end SQL-based analytical case study using a simulated Brazilian e-commerce dataset modeled after a Target-like business. It explores order trends, customer behavior, freight costs, and delivery efficiency, with strategic business recommendations drawn from each analysis.

---

## 📌 Objectives

- Analyze customer distribution across Brazilian states and cities
- Identify seasonal and hourly order trends
- Assess delivery performance vs. estimated timelines
- Evaluate freight and order pricing by geography
- Study payment method preferences and installment usage
- Deliver actionable business insights and recommendations

---

## 🛠️ Tools & Technologies

- SQL (Google BigQuery syntax)
- Dataset from Target's e-commerce sales in Brazil
- Visualization tools (optional): Google Sheets / Excel / Tableau
- GitHub for version control and showcasing project


---

## 🔍 Key Analyses & Insights

### 🧑‍🤝‍🧑 1. Customer Distribution
- ~99,441 total customers; 96,096 are unique.
- Customers are from **4,119 cities** across **27 Brazilian states**.
- **São Paulo (SP)** has the largest customer base; **Roraima (RR)** the lowest.
- SP, RJ, and MG are top GDP states with 10,000+ customers.
- States like RR, AP, and AC have low customer counts due to geographic/logistic isolation.

### 📦 2. Order Volume Trends
- Orders increased **140× from 2016 to 2018**.
- Most orders were placed in **2017 and 2018**.
- Monthly order volume peaks in **August**; lowest in **September**.
- Strong seasonality observed from **May to August** due to Brazil’s festive season.

### 🕐 3. Time-of-Day Ordering Behavior
- Most orders are placed in the **afternoon (1PM–6PM)**.
- **Dawn (12AM–6AM)** has the least activity.
- Afternoon peaks suggest it’s the best time for promotional pushes.
- Early morning (Dawn) is optimal for maintenance activities.

### 🚚 4. Delivery Timelines
- **Average delivery time** is ~**7 days**.
- Only **13 orders** were delivered within 24 hours.
- Some orders took over **200 days** to be delivered.
- ~7,300 orders were delivered **later than the estimated date**.

### 📉 5. Freight Costs
- **São Paulo (SP)** has the **lowest average freight** cost.
- **Roraima (RR)** has the **highest average freight** — due to isolation.
- Infrastructure and logistics strongly affect shipping cost across states.

### 💳 6. Payment Preferences
- **74% of orders** were paid via **credit card**.
- UPI is the second most-used method.
- Most popular **installment plan** is a **single payment**, followed by 2–3 months.
- Only **3 orders** were marked with undefined payment types.

### 💰 7. Order Value Analysis
- Highest **total order value** in São Paulo (SP).
- Highest **average order value** in Paraíba (PB).
- Lower average order value in SP due to high order volume.
- Average order value across Brazil: **~$145.16**.

---

## 🧠 Recommendations Summary

- Focus marketing efforts around festive months (May–Aug).
- Provide **same-day delivery** in high-density regions (SP, RJ).
- Implement **reward points** with expiration to maintain off-season sales.
- Offer **credit-based EMI plans** and better UPI support for lower-GDP states.
- Consider **bulk order minimums** or hubs in remote areas to lower freight cost.

---



