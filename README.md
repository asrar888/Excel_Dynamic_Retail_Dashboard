# **Dynamic Retail Dashboard in Excel**

This repository contains a **Dynamic Retail Dashboard** built using Excel and Power Query, which integrates and visualizes retail data from multiple sources. The dashboard allows users to interact with important retail KPIs, providing insights into sales performance, market segmentation, and regional analysis.

---

### **Objectives**
1. To build a dynamic and interactive retail dashboard using Excel.
2. To analyze key performance indicators (KPIs) such as sales, profit, quantity, and profitability.
3. To visualize top and bottom-performing products, categories, and regions.
4. To use Power Query for data extraction, cleaning, and transformation.
5. To answer critical business questions using retail data and enhance decision-making with visuals.

---

### **Sample Data Used**

1. **Orders Table**  
This table contains detailed transaction data for each order, including product details, sales, and shipping information.

| Order ID       | Order Date | Ship Date | Ship Mode    | Customer ID | Customer Name  | Segment   | City           | State       | Country     | Market | Region | Product ID      | Category   | Sub-Category | Product Name                                                               | Sales    | Quantity | Discount | Profit   | Shipping Cost | Order Priority |
|----------------|------------|-----------|--------------|-------------|----------------|-----------|----------------|-------------|-------------|--------|--------|-----------------|------------|--------------|---------------------------------------------------------------------------|----------|----------|----------|----------|---------------|----------------|
| CA-2012-124891 | 31-07-2020 | 31-07-2020 | Same Day     | RH-19495    | Rick Hansen    | Consumer  | New York City  | New York    | USA         | US     | East   | TEC-AC-10003033 | Technology | Accessories  | Plantronics CS510 Wireless Headset System                                  | 2309.65  | 7        | 0        | 762.18   | 933.57        | Critical       |
| IN-2013-77878  | 05-02-2021 | 07-02-2021 | Second Class | JR-16210    | Justin Ritter  | Corporate | Wollongong     | New South Wales | Australia  | APAC   | Oceania| FUR-CH-10003950 | Furniture  | Chairs       | Novimex Executive Leather Armchair, Black                                  | 3709.40  | 9        | 0.1      | -288.77  | 923.63        | Critical       |
| IN-2013-71249  | 17-10-2021 | 18-10-2021 | First Class  | CR-12730    | Craig Reiter   | Consumer  | Brisbane       | Queensland  | Australia   | APAC   | Oceania| TEC-PH-10004664 | Technology | Phones       | Nokia Smart Phone, with Caller ID                                          | 5175.17  | 9        | 0.1      | 919.97   | 915.49        | Medium         |

2. **People Table**  
This table includes the regional assignment for key personnel involved in the operations.

| Person           | Region  |
|------------------|---------|
| Anna Andreadi    | Central |
| Chuck Magee      | South   |
| Kelly Williams   | East    |
| Matt Collister   | West    |
| Deborah Brumfield| Africa  |

3. **Return Table**  
This table tracks the orders that have been returned, along with their respective markets.

| Returned | Order ID       | Market     |
|----------|----------------|------------|
| Yes      | MX-2013-168137  | LATAM      |
| Yes      | US-2011-165316  | LATAM      |
| Yes      | ES-2013-1525878 | EU         |
| Yes      | CA-2013-118311  | United States |
| Yes      | ES-2011-1276768 | EU         |

---

### **Key Business Questions Solved**
1. **Important KPIs that can be sliced and diced based on key filters**  
   - This dashboard provides filters to explore KPIs like **Sales**, **Profit**, **Quantity**, etc., by various dimensions such as segment, category, region, and market.

2. **Charts showing Segment, Category, and Market Analysis**  
   - Analyze sales and profit performance across different **customer segments** (Consumer, Corporate, Home Office), **product categories** (Technology, Furniture, Office Supplies), and **markets**.

3. **Top 5 and Bottom 5 charts for Sales, Profits, and Order Quantity**  
   - Discover the **top 5** and **bottom 5** performing products or regions in terms of **Sales**, **Profit**, and **Order Quantity**.

4. **World Map showing the top 10 countries by Sales**  
   - A geographic breakdown showcasing the top 10 countries contributing to sales with an interactive world map visualization.

5. **Top Sub-Category and their contribution to the overall Sales**  
   - Identify which **sub-categories** (e.g., Phones, Chairs, Accessories) contribute the most to overall sales performance.

6. **Charts showing the Market Share of Regions**  
   - Understand the regional market share distribution, giving insights into how different regions (e.g., North America, APAC, Europe) contribute to the overall sales.

---

### **Key Metrics Explained**

- **Total Sales** (🔍):  
  The total revenue generated from all orders.

- **Total Profit** (💰):  
  The total profit margin after deducting all costs from the sales.

- **Total Quantity** (📦):  
  The total number of units sold across all transactions.

- **Average Discount** (💹):  
  The average discount offered on the products sold.

- **Total Orders** (🛒):  
  The count of total orders processed within the dataset.

- **Profitability** (📈):  
  A derived metric that reflects overall business profitability, calculated as the sum of profit margins.

---

### **Steps Followed in the Project**

1. **Data Import and Cleaning**:
   - Imported data from three tables: `Orders`, `People`, and `Return` using the **Get Data** option.
   - Cleaned and transformed data using **Power Query Editor** to ensure consistency and accuracy.
   - Established relationships between the tables for improved analysis.

2. **KPI Creation**:
   - Created important KPIs (as explained above) to track performance metrics.
   - These KPIs can be sliced and filtered by key dimensions like **Segment**, **Market**, **Region**, and **Product Category**.

3. **Visualization Creation**:
   - Built interactive charts to answer key business questions:
     - Segment, Category, and Market Analysis charts.
     - Top and Bottom 5 Sales/Profit/Quantity performance.
     - Regional Market Share pie and bar charts.
     - A world map showing top-performing countries by sales.

4. **Consolidated KPI Table**:
   - Created a table to summarize all KPIs with corresponding symbols:
     | Name            | Metric                  | Symbol |
     |-----------------|-------------------------|--------|
     | Total sales      | Sum of Sales            | 🔍      |
     | Total profit     | Sum of Profit           | 💰      |
     | Total Quantity   | Sum of Quantity         | 📦      |
     | Average Discount | Average of Discount     | 💹      |
     | Total Orders     | Count of Order ID       | 🛒      |
     | Profitability    | Sum of Profitability    | 📈      |

---

### **Conclusion**
The **Dynamic Retail Dashboard** provides a comprehensive view of retail performance, enabling businesses to analyze key metrics and take informed decisions. Users can easily explore the data by filtering through segments, categories, and regions.

---

### **Significance**
This dashboard is highly valuable for retail businesses to:
- **Improve Decision Making**: Access real-time, interactive reports to make better business decisions.
- **Optimize Performance**: Analyze sales trends and market dynamics to boost profitability.
- **Track Regional Insights**: Identify strong and weak regions based on sales and profit data.
- **Enhance Data Accessibility**: The dynamic dashboard provides all relevant KPIs and visuals in one place.

---

### **How to Use the Dashboard**
1. Open the Excel file containing the dashboard.
2. Use filters and slicers to segment the data by categories like **Segment**, **Market**, **Region**, and **Sub-Categories**.
3. Explore the visualizations to:
   - View top and bottom performers.
   - Analyze market share.
   - Drill down into specific KPIs like Sales, Profit, Quantity, and Orders.
4. Load new data and the dashboard updates automatically.
   
###Screenshot
![image](https://github.com/user-attachments/assets/ca757738-4f2e-4f21-87af-3852b7b05462)







