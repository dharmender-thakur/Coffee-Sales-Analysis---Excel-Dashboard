
# ☕ Coffee Business Data Analysis 

Managing a coffee business isn’t just about brewing the perfect cup—it’s about making **data-driven decisions**. With thousands of transactions across different regions, it’s vital to understand trends, preferences, and performance indicators to grow profitably.

This project dives into sales data to answer critical business questions:

- 💎 Who are the **top-spending customers**?  
- 🌍 Which **countries** generate the most sales?  
- ☕ What **coffee types** are most popular and profitable?  
- 📦 Which **products** yield the highest margins?  
- 📊 How do **sales trends evolve** over time?

By applying **Excel-based data cleaning, functions, and dashboard techniques**, we converted complex data into actionable insights.

![Coffee Sales Dashboard](https://github.com/dharmender-thakur/Coffee-Sales-Analysis---Excel-Dashboard/blob/2f53d94475e9ccaae1733697aafa7470b78bdbec/CoffeeSalesDashboard.png)

---

## 📁 Dataset Overview
The dataset is structured into **three primary tables**, each playing a unique role in the analysis:

### 📦 1. Orders Table  
Captures transactional-level data:
### 1️⃣ Orders Data 📦
This table tracks every coffee sale made, capturing essential transaction details:
- **Order ID** – Unique identifier for each purchase.
- **Order Date** – The date when the order was placed.
- **Customer ID** – Links to the customer who placed the order.
- **Product ID** – Identifies the type of coffee sold.
- **Quantity** – The number of coffee units bought.
- **Sales Amount** – Total revenue from the sale.
- **Country** – The country where the order was placed.
- **Coffee Type & Roast Type** – Specific details about the coffee purchased.
- **Loyalty Program** – Indicates if the customer is part of the loyalty scheme.

 ![Dataset](https://github.com/dharmender-thakur/Coffee-Sales-Analysis---Excel-Dashboard/blob/2f53d94475e9ccaae1733697aafa7470b78bdbec/CoffeeSalesDataset.png)

### 2️⃣ Customers Data 👥
This table gives us insight into who is buying the coffee:
- **Customer Name** – Identifies the buyer.
- **Email & Phone Number** – Contact details.
- **Address & Country** – Location insights.
- **Loyalty Program Membership** – Helps track repeat customers.

### ☕ ### 3️⃣ Products Data ☕
This table focuses on coffee varieties and their pricing:
- **Product ID** – Unique identifier for each coffee type.
- **Coffee Type** – Arabica, Robusta, Excelsa, Liberica.
- **Roast Type** – Light, Medium, or Dark roast.
- **Size** – The weight of the coffee pack.
- **Unit Price** – The selling price per unit.
- **Profit Margin** – The amount of profit per sale.
---

## 🛠 Data Cleaning & Preparation in Excel

To turn raw data into insights, the following preprocessing steps were done:
-**🔹 Cleaning the Dataset:** Identified and removed duplicate entries while addressing missing values to maintain data integrity.
-**🔹 Data Integration:** Used XLOOKUP and INDEX-MATCH functions to bring actual customer names and coffee product details into the orders table from customer and product tables.
-**🔹 New Metrics:** Created calculated fields such as total sales per transaction, customer-level revenue, and profit margins to support deeper business insights.

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

![Coffee Sales Dashboard](https://github.com/dharmender-thakur/Coffee-Sales-Analysis---Excel-Dashboard/blob/2f53d94475e9ccaae1733697aafa7470b78bdbec/CoffeeSalesDashboard.png)

---

## 📂 Files Included

- `Coffee Sales Dashboard.xlsx` – Interactive dashboard for exploration  
- `Coffee Sales Dataset.xlsx` – Raw and cleaned dataset  

---

## 🧭 How to Navigate the Dashboard

1. Open `Coffee Sales Dashboard.xlsx` in Excel  
2. Use **slicers** and **filters** to explore specific regions, customers, or product types  
3. Hover over charts for dynamic insights  
4. Toggle between sheets for **sales trends, customer analysis, and product breakdowns**

---
## 🌟 Like the Project?

If you found this project helpful, consider giving it a ⭐ on GitHub and sharing your thoughts or suggestions!
