# Job-Data-Analysis-Dashboard

## Description
Extracted job-related data from MS SQL using Python, cleaned and transformed it in Power BI using Power Query and DAX, and built interactive dashboards to visualize job trends across locations.

## Technologies Used

- **MS SQL Server** – Storing and querying structured job-related data.
- **Python** – Connecting to SQL, extracting and preparing data.
- **Power Query (M Code)** – Data transformation within Power BI.
- **Power BI** – Interactive dashboard creation and insights.

## How the Project Works

This project follows a clear and logical flow:

1. **Data Extraction**
   - Job-related data is stored in multiple MS SQL tables.
   - A **Python script** is used to connect to MS SQL Server and extract the data.
   - Computed columns (e.g., job duration, location groupings) are created within the script before passing to Power BI.

2. **Data Cleaning & Transformation**
   - The raw SQL data is loaded into **Power BI**.
   - Using **Power Query (M Code)**:
     - Null values are handled.
     - Columns are standardized and transformed.
     - Tables are merged into a unified data model.

3. **Data Modeling**
   - Relationships are defined between tables.
   - **DAX formulas** are used to create calculated columns and measures (e.g., total jobs, job trends by location).

4. **Visualization**
   - A fully interactive **Power BI dashboard** is designed to show:
     - Job openings by location
     - Monthly hiring trends
     - Role distributions
     - KPIs and filters for deeper insights

## Repository Contents
This repository includes:
- **Dashboard Overview** – Snapshots of key visuals from the Power BI report.
- **M Code** – Scripts used in Power Query Editor for transforming the data.
- **DAX Code** – Calculated columns and measures used in the Power BI model.
- **Python Script** – Script used to connect to SQL Server and extract/prepare the data.

## Dashboard Preview
- Power BI dashboard preview see in Dashboard Overview Folder.
  
## Folder Structure
- Dax Code: File for DAX queries and calculations
- M language code: Power Query (M code) used for data transformation
- Job data analysis code: Jupyter notebook with job data analysis in Python

## Author
Trushant Jagdish
