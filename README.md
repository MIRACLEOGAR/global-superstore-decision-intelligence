# 📊 Executive Sales Performance & Decision Intelligence Dashboard

### Transforming transactional sales data into executive-level performance intelligence and actionable business decisions.

![Executive Sales Summary](assets/01-executive-summary.png)

---

## 📌 Project Overview

The **Executive Sales Performance & Decision Intelligence Dashboard** is a six-page interactive Business Intelligence solution developed in **Microsoft Power BI** using the **Global Superstore dataset covering 2011–2014**.

The solution combines performance monitoring, profitability analysis, interactive investigation, DAX-driven classification, contextual insights, and executive recommendations.

> **What happened → Why it happened → Where the opportunity or risk exists → What action should be taken**

---

## 🎯 Business Problem

Sales data can show what is happening without clearly explaining **what is driving profitable performance**.

The project was designed to help decision-makers:

- Identify strong and underperforming products and sub-categories
- Compare sales performance with profitability
- Understand the effect of shipping costs on retained profit
- Evaluate customer segments beyond sales volume
- Identify growth opportunities and business risks
- Translate analysis into practical management actions

---

## 💡 Solution

The report follows a guided analytical workflow:

**Executive Summary → Sub-Category Performance → Product Investigation → Shipping & Logistics → Customer Segment Analysis → Executive Insights & Recommendations**

Users can move from high-level performance monitoring into detailed investigation and finally into an executive decision-support layer.

### Intended Users

**Executive Management • Sales Managers • Business Owners • Marketing Teams • Operations & Logistics Managers**

---

## 🛠️ Technology

**Microsoft Power BI • Power Query • DAX**

---

# 📊 Dashboard Architecture

## 1. Executive Summary

Provides a consolidated view of organizational performance using dynamic KPIs, comparative trends, category analysis, regional performance, and Top/Bottom N analysis.

**Key features:** Dynamic Metric Switch • Growth Targets • Dynamic Headlines • Interactive Slicers • Top/Bottom N Analysis

![Executive Summary](assets/01-executive-summary.png)

---

## 2. Sub-Category Performance

Evaluates sub-category performance using **Total Sales** and **Profit Margin %**.

Each sub-category is dynamically compared against the average Sales and Profit Margin within the active report context.

### Performance Classification

| Performance Category | Sales vs Avg. Sales | Margin vs Avg. Margin | Business Interpretation |
| --- | --- | --- | --- |
| **High Performer** | **≥ Average** | **≥ Average** | Strong sales combined with strong profitability |
| **Opportunity** | **< Average** | **≥ Average** | Healthy profitability with room to grow sales |
| **Weak Margin** | **≥ Average** | **< Average** | Strong sales volume but weaker profitability |
| **Low Performer** | **< Average** | **< Average** | Below-average sales and profitability |

The classification responds dynamically to the active analytical context and can change with **Year, Category, Region, or Month** filters.

![Sub-Category Performance](assets/02-sub-category-performance.png)

---

## 3. Product Performance

Provides detailed product-level investigation through **drill-through navigation** from the Sub-Category Performance page.

The analysis examines:

- Product Sales
- Product Profit
- Profit Margin
- Opportunity products
- Loss-making products
- Product contribution within the selected sub-category

> **Which products are driving the performance of the selected sub-category?**

![Product Performance](assets/03-product-performance.png)

---

## 4. Shipping & Logistics Analysis

Evaluates shipping modes, shipping costs, orders, and their effect on profitability.

> **3 of 4 shipping modes were loss-making, while Standard Class was the only profitable mode in the overall reporting context.**

The analysis distinguishes between:

- **Profit Margin**
- **After Shipping Profit**
- **After Shipping Margin**

This highlights how shipping costs can materially reduce retained profitability.

![Shipping & Logistics Analysis](assets/04-shipping-logistics.png)

---

## 5. Customer Segment Analysis

Evaluates customer segments using sales, profit, customer value, order value, customer count, margin, and regional performance.

### Key findings

- **Consumer** → Leads sales
- **Corporate** → Leads customer value
- **Home Office** → Leads margin at **11.99%**

The analysis demonstrates why customer performance should be evaluated across multiple dimensions rather than sales volume alone.

![Customer Segment Analysis](assets/05-customer-segment.png)

---

## 6. Executive Insights & Recommendations

The final page consolidates the major findings into an executive interpretation and recommendation layer.

Each of the first five dashboards also contains a dedicated **Insight View** accessible through bookmarks, while this sixth page provides the overall business perspective.

The report connects:

**Performance → Investigation → Interpretation → Recommendation**

![Executive Insights & Recommendations](assets/06-executive-insight.png)

---

# ⚙️ Interactive & Technical Features

### Dynamic Metric Switch
DAX-driven metric switching allows supported visuals to change analytical focus between measures such as **Sales, Profit, and Orders**.

### Dynamic Report Headlines
Headlines respond to the selected report context and filters, providing business context beyond static chart titles.

### Dynamic Sub-Category Classification
DAX compares Sales and Profit Margin against active-context averages to classify sub-categories as **High Performer, Opportunity, Weak Margin, or Low Performer**.

### Bookmark-Driven Insight Views
Each of the first five dashboards includes an Insight View that provides contextual interpretation without overcrowding the main analytical canvas.

### Drill-Through Navigation
Users can move from **Sub-Category → Product** while maintaining the selected analytical context.

### Field Parameters
Field parameters provide additional flexibility by allowing supported visuals to dynamically change analytical dimensions or metrics.

### Interactive Tooltips
Context-sensitive tooltips provide additional information without requiring users to leave the current analytical view.

### Top/Bottom N Analysis
Interactive Top/Bottom N analysis identifies leading and underperforming products, customers, regions, and sub-categories.

---

# 🔍 Key Business Findings

### Overall Performance

- **Total Sales:** $12.64M
- **Profit Margin:** 11.61%
- **After Shipping Profit:** $114.64K
- **After Shipping Margin:** 0.91%
- **Month-over-Month Profit Growth:** 3.3%

The results show positive reported-profit performance, while the much lower **After Shipping Margin** highlights the significant effect of shipping costs on retained profitability.

### Category Performance

**Technology** emerged as the strongest category and performed above the defined growth benchmark. All three categories were identified as being on track.

### Sub-Category Performance

The dynamic classification identified:

- **3 High Performers**
- **6 Opportunities**
- **6 Weak Margin**
- **2 Low Performer**

### Shipping Performance

**3 of 4 shipping modes were loss-making**, making shipping cost recovery a major area for management attention.

### Customer Segment Performance

**Consumer** leads sales, **Corporate** leads customer value, and **Home Office** leads margin at **11.99%**.

---

# 💡 Why These Findings Matter

The analysis demonstrates why business performance should not be evaluated through a single metric.

> **Consumer leads sales, while Home Office leads margin.**

A strategy focused only on sales volume could therefore overlook opportunities to improve profitability.

Similarly:

> **Standard Class is the only profitable shipping mode.**

Increasing sales without addressing shipping economics may not produce a proportional improvement in retained profitability.

The dashboard therefore moves the analysis from:

**"What is selling?"**

to:

**"What is actually creating profitable business performance?"**

---

# 🚀 Executive Recommendations

### 1. Sustain Technology Performance
Continue supporting Technology while identifying successful practices that can be applied to weaker areas.

### 2. Address Weak Margin and Low Performer Sub-Categories
Investigate pricing, discounting, product mix, demand, and cost structure to identify drivers of weaker performance.

### 3. Improve Shipping Cost Recovery
Review loss-making shipping modes and evaluate approaches such as shipping surcharges, minimum order values, or revised shipping pricing.

### 4. Balance Consumer Volume with Corporate Value
Maintain Consumer as the primary sales engine while developing Corporate opportunities to strengthen customer value and margin quality.

### 5. Develop Opportunity Sub-Categories
Target sub-categories with healthy margins but below-average sales through focused sales, marketing, and product strategies.

---

# 📈 Business Value

The solution provides management with a centralized decision-support environment for:

- Monitoring business performance
- Identifying profitability drivers
- Detecting business risks
- Investigating product performance
- Evaluating shipping profitability
- Understanding customer segment quality
- Identifying growth opportunities
- Translating analysis into actionable decisions

The dashboard moves beyond conventional KPI reporting by connecting:

**Performance Measurement → Investigation → Interpretation → Recommendation**

---

# 📚 Dataset

**Global Superstore | 2011–2014**

The dataset contains transactional information covering **sales, products, customers, regions, shipping methods, and profitability**.

---

# 📁 Repository Structure

<pre>
global-superstore-decision-intelligence/
│
├── README.md
├── Executive-Sales-Decision-Intelligence.pbix
│
└── assets/
    ├── 01-executive-summary.png
    ├── 02-sub-category-performance.png
    ├── 03-product-performance.png
    ├── 04-shipping-logistics.png
    ├── 05-customer-segment.png
    └── 06-executive-insight.png
</pre>

---

# 👩‍💻 Author

## Miracle Ogar

**Data Analyst | Business Intelligence | Data Analytics**

GitHub: **[@miracleogar](https://github.com/miracleogar)**

## 🎯 Project Focus

**Business Intelligence • Data Analytics • Power BI • DAX • Decision Intelligence**