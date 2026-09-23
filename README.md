# Excel Sales Analysis

## Project Overview

This project focuses on analyzing sales data using Microsoft Excel.

The goal of the analysis is to evaluate overall sales and profitability, identify the best-performing products and categories, analyze sales trends over time, and generate business insights based on the available data.

The analysis was performed using Excel formulas, data aggregation, sorting, filtering, and data visualization.

## Business Questions

The analysis aims to answer the following questions:

- Which products generate the highest sales?
- Which categories generate the highest sales and profit?
- How do sales change over time?
- Which categories have the highest profit margins?
- What are the main sales trends?
- Which areas may require further business attention?

## Dataset

The dataset contains 9,995 rows and 21 columns. Each row represents a sales transaction.

The dataset includes information about:

- Order and shipping dates
- Shipping mode
- Customer information
- Customer segment
- Geographic information
- Product information
- Product categories and sub-categories
- Sales
- Quantity
- Discount
- Profit

### Data Quality Check

The dataset was checked before performing the analysis:

| Check | Result |
|---|---:|
| Number of rows | 9,995 |
| Number of columns | 21 |
| Missing values | 0 |
| Duplicate rows | 0 |

The dataset did not contain missing values or duplicate rows.

## Data Cleaning

Before starting the analysis, the dataset was checked and prepared for further calculations.

The following steps were performed:

- Checked the dataset structure and data types
- Converted `Order Date` and `Ship Date` from text to date format
- Converted `Sales`, `Quantity`, `Discount`, and `Profit` from text to numeric format
- Checked for missing values
- Checked for duplicate rows
- Prepared the cleaned data for further calculations and analysis

### Data Quality Check

| Check | Result |
|---|---:|
| Number of rows | 9,995 |
| Number of columns | 21 |
| Missing values | 0 |
| Duplicate rows | 0 |## Data Cleaning

The following steps were performed before the analysis:

- Checked the structure of the dataset
- Checked the number of rows and columns
- Checked for missing values
- Checked for duplicate rows
- Prepared the data for aggregation and analysis
- Created calculated fields for sales and profit analysis
- Organized the data into analytical tables

## Analysis

### Overall Sales Performance

The dataset contains **5,011 orders**.

The average order value is approximately **458.43**.

Total sales are approximately **2.30 million**, while total profit is approximately **286.40 thousand**.

The overall profit margin is approximately **12%**.

### Sales and Profit by Category

The analysis was performed for three main categories:

| Category | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| Furniture | 741,999.80 | 18,451.27 | 2% |
| Office Supplies | 719,047.03 | 122,490.80 | 17% |
| Technology | 836,154.03 | 145,454.95 | 17% |

Technology generated the highest sales and the highest total profit.

Furniture generated a similar level of sales to the other categories, but its profit margin was considerably lower.

Office Supplies generated lower sales than Technology and Furniture, but its profit margin was significantly higher than Furniture.

### Sales by Year

Sales were analyzed for the period from 2014 to 2017.

| Year | Sales |
|---|---:|
| 2014 | 484,247.50 |
| 2015 | 470,532.51 |
| 2016 | 609,205.60 |
| 2017 | 733,215.26 |

Sales decreased slightly from 2014 to 2015.

From 2015 onwards, sales increased substantially, with the highest annual sales recorded in 2017.

The strongest increase occurred between 2015 and 2016, followed by another significant increase in 2017.

### Top 10 Products by Sales

The Top 10 products were identified using Excel sorting and dynamic formulas.

| Rank | Product | Sales |
|---:|---|---:|
| 1 | Canon imageCLASS 2200 Advanced Copier | 61,599.82 |
| 2 | Fellowes PB500 Electric Punch Plastic Comb Binding Machine with Manual Bind | 27,453.38 |
| 3 | Cisco TelePresence System EX90 Videoconferencing Unit | 22,638.48 |
| 4 | HON 5400 Series Task Chairs for Big and Tall | 21,870.58 |
| 5 | GBC DocuBind TL300 Electric Binding System | 19,823.48 |
| 6 | GBC Ibimaster 500 Manual ProClick Binding System | 19,024.50 |
| 7 | Hewlett Packard LaserJet 3310 Copier | 18,839.69 |
| 8 | HP Designjet T520 Inkjet Large Format Printer - 24" Color | 18,374.90 |
| 9 | GBC DocuBind P400 Electric Binding System | 17,965.07 |
| 10 | High Speed Automatic Electric Letter Opener | 17,030.31 |

The highest-sales product was the **Canon imageCLASS 2200 Advanced Copier**, with sales of approximately **61.6 thousand**.

## Excel Techniques Used

The project uses several Excel techniques for data analysis:

- `SUMIF`
- `SORT`
- `INDEX`
- `SEQUENCE`
- Sorting and filtering
- Data aggregation
- Calculated fields
- Top 10 analysis
- Charts and data visualization

For example, the Top 10 products were generated by aggregating sales by product, sorting the results in descending order, and extracting the first 10 products.

## Data Visualization

Several charts were created to present the results visually:

- Sales by Category
- Profit by Category
- Sales by Year
- Average Profit analysis

These visualizations make it easier to compare category performance and identify changes in sales over time.

## Key Findings

Looking at the results, I can see that the company's sales increased during the analyzed period. There was a small decrease in 2015, but after that sales started to grow and reached the highest level in 2017. Compared with 2014, the sales in 2017 were noticeably higher.

When looking at the categories, Technology has the highest sales and profit. Office Supplies also has a good result, especially when looking at the profit margin. Furniture has quite high sales as well, but the profit is much lower and the profit margin is only around 2%.

This shows that having high sales does not always mean having high profit. It would be interesting to look deeper into the Furniture category and understand why the company earns much less from it.

The Top 10 analysis also shows that some products generate much higher sales than others. The highest-selling product is the Canon imageCLASS 2200 Advanced Copier, with around 61.6K in sales.

It would also be interesting to analyze more recent data and check if these trends continued after 2017.

## Business Recommendations

Based on the results, I think it would be useful to:

- Check why the Furniture category has such a low profit margin.
- Look at discounts and prices to see if they affect the profit.
- Take a closer look at the products with the highest sales.
- Continue monitoring the sales growth in the following years.
- Analyze more recent data to see if the same trends are still present.

## Tools

- Microsoft Excel
- Excel formulas
- Data cleaning
- Data aggregation
- Data analysis
- Data visualization

## Conclusion

This project helped me analyze sales data and better understand the company's sales and profit performance.

I found that sales increased over the analyzed period, especially in 2016 and 2017. Technology had the highest sales and profit, while Furniture had a much lower profit margin despite having relatively high sales.

The project also helped me practice Excel skills such as data cleaning, formulas, sorting, filtering, data aggregation, and creating charts.
