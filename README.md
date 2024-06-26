
# Electric Vehicle Analysis Dashboard in Power BI

Electric Vehicle Analysis Dashboard in Power BI
### Dashboard Link : https://app.powerbi.com/groups/me/reports/30ba3d3b-5c30-47ca-b410-357b72eb163a?experience=power-bi
Welcome to the Electric Vehicle Analysis Dashboard project. This will walk through the creation of an interactive dashboard in Power BI, designed to provide comprehensive insights into the electric vehicle market. The dashboard uses various visualization techniques to present data clearly and interactively.

Dashboard Overview
The dashboard will include multiple key performance indicators (KPIs) and various charts to visualize data such as total vehicles, average electric range, distribution by states, and top vehicle models. The theme will be green to represent green energy.

Key Features
Dynamic KPIs:

Total Vehicles
Average Electric Range
Battery Electric Vehicles (BEV)
Plug-in Hybrid Electric Vehicles (PHEV)
Interactive Charts:

Total Vehicles by Model Year: Line or area chart.
Total Vehicles by State: Map chart.
Top 10 Vehicles by Make: Bar chart.
Total Vehicles by Clean Alternative Fuel Vehicles (CAFV): Donut chart.
Top 10 Vehicles by Model: Tree map.
Interactive Filters:

City Filter
Electrical Utility Filter
Vehicle Type Filter
Make and Model Filters
Data Preparation
The dataset is sourced from Kaggle, containing electric vehicle registrations data. Follow these steps to prepare and transform the data:

Load Data:

Open Power BI Desktop.
Click on Get Data > Text/CSV.
Select CSV file and load the data.
Transform Data:

Once the data is loaded, open Power Query Editor.
Ensure headers are promoted.
Remove any unnecessary columns.
Filter out any irrelevant data or null values.
Rename columns for clarity if necessary.
Click Close & Apply to load the transformed data into Power BI.
Steps to Build the Dashboard
Creating KPIs:

Total Vehicles:
Insert a Card visual.
Set the Value to the count of vehicles.
Average Electric Range:
Insert another Card visual.
Set the Value to the average of the electric range column.
Battery Electric Vehicles (BEV):
Insert another Card visual.
Use a measure or filter to display the count of BEVs.
Plug-in Hybrid Electric Vehicles (PHEV):
Insert another Card visual.
Use a measure or filter to display the count of PHEVs.
Creating Charts:

Total Vehicles by Model Year:
Insert a Line Chart.
Set the X-axis to model year and Y-axis to the count of vehicles.
Total Vehicles by State:
Insert a Map visual.
Set the Location to state and Size to the count of vehicles.
Top 10 Vehicles by Make:
Insert a Bar Chart.
Set the Axis to vehicle make and Values to the count of vehicles.
Apply a top 10 filter to show only the top 10 makes.
Total Vehicles by CAFV:
Insert a Donut Chart.
Set the Legend to CAFV category and Values to the count of vehicles.
Top 10 Vehicles by Model:
Insert a Tree Map.
Set the Group to vehicle model and Values to the count of vehicles.
Apply a top 10 filter to show only the top 10 models.
Adding Filters:

Insert Slicers for city, electrical utility, vehicle type, make, and model.
Arrange the slicers on the dashboard for easy access.
Formatting and Styling:

Apply a green-themed background to the dashboard.
Format the visuals to ensure consistency.
Use color schemes that align with the green energy theme.
Add titles, labels, and tooltips to each visual for better context.
Problem Statement
The client requires an in-depth analysis of electric vehicle data with the following goals:

Identify the total number of electric vehicles and their distribution over time and geography.
Analyze the average electric range of these vehicles.
Differentiate between BEV and PHEV vehicles and analyze their proportions.
Identify top-performing vehicle makes and models.
Conclusion
By following these steps, we created a comprehensive and interactive Electric Vehicle Analysis Dashboard in Power BI. This project will enhance understanding of Power BI’s capabilities and provide valuable insights into the electric vehicle market.

Below is the overall view of the Dashboard:

![Screenshot 2024-06-26 141423](https://github.com/SaranNodagala/ELECTRIC-_VEHICLE/assets/161497636/6b54a014-3122-4997-bc31-16f693c050cb)


