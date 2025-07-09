# cryptoData_project
In this project, I developed a cloud-native data pipeline using Azure and Databricks. 
Real-time crypto data from CoinGecko API was ingested via Python scripts, stored in Azure Blob Storage (Bronze-layer), transformed using Databricks, Unity catalogue, Autoloader and loaded to Delta Lakehouse (Gold-layer), finally loaded into Azure SQL Database for reporting with configuration of Key Vault. 
Automation was achieved with Databricks jobs and Azure Data Factory, enabling scalable, reliable and timely analytics-ready data that improves investment decisions and operational efficiency.
