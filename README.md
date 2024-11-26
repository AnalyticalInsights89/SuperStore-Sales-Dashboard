# Super Store Sales Insights Dashboard 

This project involves analyzing and visualizing superstore sales data to uncover meaningful business insights. From raw data cleaning to creating an interactive dashboard in **Power BI**, this project demonstrates the end-to-end data analysis process.
 
##Project Objective
To analyze the performance of a superstore's sales across regions, categories, and time periods, providing actionable insights for better decision-making.
 
##Steps Performed**

### 1. **Data Cleaning**
- Removed duplicates and null values to ensure data accuracy.
- Standardized date formats and corrected inconsistencies.
- Verified and categorized data columns such as `Ship Mode`, `Category`, and `Segment`.
- Added calculated columns for profit margins and delivery timelines.

### 2. **Data Transformation**
- Grouped data to calculate total sales, profit, and average delivery time.
- Created additional measures such as 'Sales by Segment and `Profit by State`.
- Used DAX measures in Power BI for custom calculations, including:
  - **Profit Margin**: `(Profit / Sales) * 100
  - **Average Delivery Time**: AVERAGE(Days to Deliver)

### 3. **Dashboard Design in Power BI**
The dashboard includes the following key visualizations:
- **Cards**: Showcasing total sales, profit, and average delivery time.
- **Pie Charts**: Breaking down sales by `Segment` and `Payment Mode`.
- **Bar Charts**: Displaying sales and profit trends by sub-category and category.
- **Line Charts**: Tracking sales and profit over months and years.
- **Map Visualization**: Highlighting sales and profit distribution across states.
- **Filters**: Region-based filters (Central, East, South, West) for customized analysis.
 
## Key Insights**
1. **Top-Selling Segment**: Consumer goods contributed to 53.57% of total sales.
2. **Preferred Payment Mode**: 43.69% of transactions were Cash on Delivery (COD), followed by Online payments.
3. **Profit Analysis**: The highest profits were recorded in the **Technology** category, with a significant share from **Phones** and **Tables**.
4. **Regional Sales**: The **South region** outperformed others in terms of overall sales.
5. **Monthly Trends**: Sales peaked during the holiday season (November and December), highlighting seasonality.

## Tools Used**
- **Power BI**: For interactive dashboard creation and visualizations.
- **Excel**: For data cleaning and preprocessing.
 
## How to Use**
1. Clone this repository to your local system:
   git clone https://github.com/yourusername/super-store-sales-dashboard.git
