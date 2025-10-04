# Elevate-Labs-DAY-8 

📊 Task 8: Simple Sales Dashboard Design

 🎯 Objective
 
    Build an interactive dashboard to visualize sales performance by **Product**, **Region**, and **Month-Year** using Tableau. The goal is to create a clean, business-friendly dashboard     that highlights key trends and supports decision-making.

## 🛠 Tools Used

- **Tableau Public/Desktop** for dashboard creation
- 
- *(Optional)* **Python + Pandas** for data cleaning
-  
- **Dataset**: `Superstore_cleaned.xlsx`
- 
  - Key Columns: `Date`, `Region`, `Product`, `TotalPrice`, `Quantity`, `Order Status`


 📁 Workflow Steps

 1. Import Dataset
     - Load `Superstore_cleaned.xlsx` into Tableau
    
    - Verify key fields: `Date`, `Product`, `Region`, `TotalPrice`

2. Create “Month-Year” Field
  - Right-click `Date` → Create Calculated Field:
    ```text
    Month-Year = DATENAME('month', [Date]) + " " + STR(YEAR([Date]))Use this field for time-based analysis

3. Build Visuals
📈 Line Chart: Sales Over Time
Columns: Month-Year

Rows: SUM(TotalPrice)

Color: Region or Product

📊 Bar Chart: Sales by Region
Columns: Region

Rows: SUM(TotalPrice)

Sort descending, apply color to highlight top regions

🍩 Donut Chart: Sales by Product
Marks: Pie → Inner Radius for donut effect

Sections: Product

Angle: SUM(TotalPrice)

Label: % of Total Sales (calculated field)

4. Add Filters
   
Add slicers for Region and/or Product

Show as dropdowns or multi-select filters

5. Apply Color Logic
   
Use color to highlight top-performing categories

📦 Deliverables

✅ Dashboard Export

Export as a twb file

🔍 Insights

1. **Phones and Monitors** are the top-selling products, contributing over 40% of total revenue.
   
2. **South Region** consistently outperforms others, especially in Q2 and Q4.
  
3. **Sales peaked in November**, likely due to seasonal promotions.

4. **Cancelled orders** are highest for Tablets—potential issue with fulfillment or pricing..

📌 Outcome
  
    You’ll gain hands-on experience building a clean, interactive dashboard and learn how to summarize performance visually for business users that leads better insights ,patterns        extraction



    
