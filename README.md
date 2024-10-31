## Tokyo-olympic-azure-data-engineering-project

This project explores the Tokyo Olympics data, leveraging Azure’s powerful data engineering services to perform end-to-end data processing and analysis. Following Darshil Parmar's tutorial, the project covers data ingestion, transformation, and storage in a scalable pipeline. It uses Azure Data Factory for orchestration, Azure Databricks for data transformation, Azure Data Lake Storage for scalable storage, and Azure Synapse Analytics for data warehousing and analysis. Visual insights are generated through Power BI, creating a comprehensive data workflow that offers insights into Olympic performance, trends, and statistics.

## Architecture Diagram
<img src="Architecture diagram of Data engineering on Tokyo olympics data.png" alt="drawing" width="800" />

## Breif overview of the project

**Data Ingestion**: Utilized **AzureDataFactory** to extract data from **github** repo and store it in **AzureDataLakeStorageGen2**.

**Data Transformation**: Employed **AzureDatabricks** for data cleaning, transformation, and processing, ensuring the data was ready for analysis.

**Data Storage**: Leveraged **AzureDatabricks** to store and manage the transformed data, making it easily accessible for querying and analysis.

**Data Analysis**: Leveraged **AzureSynapseAnalytics** serverless **sql** feature for the analysis of the transformed data.

**Data Visualization**: Created an interactive **PowerBI dashboard** to visualize the insights derived from the data, providing a comprehensive view of the Olympic events, athletes, and performances.

## Key Achievements:
• Processed and analyzed data for over 11,000 athletes across 47 disciplines and 743 teams.

• Built a scalable and efficient data pipeline using Azure's robust tools.

• Developed a user-friendly Power BI dashboard that offers valuable insights into the Tokyo Olympics.

