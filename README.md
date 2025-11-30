# Coffee-shop-Dashboard
# 🛒 Store & Product Performance Analysis Dashboard

This dashboard provides a comprehensive view of **store performance**, **product category insights**, **sales forecasting**, and **monthly revenue trends**. It is designed to help retail teams understand sales behavior across stores and product categories, enabling data-driven decisions.

---

## 📸 Dashboard Preview

![Store Dashboard](f5ec0afc-b357-448a-8e99-6edb2bbab03e.png)

---

## 🚀 Key Metrics

The top section highlights essential KPIs for business performance:

- **Total Sales Revenue:** 10.22K  
- **Total Quantity Sold:** 502  
- **Average Transaction Value:** 20.36  
- **Total Revenue per Product:** 40.09K  
- **% of Category Revenue:** 25.49%  

These metrics provide an instant overview of overall store performance.

---

## 🏬 Store Selection Panel

The dashboard includes a store navigation menu:

- **Astoria**  
- **Hell’s Kitchen**  
- **Lower Manhattan**

Selecting a store updates all charts and KPIs in real-time, providing store-level insights.

---

## 🍫 Product Category Selector

Product categories available for filtering:

- Bakery  
- Branded  
- Coffee  
- Coffee Beans  
- Drinking Chocolate  
- Flavours  
- Loose Tea  
- Packaged Chocolate  
- Tea  

Selecting a product category updates all visualizations to focus on category-specific performance.

---

## 📊 Sales Breakdown by Product Category

This horizontal bar chart shows:

- **Total Sales Revenue per product category**  
- **Total Quantity Sold per category**  

Example insights from sample data:

| Category            | Revenue |
|---------------------|---------|
| Coffee              | 90K     |
| Tea                 | 68K     |
| Bakery              | 27K     |
| Drinking Chocolate  | 26K     |
| Coffee Beans        | 10K     |
| Loose Tea           | 3K      |
| Flavours            | 2K      |
| Packaged Chocolate  | 1K      |

You can switch between **Top** and **Bottom** categories using dashboard buttons.

---

## 📈 Forecast Revenue by Date

The dotted line chart displays **daily revenue trends**, including:

- Seasonal revenue patterns  
- High and low revenue periods  
- Outlier peaks (e.g., 454 on one date)  

This helps identify promotions, demand surges, or slow days.

---

## 📆 Total Sales Revenue by Month

A month-wise revenue trend is visualized for 2023:

| Month | Revenue |
|--------|---------|
| Jan    | 1261    |
| Feb    | 1034    |
| Mar    | 1571    |
| Apr    | 1694    |
| May    | 2280    |
| Jun    | 2379    |

The area chart clearly shows revenue growth across months.

---

## 🛠️ Data Processing & Cleaning

To prepare the data for accurate reporting and fast performance, the following steps were applied:

### ✔️ Merged multiple tables  
- Sales data  
- Product category mapping  
- Store details  
- Dates & calendar table  

### ✔️ Removed unnecessary columns  
Examples removed:  
- Internal IDs  
- Extra timestamps  
- Unused metadata fields  

### ✔️ Handled missing values  
- Filled missing quantities with 0  
- Fixed incomplete date entries  
- Standardized product category names  

### ✔️ Optimized data types  
- Converted categories to `category` type  
- Converted dates using `datetime`  
- Reduced numeric precision for faster loading  

### ✔️ Created new calculated fields  
- Monthly sales  
- Total revenue per category  
- Forecasted revenue  
- Average transaction value  

---

## 🎯 Purpose of This Dashboard

This dashboard helps answer key business questions such as:

- Which store performs the best?  
- Which product categories generate the highest revenue?  
- What are the monthly sales patterns?  
- How does revenue fluctuate daily?  
- What is the expected revenue trend?  

Perfect for **retail analytics**, **store managers**, **product teams**, and **data portfolio projects**.

---

## ⭐ Features Summary

- Interactive store & category filters  
- Revenue & quantity comparison  
- Daily revenue forecasting  
- Monthly revenue trends  
- Clean UI with coffee-themed branding  

---

## 🙌 Acknowledgements

Thanks to open-source analytics tools and design resources used in building this dashboard.

