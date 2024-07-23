# Data-Pipeline-and-Analytics-Solution-using-Azure-Databricks-and-Delta-Lake
Designed and implemented a comprehensive data pipeline and analytics solution leveraging Azure Databricks, Delta Lake, and Azure Data Factory to handle data ingestion, processing, and analysis.

![Architecture](https://github.com/ansel9618/Data-Pipeline-and-Analytics-Solution-using-Azure-Databricks-and-Delta-Lake/blob/main/images/Architecture.png)

**Key Responsibilities:**
- **Data Ingestion:**
  - Exported data from the Ergast website and manually imported it into the Data Lake raw container.
  - Utilized Databricks Notebooks to process and ingest data into the processed layer, applying schema and storing data in columnar format (Parquet).
  - Implemented data partitioning and added audit information such as ingestion date and data source.

- **Data Processing and Storage:**
  - Initially stored processed data in Parquet format.
  - Planned conversion of Parquet data to Delta Lake format to meet GDPR requirements, enable time travel, and other advanced features.

- **Data Transformation:**
  - Used Databricks Notebooks to transform ingested data and store results in the presentation layer.
  - Converted transformed data to Delta Lake format to leverage its benefits over traditional Data Lake.

- **Data Analysis and Reporting:**
  - Created analytical dashboards using Databricks Notebooks, sourcing data from both the ingested and presentation layers.
  - Provided a high-level overview of using Power BI to connect to Delta Lake and create BI reports.

- **Production Quality Implementation:**
  - Set up scheduling and monitoring for data pipelines to ensure regular, automated execution with minimal manual intervention.
  - Used Databricks Jobs for scheduling and addressed their limitations by integrating Azure Data Factory for more efficient pipeline orchestration and monitoring.

- **Research and Design:**
  - Conducted research on architecture solutions from Microsoft Docs and company blogs.
  - Designed the solution based on Microsoft's documented architecture used by Swiss Reinsurance, incorporating real-time events via Event Hub and batch data from Azure Data Factory.

**Technologies Used:**
- Azure Databricks
- Delta Lake
- Azure Data Factory
- Power BI
- Parquet format
- Spark



This summary highlights your project experience, key responsibilities, and the technologies you used, making it a strong addition to your resume.
