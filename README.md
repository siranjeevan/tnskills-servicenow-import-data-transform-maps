Import Data using Transform Maps in ServiceNow Project Overview This project demonstrates how to successfully import external data from a spreadsheet into ServiceNow. It covers the end-to-end process of data ingestion, including creating target tables, configuring import sets, building transform maps, validating data to prevent duplicates, and visualizing the results through reports.

Files Included in this Repository Sample Spreadsheet (.xlsx / .csv): The raw data source containing the mock records used for the import process.

ServiceNow Update Set (.xml): The exported configurations from my ServiceNow instance, which includes the custom tables, transform maps, and reports.

Project Milestones & Features Creation of Spreadsheet and Table: Created the initial raw data and configured the target destination table within ServiceNow.

Creation of Import Set Table and Transform Map: Configured the staging table (Import Set) and mapped the spreadsheet columns to the correct target table fields.

Transform Data, Validate, and Enable Coalesce: Executed the data transformation, validated the imported records, and configured Coalesce fields to ensure existing records update instead of creating duplicates.

Creation of Reports & Dashboards: Built ServiceNow reports to visualize the successfully imported data and organized them into a dashboard.
