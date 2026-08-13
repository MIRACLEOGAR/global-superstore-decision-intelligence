\# Executive Sales Performance \& Decision Intelligence Dashboard



\### Transforming transactional sales data into executive-level performance intelligence and actionable business decisions.



\---



\## 📊 Project Overview



The \*\*Executive Sales Performance \& Decision Intelligence Dashboard\*\* is a six-page interactive Business Intelligence solution developed in Microsoft Power BI using the \*\*Global Superstore dataset covering 2011–2014\*\*.



The project combines performance monitoring, interactive analysis, DAX-driven classification, drill-through investigation, contextual insights, and executive recommendations within one analytical workflow.



> \*\*What happened → Why it happened → Where the opportunity or risk exists → What action should be taken\*\*



\---



\## 🎯 Business Objective



The objective was to transform transactional sales data into a centralized decision-support environment that helps management:



\- Monitor sales and profitability

\- Identify strong and underperforming areas

\- Evaluate products and sub-categories

\- Understand the impact of shipping costs

\- Compare customer segments

\- Identify growth opportunities and business risks

\- Translate analytical findings into actionable recommendations



\---



\## 💡 Analytical Workflow



Executive Summary  

↓  

Sub-Category Performance  

↓  

Product Performance  

↓  

Shipping \& Logistics  

↓  

Customer Segment Analysis  

↓  

Executive Insights \& Recommendations



\---



\## 👥 Intended Users



\- Executive Management

\- Sales Managers

\- Business Owners

\- Marketing Teams

\- Operations \& Logistics Managers



\---



\# 📊 Dashboard Architecture



\## 1. Executive Summary



!\[Executive Summary](assets/01-executive-summary.png)



Provides a consolidated view of business performance through dynamic KPIs, comparative trends, category analysis, regional performance, and Top/Bottom N analysis.



Key features include:



\- Dynamic Metric Switch

\- Growth target comparison

\- Dynamic report headlines

\- Interactive slicers

\- Top/Bottom N analysis



\---



\## 2. Sub-Category Performance



!\[Sub-Category Performance](assets/02-sub-category-performance.png)



Evaluates sub-categories using \*\*Total Sales\*\* and \*\*Profit Margin %\*\*.



Each sub-category is dynamically classified against the average Sales and Profit Margin of the sub-category population.



| Classification | Sales vs Average | Margin vs Average | Business Interpretation |

|---|---|---|---|

| \*\*High Performer\*\* | ≥ Average | ≥ Average | Strong sales performance and strong profitability |

| \*\*Opportunity\*\* | < Average | ≥ Average | Healthy profitability with room to increase sales |

| \*\*At Risk\*\* | ≥ Average | < Average | Strong sales volume but weaker profitability |

| \*\*Critical Risk\*\* | < Average | < Average | Below-average sales and profitability |



The classification responds dynamically to the selected \*\*Year, Category, Region, and Month\*\* filters. Therefore, a sub-category's classification can change as the analytical context changes.



\---



\## 3. Product Performance



!\[Product Performance](assets/03-product-performance.png)



Provides product-level investigation through \*\*drill-through navigation\*\* from Sub-Category Performance.



The analysis identifies:



\- Product sales and profit

\- Profit margin

\- Opportunity products

\- Loss-making products

\- Product contribution within the selected sub-category



This supports the question:



> \*\*Which products are driving the performance of the selected sub-category?\*\*



\---



\## 4. Shipping \& Logistics Analysis



!\[Shipping \& Logistics Analysis](assets/04-shipping-logistics.png)



Evaluates shipping modes, shipping costs, orders, and their effect on profitability.



The analysis identified that:



> \*\*3 of 4 shipping modes were loss-making, while Standard Class was the only profitable mode in the overall reporting context.\*\*



The dashboard distinguishes between:



\- \*\*Profit Margin\*\*

\- \*\*After Shipping Profit\*\*

\- \*\*After Shipping Margin\*\*



This highlights how shipping costs can significantly reduce the profitability retained by the business.



\---



\## 5. Customer Segment Analysis



!\[Customer Segment Analysis](assets/05-customer-segment.png)



Evaluates customer segments across sales, profit, customer value, order value, customer count, and margin.



Key findings:



\- \*\*Consumer\*\* → Leads sales

\- \*\*Corporate\*\* → Leads customer value

\- \*\*Home Office\*\* → Leads margin at \*\*11.99%\*\*



This demonstrates why customer performance should be evaluated across multiple dimensions rather than sales volume alone.



\---



\## 6. Executive Insights \& Recommendations



!\[Executive Insights \& Recommendations](assets/06-executive-insight.png)



The final page consolidates the major findings from the report into an overall executive interpretation.



Each of the first five dashboards also contains a dedicated \*\*Insight View\*\*, accessible through bookmarks, while this final page provides the overall business perspective.



The report therefore connects:



\*\*Performance → Investigation → Interpretation → Recommendation\*\*



\---



\# ⚙️ Key Technical Features



\### Dynamic Metric Switch



A DAX-driven metric switching mechanism allows users to change the analytical focus between measures such as:



\- Sales

\- Profit

\- Orders



\### Dynamic Performance Classification



Sub-categories are classified using dynamically calculated average Sales and Profit Margin benchmarks.



| Classification     | Sales vs Average | Margin vs Average | Business Interpretation                           |

| ------------------ | ---------------- | ----------------- | ------------------------------------------------- |

| \*\*High Performer\*\* | ≥ Average        | ≥ Average         | Strong sales and strong profitability             |

| \*\*Opportunity\*\*    | < Average        | ≥ Average         | Healthy profitability with room to increase sales |

| \*\*At Risk\*\*        | ≥ Average        | < Average         | Strong sales but weaker profitability             |

| \*\*Critical Risk\*\*  | < Average        | < Average         | Below-average sales and profitability             |



The classification changes with the current analytical context, including Year, Category, Region, and Month selections.



\### Other Features



\- Bookmark-driven Insight Views

\- Drill-through navigation

\- Dynamic report headlines

\- Field Parameters

\- Interactive Tooltips

\- Top/Bottom N analysis

\- DAX growth targets

\- Interactive dashboard navigation



\---



\# 🔍 Key Business Findings



\### Overall Performance



Across the overall reporting context:



\- \*\*Total Sales:\*\* $12.64M

\- \*\*Profit Margin:\*\* 11.61%

\- \*\*After Shipping Profit:\*\* $114.64K

\- \*\*After Shipping Margin:\*\* 0.91%

\- \*\*Month-over-Month Profit Growth:\*\* 3.3%



The results show positive business momentum at the reported-profit level, while the significantly lower After Shipping Margin highlights the financial impact of shipping costs.



\### Category Performance



\*\*Technology\*\* emerged as the strongest category and performed above the defined growth benchmark.



All three categories were identified as being on track.



\### Sub-Category Performance



The dynamic classification identified:



\- \*\*3 High Performers\*\*

\- \*\*6 Opportunities\*\*

\- \*\*6 At Risk\*\*

\- \*\*2 Critical Risk\*\*



This indicates that although several areas perform strongly, a substantial portion of the sub-category portfolio contains opportunities or risks requiring management attention.



\### Shipping Performance



\*\*3 of 4 shipping modes were loss-making\*\*, making shipping cost recovery an important area for management attention.



\### Customer Segment Performance



Different segments lead across different dimensions:



\*\*Consumer\*\* → Highest sales



\*\*Corporate\*\* → Highest customer value



\*\*Home Office\*\* → Highest margin at \*\*11.99%\*\*



\---



\# 💡 Why These Findings Matter



The analysis demonstrates the importance of evaluating business performance across multiple dimensions simultaneously.



For example:



> Consumer leads sales, while Home Office leads margin.



Therefore, a strategy focused exclusively on sales growth could overlook opportunities to improve profitability.



Similarly:



> Standard Class is the only profitable shipping mode.



Therefore, increasing sales without addressing shipping economics may not produce proportional improvements in profitability.



The dashboard helps move the analysis from:



\*\*"What is selling?"\*\*



to:



\*\*"What is actually creating profitable business performance?"\*\*



\---



\# 🚀 Executive Recommendations



\### 1. Sustain Technology Performance



Continue supporting Technology while identifying successful practices that can be applied to weaker areas.



\### 2. Address At Risk and Critical Risk Sub-Categories



Investigate pricing, discounting, product mix, demand, and cost structure to identify the drivers of weaker performance.



\### 3. Improve Shipping Cost Recovery



Review loss-making shipping modes and consider approaches such as shipping surcharges, minimum order values, or revised shipping pricing.



\### 4. Balance Consumer Volume with Corporate Value



Retain Consumer as the primary sales engine while developing Corporate opportunities to strengthen customer value and overall margin quality.



\### 5. Develop Opportunity Sub-Categories



Target sub-categories with healthy margins but below-average sales through focused sales, marketing, and product strategies.



\---



\# 📈 Business Value



The dashboard provides a centralized decision-support environment for:



\- Monitoring business performance

\- Identifying profitability drivers

\- Detecting business risks

\- Investigating product performance

\- Evaluating shipping profitability

\- Understanding customer segment quality

\- Identifying growth opportunities

\- Translating analysis into actionable decisions



The solution moves beyond conventional KPI reporting by connecting:



\*\*Performance Measurement → Investigation → Interpretation → Recommendation\*\*



\---



\# 🛠️ Tools \& Technologies



\*\*Microsoft Power BI • Power Query • DAX\*\*



\---



\# 📁 Repository Structure



global-superstore-decision-intelligence/  

│  

├── README.md  

├── Executive-Sales-Decision-Intelligence.pbix  

│  

├── assets/  

│   ├── 01-executive-summary.png  

│   ├── 02-sub-category-performance.png  

│   ├── 03-product-performance.png  

│   ├── 04-shipping-logistics.png  

│   ├── 05-customer-segment.png  

│   └── 06-executive-insight.png  

│  

├── data/  

├── documentation/  

└── features/



\---



\# 📚 Dataset



\*\*Global Superstore | 2011–2014\*\*



The dataset contains transactional information covering sales, products, customers, regions, shipping methods, and profitability.



\---



\# 👩‍💻 Author



\## Miracle Ogar



\*\*Data Analyst | Business Intelligence | Data Analytics\*\*



GitHub: \*\*@miracleogar\*\*



\### Project Focus



\*\*Business Intelligence • Data Analytics • Power BI • DAX • Decision Intelligence\*\*

