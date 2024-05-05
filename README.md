# ETL_Sales

## Description 

In this ETL project for the pharmaceutical industry, I review the sales data using dimensions like shifts, clients, dates, stores, and medicines. I extracted data from XML, JSON, and CSV files, transforming and loading it into a MySQL database. The schema was designed for efficient querying, enabling insightful analysis for strategic decision-making.

## Process

### Design of the database

The database design for this project centers on a star schema model for efficient querying and analysis in the pharmaceutical industry. The main part is the fact table containing sales transaction data, serving as the central point for analysis. Surrounding this are dimension tables representing key aspects such as shifts, clients, dates, stores, and medicines. Each dimension table provides additional context and views to the sales data, allowing a multidimensional analysis.

![image](https://github.com/27Steff/ETL_Sales/assets/53145039/1a180079-bba8-47d1-b35b-6ed2fbc436a8)

After this, I created the vault using DDL for each table and connected them through foreign keys using MySQL.


### Data

In this project, a significant portion of the data was randomly generated using Python scripts to mimic real-world pharmaceutical sales transactions. This approach ensured a diverse and representative dataset for analysis. However, before integrating this data into the database, it underwent a thorough preprocessing phase.

The data is conformed by various file types including XML, JSON, and CSV. While some data formats were compatible with direct integration into the database, others required transformation to align with the database schema. Utilizing ETL tools I integrated the data sources into the MySQL database.

![image](https://github.com/27Steff/ETL_Sales/assets/53145039/03c21a76-06b1-411e-bfa2-1940ef79f625)
