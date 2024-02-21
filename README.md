# Extracting data from Electronic Medical Record Database

## Problem Statement

The EMR(Electronic Medical Record) is a digital version of a patient's paper chart in a single healthcare organization, such as a doctor's office, clinic, or hospital. EMRs contain patient health information, including medical history, diagnoses, medications, treatment plans, immunization dates, allergies, radiology images, and laboratory test results. EMRs are typically used internally within a single healthcare organization. They streamline workflows, improve patient care, and enable healthcare providers to access patient information efficiently.

To build a tetanus toxoid dashboard using data from an Electronic Medical Record (EMR) database, you would typically start by writing SQL queries to extract relevant data. 

### Steps followed 

- Step 1 : Identify Data Sources: Determine which tables in the EMR database contain the relevant information for tetanus toxoid vaccinations. This might include tables for patient demographics, medical encounters, vaccinations, and diagnoses.
- Step 2 : Data Cleaning and validation was carried to ensure data quality and intergrity is kept.
- Step 3 :  Join Tables: Using SQL JOIN operations to combine data from multiple tables when necessary. For example, I joined the patient demographics table with the immunization records table to associate each vaccination with the corresponding patient.
- Step 4 :  Filter Data: Using SQL WHERE clauses to filter the data to include only tetanus toxoid vaccinations. This might involve filtering by specific vaccine codes, vaccination dates, or other relevant criteria.
- Step 5 : Format Output: Format the output of the SQL query in a way that is suitable for visualization in the dashboard. This might involve organizing the data into rows and columns or calculating additional metrics.
- Step 6 : Test and Validate: Test the SQL query to ensure that it produces the desired results and accurately reflects the information needed for the dashboard. Validate the results against known data to confirm accuracy. 
- Step 7 : Export and save the the query table as a CSV file.
- Step 8 : The CSV file was then opened using Tableau and visualization was carried out on the data.

# SQL query
![ray-so-export](https://github.com/FaeyO/SQL---extracting-data-from-Electronic-Medical-Records-database/assets/118575325/c0fc3ebe-dba5-4b4c-b6ff-eaac6a93e245)

 
