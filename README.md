# Sales

### Dashboard Image : 
![Screenshot 2024-12-20 182930](https://github.com/user-attachments/assets/f85ceb90-3ebd-4438-9187-dd3e5c7f0d6f)

## Problem Statement

This dashboard appears to be designed to provide an overview of sales performance across different dimensions. The goal is likely to gain insights into sales trends, identify areas for improvement, and track key performance indicators (KPIs).




### Steps followed 

- Step 1 : Load data into Power BI Desktop, dataset is a csv file.
- Step 2 : Open power query editor & in view tab under Data preview section, check "column distribution", "column quality" & "column profile" options.
- Step 3 : Also since by default, profile will be opened only for 1000 rows so you need to select "column profiling based on entire dataset".
- Step 4 : It was observed that in none of the columns errors & empty values were present except column named "Arrival Delay".
- Step 5 : For calculating average delay time, null values were not taken into account as only less than 1% values are null in this column(i.e column named "Arrival Delay") 
- Step 6 : In the report view, under the view tab, theme was selected.
- Step 7 : Since the data contains various ratings, thus in order to represent ratings, a new visual was added using the three ellipses in the visualizations pane in report view. 
- Step 8 : Visual filters (Slicers) were added for four fields named "Class", "Customer Type", "Gate Location" & "Type of travel".
- Step 9 : Two card visuals were added to the canvas, one representing average departure delay in minutes & other representing average arrival delay in minutes.
           Using visual level filter from the filters pane, basic filtering was used & null values were unselected for consideration into average calculation.
           
          
- Step 10 : A bar chart was also added to the report design area representing the number of satisfied & neutral/unsatisfied customers. While creating this visual, field named "Gender" was also added to the Legends bucket, thus number of customers are also seggregated according the gender. 

  
# Dashboard Functionality:

- Data Import:
The data for this dashboard is likely imported from various sources, such as databases, spreadsheets, or cloud platforms. The "Get Data" section in the ribbon suggests that data can be imported from various sources.

- Data Transformation:
The imported data is likely transformed and cleaned to ensure data quality and consistency. This might involve handling missing values, formatting data types, and creating calculated columns.

- Data Visualization:
The dashboard presents the data using various visualizations: 

Sum of Sales by Country: A map visualization likely shows the total sales for each country.

Sum of Sales by Segment: A pie chart likely shows the distribution of sales across different customer segments (e.g., Consumer, Corporate, Home Office).

Sum of Quantity and Sum of Profit by Year and Sales: A bar chart likely shows the trend of sales quantity and profit over time.

Average of Delivery Days: A gauge chart likely shows the average delivery time.

Sum of Returns Orders: A card likely displays the total number of returned orders.

- Filtering and Slicing:

The dashboard likely allows users to filter and slice the data to focus on specific aspects. For example, users might be able to filter data by year, region, product, or customer segment.
KPIs:

The dashboard highlights key performance indicators (KPIs) such as total sales, total quantity, average delivery days, and the number of returns.
