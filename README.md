# Analysis-of-Coffee-Shop-Sale-in-Lower-Manhattan-Hell-s-Kitchen-and-Astoria

![Coffee Sales](CoffeeSale.jpeg)

## Introduction 
This project involves the analysis of a transactional sales dataset from a retail coffee and bakery business operating across three different store locations. The dataset captures detailed information about each transaction, including the date and time of purchase, quantity sold, store location, product category, type, and unit price.The primary objective is to explore customer purchasing patterns, identify top selling products, evaluate sales performance by time and location, and uncover key trends in product demand. Through this analysis, the project aims to provide actionable insights that can support business decisions in areas such as inventory management, marketing strategies, and operational efficiency.
## Data Description: 
The dataset contains transactional sales records from a coffee and bakery retail chain. Each row represents a single transaction detailing product purchase made at specific times and locations.
 - transaction_id -	Unique identifier for each transaction
 - transaction_date -	Date the transaction occurred (MM/DD/YYYY format)
 - transaction_time -	Time the transaction was recorded (HH:MM:SS format)
 - transaction_qty -	Quantity of items purchased in the transaction
 - store_id -	Unique ID for the store location
 - store_location -	Name of the store location (e.g., Lower Manhattan, Hell’s Kitchen)
 - product_id -	Unique identifier for each product
 - unit_price -	Price per unit of the product in USD
 - product_category -	Broad classification of the product (e.g., Coffee, Tea, Bakery)
 - product_type -	Specific type of product (e.g., Drip coffee, Hot chocolate, Scone)
 - revenue	Total revenue generated from each transaction (in USD).
 - month	Numeric representation of the month (1 for January, 12 for December).
 - monthNAME	Full name of the month (e.g., January).
 - weekday	Numeric representation of the day of the week (1=Monday, ..., 7=Sunday).
 - weekdayNAME	Full name of the day (e.g., Sunday).
 - hour:The hour of the day the transaction took place (24-hour format).

## Data Sources: 
The dataset used for this project was obtained from Coffee Sales Company. It contains detailed transaction records including dates, times, three different store locations, product categories, quantities sold, and pricing information. The data is provided in CSV format under the file name coffee_sales_data.csv.

Data Collection and Preparation 
Raw Data Sheet: Include the raw data as a separate sheet. Label it clearly as "Raw Data 
Tools used: Excel(Add Columns Pivot Table, Pivot charts, Slicers) 

Skills demonstrated
1. Data Cleaning, Preparation  and Transformation:
 (a) Removing the duplicates
 (b) Adding Columns to Calculate Total Revenue, months, monthName,Weekday, 
      WeekdayNames,Hour
  (c)  It was formatted as table
  (d) Data visualization 
  (e)Dashboard development 
  (f) Insight Generation 

## Data Analysis:
•	The following pivot tables and chat were created:
I.	StoreLocation by Total revenue
II.	WeekDay by no of  Revenue
III.	Location by No of Revenue
IV.	Weekday by Sum of Revenue
V.	Product by No of Revenue 
VI.	Month  by Sum of Revenue
VII.	Hours by No of transaction

## Visualizations: 
This project includes several visualizations to better understand sales trends, Salespersons and Months  behavior across three different store locations and product categories. Visualizations were created using tools like Excel.

### Slicer Application: 
Slicers were added via insert > Slicers allowing dynamic filtering by fields such as Month, Salesperson, Weekday, Hours three different Locations.

## Insight from analysis:
Morning Hours Drive Most Sales: Most transactions occurred between 7:00 AM and 8:00 AM, indicating peak customer activity in the early morning hours.
Store Location Performance: Lower Manhattan saw the majority of transactions in this sample, contributing a higher total revenue compared to Hell’s Kitchen.
Sunday was a High-Traffic Day: Sunday is a popular day for hot beverages and baked goods (e.g., family outings, brunch traffic).

Popular Product Categories: Coffee remains the best-selling category overall, with items like Ethiopia Rg.
## Summary of Analysis:
The Coffee Sales dataset was analyzed to uncover patterns in product performance, customer preferences, and sales behavior across three different  store locations. The data included 149117 transaction records featuring product details, store information, quantity sold, unit price, revenue, and timestamps with extracted time-based fields like month, weekday, and hour.

## Conclusion:
The Coffee Sales analysis provides valuable insights into customer purchasing behavior, product performance, and store activity. By examining transaction-level data enriched with time-based and financial metrics, we identified key trends in product preferences and peak sales periods.
The data reveals that early mornings are the busiest hours for transactions, with coffee being the dominant product category. Flavored teas like Spicy Eye Opener Chai and premium beverages such as Drinking Chocolate also contribute significantly to revenue. Moreover, Lower Manhattan consistently generates higher transaction volumes, while Hell’s Kitchen sees fewer but higher-value purchases.
