# University-Selection
Dashboarding and creating a data warehouse from the university selection database and adding data lakehouse with village index

## Dashboard Preview
![image](https://github.com/user-attachments/assets/8f8c804e-4ac3-448a-b76f-7dcd68bb3a24)

## Tools
- PowerBI: Data visualization and dashboarding
- mySQL: Data query
- Pentaho: Data warehousing
- Excel: Integrated database with data Lakehouse
- Vertabelo: Create star schemas data warehouse

## Project Documentation
1. **Design schema:** Define the data structure (fact/star schema) for the warehouse based on the university database.
2. **Build transformation schema:** Create a transformation schema with Pentaho to map university selection data to the warehouse schema.
3. **Data lakehouse enrichment:** Find an internet data source to enrich the data warehouse (Data source: https://satudata.go.id). This project uses a village progress dataset from Satudata
4. **Integrate data**: Integrate data with the relevant key in the warehouse with Excel.
5. **Extract, Transform, Load (ETL):** Use Pentaho to extract data from the university database and data lakehouse, perform transformations, and load the data into the warehouse.
6. **Dashboarding:** Establish a connection between the SQL data warehouse and Power BI to develop a dashboard.
