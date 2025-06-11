
# ☕ Coffee Sales Analysis Dashboard

Managing a coffee business isn’t just about brewing the perfect cup—it’s about making **data-driven decisions**. With thousands of transactions across different regions, it’s vital to understand trends, preferences, and performance indicators to grow profitably.

This project dives into sales data to answer critical business questions:

- 💎 Who are the **top-spending customers**?  
- 🌍 Which **countries** generate the most sales?  
- ☕ What **coffee types** are most popular and profitable?  
- 📦 Which **products** yield the highest margins?  
- 📊 How do **sales trends evolve** over time?

By applying **Excel-based data cleaning, functions, and dashboard techniques**, we converted complex data into actionable insights.



---

## 📁 Dataset Overview
The Power BI dashboard provides insights into:

- **Total Sales Over Time** (by coffee type)
- **Sales by Country**
- **Top 5 Customers**
- Filters for:
  - **Order Date**
  - **Roast Type** (Dark, Medium, Light)
  - **Coffee Size** (0.2 kg, 0.5 kg, etc.)
  - **Loyalty Card Holders**

![Coffee Sales Dashboard](https://raw.githubusercontent.com/your-username/your-repo-name/main/dashboard.png)

---

## 📁 Dataset Description

Each row in the dataset represents a transaction made by a customer. The key columns include:

| Column Name         | Description                                               |
|---------------------|-----------------------------------------------------------|
| Product ID          | Unique identifier for the product                         |
| Quantity            | Number of units purchased                                 |
| Customer Name       | Name of the customer                                      |
| Email               | Customer email address                                    |
| Country             | Country of purchase                                       |
| Coffee Type         | Short code for type (e.g., Rob, Ara, Exc, Lib)            |
| Roast Type          | Roast level (Dark, Medium, Light)                         |
| Size                | Package weight (e.g., 0.2 kg, 2.5 kg)                      |
| Unit Price          | Price per unit in USD                                     |
| Sales               | Total sales value (Quantity × Unit Price)                 |
| Coffee Type Name    | Full coffee type name (e.g., Robusta, Arabica, etc.)      |
| Roast Type Name     | Full roast type name                                      |
| Loyalty Card        | Indicates if the customer is a loyalty card holder (Yes/No) |

---



---

## 🛠 Data Cleaning & Preparation in Excel

To turn raw data into insights, the following preprocessing steps were done:

- 🔗 **Lookup Integration**: Used `XLOOKUP` and `INDEX MATCH` to bring together customer and product details with transactions.  
- 🚫 **Missing & Duplicate Handling**: Removed redundant entries and filled critical gaps.  
- 📊 **Metric Creation**: Computed new fields like revenue per customer and product-level profits.  
- 📅 **Date Formatting**: Organized time-based insights using `MONTH()`, `YEAR()` functions for trend analysis.

---

## 📊 Key Findings

### 👥 1. Top Customers  
- Top customers contribute a **significant share** of total revenue.  
- Members of the loyalty program purchase **larger pack sizes** more frequently.  
- **Repeat buyers** show higher lifetime value.

### 🌐 2. Country-Level Performance  
- The **U.S. leads in sales**, followed by select European countries.  
- Product preferences vary: e.g., **Arabica** is favored in the U.S., **Robusta** elsewhere.  
- Roast preference trends help in targeted marketing by geography.

### 💸 3. Coffee Type & Profitability  
- **Light roast Arabica** has both **high sales volume and profit margin**.  
- While medium roast is popular, its margins are slimmer.  
- **Larger pack sizes** drive profitability—ideal for bulk purchase targeting.

### 📅 4. Time-Based Sales Trends  
- Seasonal spikes seen in **Q4 (Oct–Dec)** due to festive demand.  
- Year-on-year sales showed an **18% increase**, confirming business growth.  
- Trends help plan **seasonal promotions and inventory cycles**.

---

## 📈 Final Output: Interactive Excel Dashboard

An easy-to-use **dashboard brings everything together**:

- ✅ **Customer Insights** – High-value buyers  
- ✅ **Country-Level Sales** – Geographical breakdown  
- ✅ **Product Profitability** – Which coffee types work best  
- ✅ **Monthly Trends** – Seasonal fluctuations  

**[📸 Insert your dashboard image or link here]**

---

## 📂 Files Included

- `Final_Dashboard.xlsx` – Interactive dashboard for exploration  
- `coffeeOrders_Data.xlsx` – Raw and cleaned dataset  

---

## 🧭 How to Navigate the Dashboard

1. Open `Final_Dashboard.xlsx` in Excel  
2. Use **slicers** and **filters** to explore specific regions, customers, or product types  
3. Hover over charts for dynamic insights  
4. Toggle between sheets for **sales trends, customer analysis, and product breakdowns**

---
## 🌟 Like the Project?

If you found this project helpful, consider giving it a ⭐ on GitHub and sharing your thoughts or suggestions!
