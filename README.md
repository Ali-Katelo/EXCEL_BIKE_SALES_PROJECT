# BIKE SALES PROJECT

## Project Description

This project involves the analysis of bike sales data to uncover insights about customer demographics, purchasing behavior, and income levels. The analysis is structured in an Excel workbook containing several sheets with raw data, processed data, pivot tables, and a dashboard.

## File Structure
The Excel workbook comprises the following sheets:

1.bike_buyers
2. Working_Sheet
3. Pivot_Tables
4. Dashboard

1. bike_buyers
This sheet contains raw data about bike buyers with the following columns:

ID: Unique identifier for each record.
Marital Status: Marital status of the buyer (M for Married, S for Single).
Gender: Gender of the buyer (F for Female, M for Male).
Income: Annual income of the buyer.
Children: Number of children the buyer has.
Education: Educational qualification of the buyer.
Occupation: Occupation of the buyer.
Home Owner: Home ownership status (Yes or No).
Cars: Number of cars owned.
Commute Distance: Distance the buyer commutes.
Region: Geographic region of the buyer.
Age: Age of the buyer.
Purchased Bike: Indicates whether the buyer purchased a bike (Yes or No).
2. Working_Sheet
This sheet is a cleaned and processed version of the bike_buyers data with an additional column for age brackets:

Marital Status
Gender
Income
Children
Education
Occupation
Home Owner
Cars
Commute Distance
Region
Age
Age Brackets: Categorizes ages into brackets such as Middle Age, Old, etc.
Purchased Bike
3. Pivot_Tables
This sheet contains a pivot table summarizing the data:

Average Income by Gender and Purchase Decision:
Row Labels: Gender
Column Labels: Purchased Bike (Yes/No)
Values: Average income
4. Dashboard
This sheet is designed to present a dashboard summarizing key insights from the analysis. Currently, it is a placeholder with the header "BIKE SALES DASHBOARD".

## Tools Used

* Excel


## Data Source

* https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx

## Instructions

1. **Download the Dataset:**  Download the dataset from the link provided above.
2. **Clean the Data:**  
A) Remove all Duplicates
B) Reform Marital Status & Gender Columns: Marital status of the buyer (M for Married, S for Single), Gender: Gender of the buyer (F for Female, M for Male)..
C) Introduce New Column named Age Bracket using this excel  formula {=IF(L3>54,"Old",IF(L3>=31,"Middle Age",IF(L3<31,"Adolescent","Invalid")))}

3. Pivot Tables Sheet
Overview
The Pivot_Tables sheet contains three pivot tables summarizing different aspects of the bike buyers' data. Below is a detailed description of each pivot table created in this sheet.

Pivot Table 1: Average Income by Gender and Purchase Decision (Clustered Column Chart)
Row Labels: Gender (Female, Male)
Column Labels: Purchased Bike (Yes, No)
Values: Average Income
This pivot table provides an overview of the average income of buyers segmented by gender and whether they purchased a bike. It helps in understanding the income distribution among different demographics and their purchasing decisions.

## Steps to Create Pivot Table:

Select Data: Highlight the range of data from the Working_Sheet including columns for Gender, Income, and Purchased Bike.
Insert Pivot Table:
Go to the Insert tab.
Click on PivotTable.
Choose to place the pivot table in a new worksheet or existing worksheet.
Configure Pivot Table:
Drag Gender to the Rows area.
Drag Purchased Bike to the Columns area.
Drag Income to the Values area and set it to show Average of Income.
Format Pivot Table:
Adjust the number format for the average income to display as currency or number with appropriate decimal places.
                             
## Create Clustered Column Chart:
                             
Highlight the pivot table.
Go to the Insert tab and select Clustered Column Chart.
Pivot Table 2: Customer Commute (Line Chart)
Row Labels: Commute Distance
Column Labels: Purchased Bike (Yes, No)
Values: Count of IDs
This pivot table shows the distribution of customers based on their commute distance and whether they purchased a bike.



## 3. Steps to Create Pivot Table:

Select Data: Highlight the range of data from the Working_Sheet including columns for Age Brackets and Purchased Bike.
Insert Pivot Table:
Go to the Insert tab.
Click on PivotTable.
Choose to place the pivot table in a new worksheet or existing worksheet.
Configure Pivot Table:
Drag Age Brackets to the Rows area.
Drag Purchased Bike to the Columns area.
Drag ID to the Values area and set it to show Count of IDs.
Create Stacked Line with Markers Chart:
Highlight the pivot table.
Go to the Insert tab and select Stacked Line with Markers.

4. **Dashboard Sheet

Overview
The Dashboard sheet is designed to present key insights from the bike sales analysis in a visually appealing manner. Here are the step-by-step instructions on how to build the dashboard.

Step-by-Step Instructions to Build the Dashboard
Step 1: Define the Layout

Open the Dashboard sheet.
Plan the layout by sketching the sections for various charts, tables, and key metrics.
Step 2: Insert Key Metrics

Identify key metrics such as total sales, average income of buyers, number of bikes sold, etc.
Use Excel formulas to calculate these metrics and place them at the top of the dashboard for quick reference.
Step 3: Create Charts and Visualizations

Clustered Column Chart for Average Income by Gender and Purchase Decision:

Copy the chart from the Pivot_Tables sheet.
Paste it into the designated area on the Dashboard sheet.
Line Chart for Customer Commute:

Copy the chart from the Pivot_Tables sheet.
Paste it into the designated area on the Dashboard sheet.
Stacked Line with Markers Chart for Customer Age Bracket:

Copy the chart from the Pivot_Tables sheet.
Paste it into the designated area on the Dashboard sheet.
Step 4: Add Slicers for Interactive Filtering

Insert slicers for key dimensions like Region, Gender, and Purchased Bike.
Connect slicers to the pivot tables and charts for dynamic filtering.
Step 5: Format and Style

Apply consistent formatting for fonts, colors, and borders.
Use Excel’s built-in themes and styles to enhance visual appeal.
Ensure all elements are aligned and sized appropriately.

### Conclusion
This project provides a foundational analysis of bike sales data. With further development, it can yield valuable insights for business decisions related to marketing, sales strategies, and customer segmentation.
