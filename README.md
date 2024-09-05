

```markdown
# Consumer Goods Domain Insights and Ad-hoc Queries

## Project Overview
This project provides data-driven insights for **Atliq Hardware**, a global computer hardware manufacturer. It involves SQL queries and Power BI visualizations to help management make informed decisions based on the company's sales and financial data.

## Problem Statement
Atliq Hardware requires better insights into their sales and financial data to enhance decision-making processes. As part of their data analyst recruitment process, candidates were given a SQL challenge to showcase their data manipulation and visualization skills. The challenge focused on answering business-specific questions to assess their SQL and Power BI proficiency.

## Tasks
- Review the ad-hoc business requests and understand specific data requirements.
- Develop SQL queries to generate insights from the data.
- Create visual reports using Power BI for top-level management.
- Deliver a video presentation summarizing the findings and reports.

## Tools Used
- **MySQL**: For querying and analyzing sales and financial data.
- **Power BI**: For visualizing insights and creating interactive reports.
- **PowerPoint**: For presenting findings to the management.
- **YouTube**: For delivering a video presentation of the project.

## Quick Introduction
Atliq Hardware is a computer hardware and peripherals manufacturer with various product lines and a global customer base. The company's customers range from brick-and-mortar retailers to e-commerce platforms, selling through various channels, including retailers, distributors, and direct customers.

### Product
Products are classified into the following hierarchy:
- **Division**
- **Segment**
- **Category**
- **Products**
- **Variants**

### Customer
Atliq Hardware serves both **Brick & Mortar** and **E-Commerce** customers. Sales channels include:
- **Retailers**
- **Direct**
- **Distributors**

### Region / Market
The company operates across four major regions:
- **APAC** (Asia-Pacific)
- **EU** (Europe)
- **NA** (North America)
- **LATAM** (Latin America)

## Data Model
The data model comprises several dimensions, including product, customer, region, and fiscal year data.

## Ad-hoc Requests
Here are some key business questions addressed in this project:

1. **List of Markets**: Provide the list of markets where customer "Atliq Exclusive" operates its business in the APAC region.
2. **Product Growth**: What is the percentage increase in unique products from 2020 to 2021? Output includes:
   - `unique_products_2020`
   - `unique_products_2021`
   - `percentage_chg`
3. **Product Segments**: Provide a report of unique product counts for each segment, sorted in descending order. Output includes:
   - `segment`
   - `product_count`
4. **Manufacturing Costs**: Identify products with the highest and lowest manufacturing costs. Output includes:
   - `product_code`
   - `product`
   - `manufacturing_cost`
5. **Top Customers**: Generate a report for the top 5 customers who received the highest average discount percentages in 2021 in the Indian market. Output includes:
   - `customer_code`
   - `customer`
   - `average_discount_percentage`
6. **Gross Sales**: Provide a report of gross sales amounts for "Atliq Exclusive" across each month to identify high and low-performing months. Output includes:
   - `Month`
   - `Year`
   - `Gross sales Amount`
7. **Sales by Quarter**: Which quarter in 2020 had the highest total sold quantity? Output includes:
   - `Quarter`
   - `total_sold_quantity`
8. **Sales Channels**: Determine which sales channel contributed the most to gross sales in 2021 and its percentage of contribution. Output includes:
   - `channel`
   - `gross_sales_mln`
   - `percentage`
9. **Top Products**: List the top 3 products in each division with the highest total sold quantities in 2021. Output includes:
   - `division`
   - `product_code`

## Presentation
- [Presentation Video](#)
- [Presentation Slides](#)

## Dashboard
- [Power BI Dashboard](#)
```
