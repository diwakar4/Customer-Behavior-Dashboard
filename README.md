# 📊 Customer Behavior Analytics Dashboard

An interactive **Power BI dashboard** designed to analyze customer purchasing behavior, revenue performance, subscription patterns, product categories, demographics, and seasonal trends.

The objective of this project was to transform raw customer transaction data into **actionable business insights** that could support better marketing, sales, and customer-retention decisions.

---

## 🎯 Business Objective

The analysis focuses on answering key business questions:

* Which product categories generate the most revenue?
* Which categories have the highest order volume?
* Do subscribers and non-subscribers behave differently?
* Does customer spending vary significantly by gender?
* Which age groups contribute the most revenue?
* Do discounts increase average purchase value?
* Is there meaningful seasonal variation in revenue?
* Which areas should the business investigate for growth opportunities?

---

## 🛠️ Tools & Technologies

| Tool                | Purpose                               |
| ------------------- | ------------------------------------- |
| **Power BI**        | Dashboard development & visualization |
| **Power Query**     | Data cleaning & transformation        |
| **DAX**             | KPI calculations and measures         |
| **Python / Pandas** | Data exploration and preprocessing    |
| **SQL**             | Data analysis and querying            |
| **Excel / CSV**     | Data source and initial inspection    |

---

## 📌 Dashboard KPIs

The dashboard tracks:

* 👥 **Total Customers:** 3.9K
* 💰 **Total Revenue:** $233K
* 🛒 **Average Purchase Amount:** $59.76
* ⭐ **Average Review Rating:** 3.75
* 📈 Revenue by Product Category
* 👤 Customer Distribution by Age Group
* 🔄 Subscription Status
* 📦 Sales by Category
* 🌦️ Seasonal Revenue Performance

---

## 🔍 Key Insights

### 1. Clothing dominates revenue

Clothing generated approximately **$104K in revenue**, representing around **39% of total revenue** and significantly outperforming the other categories.

### 2. Revenue leadership is primarily volume-driven

Average purchase amounts across categories remain relatively close at approximately **$57–$60**.

This suggests that Clothing's revenue advantage is primarily driven by **higher order volume rather than a substantially higher average transaction value**.

### 3. Non-subscribers generate more total revenue

Non-subscribers generated approximately **$170K**, compared with approximately **$63K from subscribers**.

This raises an important business question:

> How can the company convert high-value non-subscribers into repeat subscribers?

### 4. Gender has limited impact on average spending

Male customers significantly outnumber female customers, but the average purchase amount between the two groups is relatively similar.

This suggests that **customer volume differs more than spending behavior**.

### 5. Discounts don't necessarily create larger baskets

Discounted orders have a slightly lower average purchase amount than full-price orders.

This suggests discounts may be helping **drive purchase volume rather than increasing order value**.

### 6. Seasonal revenue is relatively stable

Fall is the strongest season, but the difference between seasons is relatively small.

Therefore, the business does not appear to be highly dependent on a single seasonal period.

### 7. Customer satisfaction is consistent

Average review ratings remain relatively close across product categories.

This suggests that customer satisfaction is **not currently a major differentiator between categories**.

---

## 📊 Dashboard Preview

### Overview

![Customer Behavior Dashboard](dashboard-overview.png)

### Insights

![Customer Behavior Insights](dashboard-insights.png)

---

## 🧠 Analytical Approach

The project followed an end-to-end analytics workflow:

```text
Raw Customer Data
        ↓
Data Cleaning
        ↓
Data Transformation
        ↓
Exploratory Analysis
        ↓
KPI Development
        ↓
Power BI Dashboard
        ↓
Business Insights
        ↓
Recommendations
```

---

## 📐 Key DAX Measures

Examples of the measures used in the dashboard:

```DAX
Total Revenue =
SUM(CustomerBehavior[Purchase Amount])
```

```DAX
Total Customers =
DISTINCTCOUNT(CustomerBehavior[Customer ID])
```

```DAX
Average Purchase Amount =
AVERAGE(CustomerBehavior[Purchase Amount])
```

```DAX
Average Review Rating =
AVERAGE(CustomerBehavior[Review Rating])
```

---

## 💡 Business Recommendations

Based on the analysis, potential areas for further investigation include:

1. **Investigate Clothing growth opportunities** because it is the strongest revenue category.

2. **Analyze non-subscriber behavior** to identify opportunities for subscription conversion.

3. **Evaluate discount effectiveness** by comparing conversion, order volume, and customer lifetime value rather than average order value alone.

4. **Investigate repeat-purchase behavior** to understand what drives customer retention.

5. **Segment customers by purchasing behavior** to identify high-value customer groups.

---

## 📁 Repository Structure

```text
Customer-Behavior-Analytics/
│
├── 📊 Dashboard/
│   └── Customer_Behavior_Dashboard.pbix
│
├── 📂 Dataset/
│   └── Cleaned_Customer_Behavior.csv
│
├── 🖼️ Screenshots/
│   ├── dashboard-overview.png
│   └── dashboard-insights.png
│
├── 📜 SQL/
│   └── customer_behavior_analysis.sql
│
├── 🐍 Python/
│   └── customer_behavior_analysis.ipynb
│
└── README.md
```

---

## 🚀 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* SQL
* Python
* Pandas
* Power BI
* DAX
* Data Visualization
* KPI Development
* Customer Analytics
* Business Analysis
* Data Storytelling
* Business Recommendation

---

## 🎯 Project Outcome

This project demonstrates how I approach an analytics problem from **raw data to business recommendation** rather than simply creating visualizations.

The main focus was:

> **Data → Analysis → Insight → Business Decision**

I'm continuing to build practical analytics projects while developing my skills for **Data Analyst and Business Analyst opportunities, particularly within startup environments.**

---

## 👨‍💻 Author

**Diwakar Singh**

Aspiring **Data Analyst | Business Analyst**

Skills: **SQL | Power BI | Excel | Python | Pandas | DAX | Data Analytics**

---

⭐ If you found this project useful, consider giving the repository a **star**!
# Customer-Behavior-Dashboard
