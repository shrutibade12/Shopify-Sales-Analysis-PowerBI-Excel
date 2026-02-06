
# Shopify Sales Analysis 

_Analyzing and providing  a consolidated, interactive view of Shopify business performance including sales, orders, customers, revenue trends, 
geographic distribution, and key KPIs for decision-making using Excel, and Power BI._

---

## 📌 Table of Contents
- <a href="#overview">Overview</a>
- <a href="#business-problem">Business Problem</a>
- <a href="#dataset">Dataset</a>
- <a href="#tools--technologies">Tools & Technologies</a>
- <a href="#project-structure">Project Structure</a>
- <a href="#data-cleaning--preparation">Data Cleaning & Preparation</a>
- <a href="#research-questions--key-findings">Research Questions & Key Findings</a>
- <a href="#dashboard">Dashboard</a>
- <a href="#final-recommendations">Final Recommendations</a>
- <a href="#author--contact">Author & Contact</a>

---
<h2><a class="anchor" id="overview"></a>Overview</h2>

An end-to-end Shopify Sales & Customer Funnel Analysis Dashboard built in Power BI, designed to analyze transaction performance, customer retention, revenue trends, and product-level insights using interactive KPIs and drill-through reporting.

---
<h2><a class="anchor" id="business-problem"></a>Business Problem</h2>

This project aims to:
- Monitor Net Sales, AOV, and Total Quantity
- Analyze Customer Purchase Behavior (Single vs Repeat Customers)
- Track Customer Lifetime Value (LTV) & Repeat Rate
- Identify Top Performing Products & Regions
- Enable drill-through navigation from summary to transaction-level insights

---
<h2><a class="anchor" id="dataset"></a>Dataset</h2>

- CSV file located in `/data/` folder (Shopify Sales)


---

<h2><a class="anchor" id="tools--technologies"></a>Tools & Technologies</h2>

- BI Tool: Power BI
- Data Transformation: Power Query
- Data Modeling: DAX (Measures, KPIs, Calculated Columns)
- Features Used:
  - Interactive Dashboards
  - KPIs & Cards
  - Measures & Calculations
  - Filters & Slicers
  - Drill-Through Navigation
  - Conditional Formatting
  - Regional Map Visualizations
- GitHub

---
<h2><a class="anchor" id="project-structure"></a>Project Structure</h2>

```
vendor-performance-analysis/
│
├── README.md
├── .gitignore
├── Shopify_Power_BI_Project_Documentation.pdf
│
├── dashboard/                  # Power BI dashboard file
│   └── shopify_dashboard.pbix
```

---
<h2><a class="anchor" id="data-cleaning--preparation"></a>Data Cleaning & Preparation</h2>

- Data was cleaned and transformed using Power Query Editor to ensure accuracy, consistency, and reliability before visualization.
  - Removed duplicates and handled missing/null values
  - Standardized column names and data formats (dates, currency, text)
   - Corrected inconsistent categorical values (product types, payment gateways, regions)
  - Created calculated columns for revenue metrics and customer segmentation
  - Performed data type conversion and validation checks
  - Structured data into a clean star-schema model for efficient reporting

---
<h2><a class="anchor" id="research-questions--key-findings"></a>Research Questions & Key Findings</h2>

1. **Revenue Health**: With $4.18M in net sales and a high AOV of $562, the business is performing well, driven by premium product sales. 
2. **Customer Base**: Nearly half of customers are repeat buyers, showing solid loyalty and retention. However, there’s room to increase purchase frequency beyond the current 1.68. 
3. **Product Mix**: Footwear dominates; expanding into complementary 
categories (jackets, accessories) could balance revenue streams. 
4. **Upsell Potential**: High AOV suggests customers are willing to spend — bundling or premium product lines could further lift sales. 


---
<h2><a class="anchor" id="dashboard"></a>Dashboard</h2>

- Power BI Dashboard shows:
  - 1️⃣ Summary Dashboard
    -Sales Performance Overview
    -Customer Purchase Behavior
    -Retention & Value Metrics
    -Net Sales Trend Over Time
    -Regional Sales Analysis (Province & City Level)
    -Sales by Product Type
    -Sales by Payment Gateway
  - 2️⃣ Detailed Transaction Page
    -Order-Level Data
    -Customer-Level Breakdown
    -Product & Gateway Filtering
    -Drill-through from summary visuals

![Shopify Analysis Dashboard](Images/dashboard1.png)
![Shopify Analysis Dashboard](Images/dashboard2.png)


---
<h2><a class="anchor" id="final-recommendations"></a>Final Recommendations</h2>

- **Increase Focus on High-Performing Products**: Running Shoes and Tennis Shoes drive the highest net sales — allocate more inventory and marketing budget to these categories.
- **Optimize Low-Contributing Product**: Evaluate underperforming SKUs    (e.g., low-sales accessories) for discounting, bundling, or discontinuation.
- **Improve Customer Retention**: With ~46% repeat rate, implement loyalty programs and targeted email campaigns to increase repeat purchases.
- **Leverage High-Performing Gateways**: Prioritize top-performing payment gateways to reduce checkout friction and improve conversion rate.
- **Regional Targeting Strategy**: Focus digital campaigns in top-performing states/cities while exploring growth opportunities in lower-performing regions.
- **Increase Average Order Value (AOV)**: Introduce cross-selling and upselling strategies (combo offers, free shipping thresholds).

---
<h2><a class="anchor" id="author--contact"></a>Author & Contact</h2>

**Shruti Bade**  
Data Analyst  
📧 Email: shrutibade12@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/shruit-bade)  
