# ⭐ AutoElite Sales Performance Analysis ⭐

## ⭐ Introduction
AutoElite is a leading car dealership operating multiple showrooms across India. Following the launch of new showrooms in the East region in December 2022, the management team set ambitious sales targets for their top models: Hatchback, SUV, and Sedan. This analysis provides insights into sales trends across various regions, states, and months, culminating in visual representations such as bar charts.


## ActualTable 

https://raw.githubusercontent.com/Invact-Abhay/DOE/refs/heads/main/AutoElite_Actual.csv


## BudgetTable

https://raw.githubusercontent.com/Invact-Abhay/DOE/refs/heads/main/AutoElite_Budget.csv  



## ⭐ Steps for Analysis

### ⭐ 1. Import Required Libraries
The first step involves importing the necessary Python libraries for data manipulation and visualization.

### ⭐ 2. Load Data
Next, the actual and budgeted sales data needs to be loaded into DataFrames from the provided URLs.

### ⭐ 3. Display Column Names
Printing the column names of both DataFrames helps in understanding their structure.

### ⭐ 4. Clean Column Names
To ensure consistency, all column names should be converted to lowercase and spaces replaced with underscores.

### ⭐ 5. Aggregate Actual Sales Data
The actual sales data is then grouped by month, region, state, and product, and the total quantity sold is calculated.

### ⭐ 6. Merge Actual and Budget Data
A left join is performed to combine the budgeted sales data with the aggregated actual sales data based on common columns.

### ⭐ 7. Calculate Variance
The variance between the actual quantity sold and the budgeted quantity is computed and stored in a new column.

### ⭐ 8. Add Month Numbers
A new column is created to map month names to numerical values, which is useful for sorting.

### ⭐ 9. Summarize Variance by Month
The merged data is grouped by month and month number, and the total variance for each month is calculated and then sorted.

### ⭐ 10. Visualize Monthly Variance
A bar chart is generated to visually represent the monthly sales variance.

### ⭐ 11. Summarize Variance by Region
The data is grouped by region to calculate the total sales variance for each region.

### ⭐ 12. Visualize Regional Variance
A bar chart is created to show the region-wise variance in sales, allowing for comparison of performance across different regions.

### ⭐ 13. Summarize Variance by State
The merged data is grouped by state, and the total sales variance for each state is computed.

### ⭐ 14. Visualize State-wise Variance
A bar chart is produced to illustrate the state-wise variance in sales, helping to identify trends in different states.

## ⭐ Conclusion
This analysis provides insights into the sales performance of AutoElite's new showrooms in the East region. By visualizing monthly, regional, and state-wise variance, the company can identify trends and take corrective actions to meet sales targets more effectively.
