<h1 align="center" > 🔶 AtliQ Mart 🔶 </h1> 
<h2 align="center" > Electric Vehicle Sales Analysis And Forecasting </h2> 
<p align="center">
  <img src="Image/EV_IMAGE.png" alt="EV IMAGE" width="700">
</p>




Dataset include 3 CSV files:

1. sales by state, 
2. sales by maker
3. date dimension


*******************************************
electric_vehicle_sales_by_state.csv

- date: The date on which the data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- state: The name of the state where the sales data is recorded. This indicates the geographical location within India.
- vehicle_category: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- electric_vehicles_sold: The number of electric vehicles sold in the specified state and category on the given date.
- total_vehicles_sold: The total number of vehicles (including both electric and non-electric) sold in the specified state and category on the given date.

*******************************************


*******************************************
electric_vehicle_sales_by_makers.csv

- date: The date on which the sales data was recorded. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- vehicle_category: The category of the vehicle, specifying whether it is a 2-Wheeler or a 4-Wheeler.
- maker: The name of the manufacturer or brand of the electric vehicle.
- electric_vehicles_sold: The number of electric vehicles sold by the specified maker in the given category on the given date.

*******************************************


*******************************************
dim_date.csv

- date: The specific date for which the data is relevant. Format: DD-MMM-YY. (Data is recorded on a monthly basis)
- fiscal_year: The fiscal year to which the date belongs. This is useful for financial and business analysis.
- quarter: The fiscal quarter to which the date belongs. Fiscal quarters are typically divided as Q1, Q2, Q3, and Q4.

*******************************************


Few Key Points:

1. Fiscal Year: The fiscal year is a one-year period used for financial reporting and budgeting, starting on April 1st and ending on March 31st of the following year in India.

2. Penetration Rate: This metric represents the percentage of total vehicles that are electric within a specific region or category. It is calculated as:
		Penetration Rate =  (Electric Vehicles Sold / Total Vehicles Sold) * 100  
   This indicates the adoption level of electric vehicles.

3. Compound Annual Growth Rate (CAGR): CAGR measures the mean annual growth rate over a specified period longer than one year. It is calculated as:
		CAGR = [(Ending Value / Beginning Value) ** 1/n] -1

