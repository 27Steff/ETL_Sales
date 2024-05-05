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

### Objectives

Optimize sales analysis: Improve the efficiency and accuracy of reviewing sales data to gain deeper insights into pharmaceutical transactions.

Dimensional analysis: Analyze sales data through multiple dimensions such as shifts, clients, dates, stores, and medicines to identify trends and patterns.

Data integration: Integrate diverse data sources including XML, JSON, and CSV files into a unified database structure for streamlined analysis using ETL.

Database design: Design and implement a MySQL database schema tailored to the specific requirements of the pharmaceutical industry, ensuring optimal performance and scalability.

ETL pipeline development: Develop robust ETL pipelines using selected tools to extract, transform, and load data from various sources into the MySQL database, maintaining data integrity and consistency throughout the process.

Data transformation: Utilize Python scripting to randomly populate and transform data where necessary, ensuring data quality and relevance for analysis.

Insightful reporting: Enable stakeholders to make informed decisions by generating insightful reports and visualizations based on the analyzed sales data.

![image](https://github.com/27Steff/ETL_Sales/assets/53145039/054699cf-cbf7-4a11-8d64-7d1b6a9326a2)
