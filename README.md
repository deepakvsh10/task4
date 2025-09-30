# **E-Commerce Order Fulfillment Analysis**  

## 📖 **Project Overview**  
This project analyzes the **order fulfillment process** of an e-commerce business, covering **sales trends, product performance, customer segmentation, shipping cost optimization, and payment method analysis**.  

Using **Advanced SQL Techniques** and **Python-based data visualization**, we extract insights to help businesses **improve logistics, boost sales, and enhance customer satisfaction**.  

---

## 🎯 **Objectives**  
✔ **Optimize order processing efficiency** – Track delays and enhance fulfillment times.  
✔ **Identify top-selling products** – Understand which products generate the highest revenue.  
✔ **Segment high-value customers** – Analyze customer spending behavior and engagement.  
✔ **Reduce shipping costs** – Evaluate cost variations based on order priority.  
✔ **Identify preferred payment methods** – Determine customer payment preferences for better financial strategies.  

---

## 📂 **Dataset Overview**  
- **Source**: E-Commerce transaction records with **51,290 rows** and **16 columns**  
- **Data Transformation**: The raw dataset was **normalized into four tables** for efficient querying:
  - `Orders` – Order details, including sales, profit, and shipping costs.  
  - `Customers` – Customer demographics such as gender, login type, and device.  
  - `Products` – List of all products and their categories.  
  - `Categories` – Broader classification of product types.  

---

## 🚀 **Advanced SQL Techniques Used**  
This project incorporates **Advanced SQL Techniques** to improve query performance, simplify analysis, and generate powerful insights:  

### **1️⃣ Window Functions**  
   - Used to **rank top-selling products** and **calculate cumulative sales over time**.  
   - Helps in **understanding product demand trends dynamically**.  

### **2️⃣ Common Table Expressions (CTEs)**  
   - Simplifies **customer segmentation analysis** by organizing complex queries.  
   - Enhances readability and maintains **modular query execution**.  

### **3️⃣ Ranking Functions (RANK() OVER)**  
   - Assigns rankings to products based on total sales.  
   - Useful for **identifying best-performing items efficiently**.  

### **4️⃣ Partitioning & Indexing for Performance Optimization**  
   - Used for **query optimization**, especially for large datasets.  
   - Ensures **faster retrieval of insights** from orders and customer data.  

---

## 📊 **Business Insights & Findings**  

### **📌 Sales & Revenue Analysis**  
- The business generated **$7.8M in total sales**, with a **$3.6M profit margin**.  
- **Sales peaked in May and November**, indicating strong **seasonal demand trends**.  

### **📌 Top-Selling Products**  
- The **highest-selling categories were Fashion and Footwear**, with **T-Shirts, Watches, and Running Shoes leading sales**.  
- **Bundling slower-moving items with high-performing products** could increase sales.  

### **📌 Customer Segmentation & Retention**  
- **High-spending customers are primarily male**, highlighting an opportunity for **targeted promotions**.  
- A **VIP loyalty program** can enhance customer retention and **increase repeat purchases**.  

### **📌 Order Fulfillment & Shipping Cost Optimization**  
- **High-priority orders have significantly higher shipping costs**.  
- Encouraging **bulk orders and standard delivery options** can help reduce logistics expenses.  

### **📌 Payment Method Preferences**  
- **Credit cards dominate transactions (74% of total revenue)**, while **e-wallet adoption remains low**.  
- **Promoting digital payment incentives** can increase checkout conversion rates.  

--- 

---

## 🔧 **Technologies Used**  
- **Database**: SQLite  
- **Query Language**: SQL  
- **Data Processing**: Pandas  
- **Visualization**: Matplotlib, Seaborn  
- **Development Environment**: Jupyter Notebook  

---
---

## 🛠 **How to Run the Project**  
1️⃣ **Clone the repository**  
```sh
git clone https://github.com/yourusername/E-Commerce-Analysis-Using-Advanced-SQL.git
cd ecommerce-sql-analysis
```
2️⃣ **Load the database (`Ecommerce_SQL_DATAProject.db`) into SQLite or DB Browser for SQLite.**  
3️⃣ **Execute SQL queries from `ecommerce_schema.sql` to explore insights.**  
4️⃣ **Run `E_Commerce_Analysis_using_Advanced_SQL.ipynb` in Jupyter Notebook to visualize trends using Python.**  
## 👤 **Author**  
🔹 **Abrar Qureshi**  

