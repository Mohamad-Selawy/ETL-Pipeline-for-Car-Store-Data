# ETL-Pipeline-for-Car-Store-Data
Built an ETL pipeline to extract data from a car store's inventory and sales systems, transform it for consistency, and load it into a data warehouse. Enabled efficient reporting on sales trends, stock levels, and customer insights.
# 1 - Extract
Scrapes data from Auction Export.
Extracts the following fields of interest:
Vin_no
Make
Model
Year
Mileage
Exterior_Color
Drivetrain
Engine
Transmission
Sale_Doc
Keys
Lot_no
Time_Left
Sale_End_Date
Location
# 2 - Transform
Cleans and transforms the extracted data.
Integrates the transformed data.
# 3 - Load
Creates a MySQL database and respective tables to match the columns of the final pandas DataFrame.
