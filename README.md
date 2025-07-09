# cryptoData_project
In this project, I developed a cloud-native data pipeline using Azure and Databricks. 
Real-time crypto data from CoinGecko API was ingested via Python scripts, stored in Azure Blob Storage (Bronze-layer), transformed using Databricks, Unity catalogue, Autoloader and Delta Lakehouse (Gold-layer), and loaded into Azure SQL Database. 
Automation was achieved with Databricks jobs and Azure Data Factory, enabling scalable, reliable and timely analytics-ready data that improves investment decisions and operational efficiency.
