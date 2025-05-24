# Sales Analysis Project

## Problem Statement

Retail businesses generate extensive transactional data on a daily basis. However, without proper analysis, identifying meaningful trends, seasonal variations, and geographic sales patterns remains a challenge. The lack of data-driven decision-making can lead to inefficient marketing, poor inventory planning, and reduced profitability. This project aims to address this problem through detailed exploratory data analysis of sales data.

## Objective

The primary objective of this project is to analyze and extract actionable insights from retail sales data. Specific goals include:

- Identifying the month with the highest sales volume
- Determining the most profitable cities
- Recognizing top-selling products
- Analyzing hourly purchase behavior to optimize marketing strategies
- Exploring the correlation between product pricing and sales volume

## Dataset Description

The dataset used in this analysis includes sales data from a U.S.-based electronics retailer for the year 2019. The data was collected on a monthly basis and later merged for comprehensive analysis. The main attributes of the dataset are:

- `Order ID`: Unique identifier for each transaction
- `Product`: Name of the purchased item
- `Quantity Ordered`: Quantity of items purchased
- `Price Each`: Price per unit
- `Order Date`: Timestamp of the order
- `Purchase Address`: Full address of the customer

## Technologies Used

The project is implemented using Python and the following libraries:

- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- OS (for file handling)

## Implementation Details

1. **Data Collection**: Combined monthly sales CSV files into a single dataset.
2. **Data Cleaning**: Removed null values, invalid rows, and converted data types where necessary.
3. **Feature Engineering**: Extracted new features such as Month, City, Hour, and Sales.
4. **Data Analysis and Visualization**:
   - Monthly sales distribution
   - City-wise sales trends
   - Product-wise performance
   - Time-of-day analysis for marketing optimization
   - Correlation between product price and quantity sold

## Results

- **Highest Sales Month**: December recorded the highest sales, likely due to the holiday season.
- **Top Cities by Sales**: San Francisco and Los Angeles showed the highest revenue generation.
- **Top-Selling Products**: USB-C Charging Cables and AAA Batteries were the most frequently purchased items.
- **Peak Purchase Times**: Significant buying activity occurred around 11:00 AM and 7:00 PM.
- **Price vs Quantity**: Lower-priced products generally had higher sales volumes, suggesting a price-sensitive customer base.

## Conclusion

The analysis provided valuable insights for improving business performance:

- December should be prioritized for marketing and stock readiness due to high sales volume.
- Marketing campaigns should be scheduled during peak hours (11 AM and 7 PM).
- High-demand, low-cost accessories should be stocked adequately and promoted to increase volume sales.
- Regional performance data can inform inventory and logistics planning.

These insights help businesses make informed, data-driven decisions to enhance sales efficiency and customer satisfaction.

## How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/saisha3003/Sales-Analysis.git
   cd Sales-Analysis
