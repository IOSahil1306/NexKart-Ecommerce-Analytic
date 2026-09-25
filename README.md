#  NexKart – E-commerce Analytics  

##  Introduction  
NeoKart is a **fictional e-commerce company** that operates an online shopping platform.  
The aim of this project is to act as an **E-commerce Data Analyst**, helping key stakeholders (CEO, Product Manager, Marketing Team, etc.) understand business health and provide **data-driven insights** for growth.  

---

##  Project Goals  
-  **Marketing Optimization** → Analyze and optimize marketing channels, measure conversion performance, and improve ad spend strategy.  
-  **Product Performance** → Assess how new product launches affect sales and revenue.  
-  **Conversion Funnel Analysis** → Identify where customers drop off in the funnel by studying landing pages, product views, cart additions, and checkout steps.  
-  **Seasonality & Trends** → Detect seasonal patterns and forecast demand to improve inventory planning and efficiency.  
-  **Customer Behavior Analysis** → Understand purchase combinations to boost **cross-selling** and **upselling** opportunities.  

---

##  Database Schema  

### **Tables Overview**
- **website_sessions**  
  - Stores user session data and UTM parameters (`utm_source`, `utm_campaign`, `utm_content`) for traffic attribution.  
- **website_pageviews**  
  - Logs user interactions with each page on the website.  
- **products**  
  - Product catalog with details of items available for sale.  
- **orders**  
  - Records all purchases.  
  - `primary_product_id` → identifies the main purchased product.  
- **order_items**  
  - Lists items in each order.  
  - `is_primary_item` → `1` for main product, `0` for cross-sell/upsell items.  
- **order_item_refunds**  
  - Tracks refunded products linked to orders.  


---

##  Tools & Skills Used  
- **SQL** → Data extraction and analysis  
- **Python (Pandas, Matplotlib/Seaborn)** → Data cleaning and visualization  
- **Excel / Google Sheets** → Quick reporting and trend analysis  
- **Analytics Techniques** → Funnel analysis, cohort analysis, customer segmentation  
- **Business Insights** → Translating analytics into actionable strategies  

---

##  Example Analyses  
✔️ Identify top-performing marketing campaigns and their ROI  
✔️ Funnel drop-off analysis (sessions → product views → add to cart → purchase)  
✔️ Product cross-sell patterns (which products are often bought together)  
✔️ Seasonality in order volumes (monthly and quarterly trends)  
✔️ Impact of discounts and promotions on conversion rates  

---
