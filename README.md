***🏬 BrandX India Stores — End-to-End Data Engineering Project***
---------------------------------------------------------------------------------------

**Built with Microsoft Fabric · Medallion Architecture · PySpark · Power BI**

![BrandX_India_Stoores_Analytics_KPI_p](https://github.com/user-attachments/assets/60445fad-8d9b-498b-9b68-8a56d5a00361)

---------------------------------------------------------------
Welcome to the BrandX India Stores project — a complete, real-world data engineering workflow built on Microsoft Fabric and the Medallion Architecture. This repository demonstrates how structured retail data moves from ingestion to transformation to analytics, empowering data-driven decision-making at scale.

---------------------------------------------------------------------------------------

**📘 About the Dataset**

---------------------------------------------------------------------------------------
The dataset provides a comprehensive view of retail operations across multiple Indian cities from 2022 to 2024, including:

- Strong dependency on high-value SKUs driving majority of revenue

- Store performance skewed by premium vs mid-tier product mix

- Distinct payment-method preferences varying by city and store

- Seasonal demand clusters influencing monthly revenue patterns

- Category performance imbalance across locations

- Store-specific price sensitivity reflected in SKU composition

- Brand affinity patterns shaping product-level sales behavior

- Top-product concentration where few SKUs generate disproportionate revenue

- Cross-category purchase opportunities (electronics + apparel)

- City-specific dominance in certain categories or product lines

It also includes a Structure.json file containing a large amount of metadata used to drive ingestion logic. The Bronze layer reads this file and automatically processes data using metadata-driven pipelines, making the entire system scalable and adaptable.

This dataset is ideal for analytics, dashboards, forecasting, and experimenting with data engineering concepts.


-----------------------------------------------------------------------

**🧱 Medallion Architecture (Bronze → Silver → Gold)**
--------------------------------------
The Medallion Design ensures clarity, quality, and scalability:
<img width="1309" height="431" alt="medallion architecture pipeline" src="https://github.com/user-attachments/assets/28415b0c-6453-47a6-933c-490ca7ff3fb3" />


**🔶 Bronze Layer**

Raw structured data is ingested as-is, preserving full lineage and operational accuracy.

**🔷 Silver Layer**

Data is cleaned, standardized, enriched, and validated using PySpark notebooks.
This stage ensures consistency and reliability across the entire ecosystem.

**🟡 Gold Layer**

Business-ready and analytics-optimized tables are created.
In this project, the Gold layer produces:

- Product Rating Table

- Quantity & Revenue Table

- Payment Method Table

These curated tables feed directly into the semantic model and Power BI dashboards.

---------------------------------------------------------

**Semantic Model**
----------------------------------------------
The semantic model enhances analysis by defining clean relationships among:

- Date Table

- Product Rating Table

- Master Stores Data Table 

- Sales Table

- Quantity and Revenue Table

<img width="1051" height="432" alt="Semantic LT Model" src="https://github.com/user-attachments/assets/f46c594a-99bb-43e8-aa73-802d4ca64e5e" />

--------------------------------------------------
**It uses:**

- One-to-many relationships

- Single-direction cross-filtering

- Clean surrogate keys

This ensures fast, predictable insights across multiple dimensions.

-----------------------------------------------------------

**📊 Dashboard Highlights**
-----------------------------------------------------
The Power BI dashboard is built entirely on curated Gold datasets and offers an interactive analytics experience.

✅ Key KPIs

Total Revenue: ₹7.1bn

Units Sold: 227.41K

✅ Store Performance

City-wise and store-wise comparisons with drill-down features.

✅ Product Insights

Top-selling products with detailed revenue contribution.

✅ Payment Method Analysis

Breakdown across UPI, Card, EMI, Wallet, Cash, Credit.

✅ Monthly Revenue Trends

Seasonality, patterns, and business health indicators.

The dashboard offers a clean, intuitive experience tailored for decision-makers and analysts.

-------------------------------------------------------------------------------------------------

![BrandX_India_Stoores_Analytics_KPI_p](https://github.com/user-attachments/assets/2e6161f4-e1b7-46ae-9a40-b1bed189eb1d)

---------------------------------------------------------

**🛠 Tech Stack**
----------------

- Microsoft Fabric

- Delta Lake & OneLake

- PySpark

- Data Factory pipelines

- Semantic Model

- Power BI

-----------------------------------------------------------------------------------------

**📌 Key Learning Outcomes**
-------------------------------------

- How to build scalable pipelines in Microsoft Fabric

- How the Medallion Architecture simplifies lifecycle design

- How metadata-driven ingestion improves automation

- How PySpark is used for data cleansing and transformations

- How to design effective Power BI dashboards

- How to model data for reliable analytics
-----------------------------------------------------------

**🤝 How to Contribute**
----------------------------------------------------

Your ideas, improvements, and enhancements are welcome!

**Ways to contribute:**
-------------------------------------
- Improve transformations

- Suggest new KPIs

- Enhance visualizations

- Add ML forecasting

- Optimize pipeline performance

- Report issues or bugs

- Add documentation or tutorials

Whether you're a beginner exploring Fabric or an expert improving the pipeline, your contributions make this project better.

-------------------------------------------------------------------------------------
**📬 Contact**
-----------------------------------
🔗 LinkedIn: https://www.linkedin.com/in/laxdip-patel

🐙 GitHub: https://github.com/laxdippatel
