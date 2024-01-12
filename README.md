# Tokyo-olympic-analytics
# Data Processing Pipeline

This project demonstrates how to build a data processing pipeline using various Azure services and tools. The pipeline consists of four main stages: Data Integration, Transformation, Analytics, and Dashboard. The following image illustrates the pipeline architecture:
![](https://github.com/munna710/tokyo-olympic-azure-data-engineering-project/blob/main/images/olympic-architecture.png)
## Data Integration

In this stage, data from various sources are ingested and integrated using Azure Data Factory. The integrated data is stored in Azure Data Lake Storage Gen2 as raw data.

## Transformation

In this stage, the raw data is transformed into a suitable format for analysis using Azure Databricks. The transformation process involves cleaning, filtering, aggregating, and enriching the data using Spark SQL and Python. The transformed data is stored back in Azure Data Lake Storage Gen2 as processed data.

## Analytics

In this stage, the processed data is analyzed using Azure Synapse Analytics. The results of the analysis are stored in Azure Synapse Analytics as analytical data.

## Dashboard

In this stage, the analytical data is visualized using various tools such as Power BI, Looker Studio, and Tableau. The visualization process involves creating interactive dashboards and reports that showcase the key findings and recommendations from the analysis.

