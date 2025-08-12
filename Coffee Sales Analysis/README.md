# **Coffee Sales Analysis and Dashboard**

Dataset soruce: https://github.com/mochen862/excel-project-coffee-sales

This project has three (3) Excel Worksheets:

**Orders sheet:** Here are the Order ID, Order Date, Customer ID, Product ID, and Quantity.

**Product sheet:** Includes information about Product ID, Coffee Type, Roast Type, Size, Unit Price, Price per 100g, and Profit.

**Customers Sheet:** This is where the data about Customer ID, Customer Name, Email, Phone Number, Address Line 1, City, Country, Postcode, and Loyalty Card.

# **Key Steps:**
1. Convert the Orders, Customers, and Products Sheets into Tables to be able to create new query.
2. Remove rows if there are duplicates data. Pre-process the data by changing its proper data types.
3. New table named Merge Data by merging the 3 tables with the join key Customer ID and Product ID column from order table to Customers and Products table.
4. Add Sale column in Merge Data table by multiplying the Quantity column and the Unit Price column
5. Add Roast Type Name and Coffee Type Name columns using the conditional column (if-else).

# **Key Insights/Findings**
1. Excelsa achieved the most sales with $12,305.90, while Robusta had the lowest sales with $9,003.01.
2. The top 5 customers are Allis Wilmore, Brenn Dundredge, Terri Farra, Nealson Cuttler, and Don Flintiff.
3. The country United States achieved the highest sales with $35,635.71, next is Ireland with $6,696.28 and last is United Kingdom with $2,798.21.
4. The Light Roast Type achieved the highest sales of $17,364.45, 39% of its total sales followed by Medium type with $14,599.52, 32% of its total sales and last is Dark type with $13,176.23, 29% of its total sales.
5. January 2022 recorded the highest monthly sales at $843.67, followed closely by September 2021 with $840.86.
