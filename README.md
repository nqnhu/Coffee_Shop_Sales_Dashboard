# **Coffee Shop Sales Analysis with MySQL and Power BI**

## **Overview**
- This project actively tracks a store's monthly sales data and analyzes the change in revenue from the prior month, expressed as a percentage increase or decrease. 
- Microsoft Power BI has been used to create an interactive dashboard while pulling data from SQL Server.

## **Data Source**
#### Data Overview:
- [Coffee Shop Sales](https://docs.google.com/spreadsheets/d/19KgEh7QVbczZhUhIc2ulb9Y1LWNc2NGE/edit?usp=drive_link) - This is a CSV file with free sources online.
- Schema:
  - **transaction_id**: the id code of the invoice
  - **transaction_date**: date the invoice was created
  - **transaction_time**: time the invoice was created
  - **transaction_qty**: number of products sold
  - **store_id**: store id code
  - **store_location**: location of the store
  - **product_id**: product id code
  - **unit_price**: price of the product
  - **product_category**: the store's product categories
  - **product_type**: product classification
  - **product_detail**: detailed information of the product (origin,...)

## **Analysis**
![](/Dashboard%20Screenshot%20&%20Feature/dashboard.jpg)

### **Filter Panel**
![](/Dashboard%20Screenshot%20&%20Feature/filter%20panel.jpg)

Select the month to view the data

### **Overall Performance**
![](/Dashboard%20Screenshot%20&%20Feature/overall%20performance.jpg)
• Total Monthly Revenue: This metric shows the total money earned each month.

• Total Orders: This metric reflects the number of invoices in each month.

• Total Quantity Sold: This metric represents the total number of monthly sold products.

• Use **DAX** to write a function that determines the monthly increase or decrease in sales, and calculates the difference in sales between the selected month and the previous month.

• We'll create line charts to see the changes on each day of the month.

### **Calendar Heat Map**
![](/Dashboard%20Screenshot%20&%20Feature/calendar%20heat%20map.jpg)

• Each day on the calendar will be a different color to represent sales, with lighter colors representing higher sales.

• Use tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific day.

**Example:**

![](/Dashboard%20Screenshot%20&%20Feature/tooltip1.jpg)

After hovering on 31 May 2023, the detailed metrics were displayed.

### **Sales Analysis by Weekday / Weekend**
![](/Dashboard%20Screenshot%20&%20Feature/weekend%20weekday%20sale.jpg)

This section shows the total sales, total sales percentage for weekdays and weekends; and whether the difference between weekdays and weekends is significant.

### **Sales Analysis by Store Location**
![](/Dashboard%20Screenshot%20&%20Feature/store%20location%20sale.jpg)

• Visualize sales data by different store locations.

• Includes month-to-month difference (MoM) metrics based on the selected month. Highlight MoM sales increases or decreases for each store location to identify trends.

### **Sales Trend Over the Period**
![](/Dashboard%20Screenshot%20&%20Feature/sale%20trend.jpg)

• Displays sales for each day of the selected month using a column chart.

• Draw a dotted line representing average daily sales -> easily see how each day's sales exceed or fall below the average sales to identify special sales days.

### **Sales Analysis by Product Category**
![](/Dashboard%20Screenshot%20&%20Feature/product%20category%20sale.jpg)

• Analyze sales performance of different product categories.

• Statistics on which product categories contribute the most to total revenue.

### **Top 10 Products by Sales**
![](/Dashboard%20Screenshot%20&%20Feature/top%2010%20sales.jpg)

• Identify and display the top 10 best-selling products based on sales volume.

• Allows users to quickly visualize the best performing products in terms of sales.

### **Sales Analysis by Days and Hours**
![](/Dashboard%20Screenshot%20&%20Feature/day%20and%20hour%20sale.jpg)

• Use heat maps to visualize sales patterns by day and time, with darker colors representing lower sales.

• Use tooltips to display detailed metrics (Sales, Orders, Quantity) when hovering over a specific hour of the day.

**Example:**

![](/Dashboard%20Screenshot%20&%20Feature/tooltip2.jpg)

This is detailed metrics on Monday at 17 o'clock.
