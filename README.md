Step 1: Download and Prepare Your Data Files
Dim_Products.csv, Dim_Carriers.csv, Dim_Locations.csv, Fact_Shipments.csv

Step 2: Import and Clean Data (Power Query)
Global_Logistics_Dashboard.pbix is the dashboard
Transform all the files in Power Query Editor
Ensure ShippingCost and Weight_KG are set to Decimal Number (1.2).
Ensure all ID columns (ProductID, CarrierID, etc.) are set to Whole Number (123).
Ensure ShipDate, TargetDeliveryDate, and DeliveryDate are set to Date.
Close and Apply

Step 3: Build the Data Model (Star Schema)
Arrange your tables so Fact_Shipments sits in the center, and your three Dim_ tables surround it.

Step 4: Write Your DAX Measures
_Measures table is the DAX Measures calculated table

Step 5: Design the Dashboard Canvas
Created CARD Visual with currency ($) symbol
Clustered BAR chart then Donut Chart
Slicer Visual for GlobalRegion
