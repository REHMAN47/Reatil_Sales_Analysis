# Excel Sales Dashboard 
## Introduction
A dynamic and interactive Excel Dashboard that visualizes key performance indicators (KPIs), trends, and insights for sales data. This project is ideal for understanding how to create data-driven dashboards using Excel formulas, PivotTables, slicers, and charts.

## Dashboard File
My final dashboard is in [sales_analysis_dashboard](/Sales_Dataset/retail_sales_analysis.xlsx)

## Project Overview
This Excel Dashboard was built to analyze and present sales data in a clear, intuitive format. It includes:

- 📈 Monthly & Quarterly Sales Trends

- 💰 Revenue by Product/Category

- 📌 KPIs like Total Sales, Average Order Value, Units Sold

- 📊 Clean visualizations using charts and PivotTables

## Excel Skills Used
The following Excel skills were utilized for analysis:

- PivotTables & PivotCharts

- Slicers & Timeline Filters

- Conditional Formatting

- GETPIVOTDATA, SUMIFS, TEXT, and other Excel formulas

## Retail Sales Dataset
- 🗂️ Dataset source : Kaggle

This dataset is a snapshot of a fictional retail landscape, capturing essential attributes that drive retail operations and customer interactions. It includes key details such as Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, and Total Amount. These attributes enable a multifaceted exploration of sales trends, demographic influences, and purchasing behaviors.

After modifing and adding some columns here is the final dataset : [final_dataset](/Sales_Dataset/finla_reatil_sales_dataset.csv)

## Dashboard Preview

![Alt image](/Assests/dashboard.png)

*This Excel Sales Dashboard provides a comprehensive visual summary of sales performance across various dimensions for the year 2023. Designed with interactivity and clarity in mind, it helps quickly identify trends, patterns, and key business metrics.*

### 🧾 Key Highlights:

#### ✅ Top KPIs Displayed

- Total Revenue: ₹4,56,000
- Average Order Amount: ₹135
- Total Sales (Units): 2,514

#### 📅 Sales Performance by Month

- A line chart showing monthly sales trends, helping identify peak and low-performing months.

#### 📊 Sales Performance by Quarter

- A bar chart breaking down units sold by product category (Beauty, Clothing, Electronics), grouped by quarter.

#### 🕒 Sales by Day of the Week

- A horizontal bar chart to track which days see higher sales activity.

#### 🧩 Sales by Gender (2023)

- A column chart representing sales distribution across genders and product categories.

#### 🎚️ Interactive Filters

- Gender
- Quarter
- Month (Date Trend)


# Dashboard Build
### 1. Sales Performance by Month 
This line chart illustrates monthly sales figures for the year 2023, showcasing how total sales values fluctuated across each month. Each point on the line represents the total sales for a specific month, with numerical labels highlighting the actual values for better clarity.

![Alt image](/Assests/sales_performence.png)

#### Insights : 
- Business performance peaked mid-year and recovered strongly in Q4.

- Consider investigating September’s underperformance and duplicating May/October strategies for sustained growth.

- Month-over-month tracking like this helps identify seasonal patterns and supports better forecasting and campaign planning.

Background Table : 

![Alt image](/Assests/month_trend_table.png)

### 2.  Sales Performance by Quarter

Each quarter is analyzed using column charts to show the number of units sold in each category. The visuals are enhanced with slicers, allowing for interactive filtering of quarters, enabling users to view and compare category-wise performance for each quarter individually.

![Alt image](/Assests/quarter.png)

#### Insights :

- The gap between the top (Clothing) and bottom (Electronics) performers highlights an opportunity to explore why Electronics underperformed in Q1 — possibly price sensitivity or lack of deals.

- The total sales in Q1 suggest a strong start to the year, with all three categories contributing significantly.

- Future quarters can be compared using the slicer to identify trends or shifts in customer preference across seasons.

### 3. Sales by Day of the Week
This bar chart displays day-wise sales performance across the days of the week for the month of February. The data highlights how sales vary from Sunday to Saturday, with each bar representing the total sales value (₹) for that specific day. The slicer on the right allows month-wise filtering, providing the ability to track and compare performance trends across different time periods.

![Alt Image](/Assests/sales_by_DOW.png)

#### Insights : 
- Friday spikes might be linked to end-of-week shopping behavior, payday effects, or targeted offers.

- The Monday bump could suggest online promotions or start-of-week incentives.

- Thursday underperformance offers a chance to introduce weekday-specific deals or push notifications to boost engagement.

Background Table :

![Alt Image](/Assests/dow_table2.png)

### 4. Sales by Gender (2023)
This clustered column chart presents the percentage of unit sales by gender across three product categories: Beauty, Clothing, and Electronics. It compares the buying patterns of Female (green) and Male (orange) customers, helping to understand how each gender contributes to sales across different product segments.

![Alt Image](/Assests/sales_gender.png)

#### Insights : 
- The gender gap is minimal across all categories, suggesting well-distributed marketing efforts or diverse product appeal.

- Clothing and Electronics show nearly equal interest from both genders — these categories are ideal for broad-based promotional campaigns.

- Beauty leans slightly toward female buyers, but male participation is still noteworthy and should not be overlooked.

Background Table : 

![alt image](/Assests/geneder_table.png)

### Acknowledgments

 Created by : <strong> Mahammed Rehman




