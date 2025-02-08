# End-to-End Data Pipeline with Azure & MongoDB

![Data Pipeline Architecture](https://raw.githubusercontent.com/anshul-jain-devx108/Big_Data_Engineering/main/Data%20Pipeline%20Architecture.png)


## Overview
This project implements a scalable ETL (Extract, Transform, Load) pipeline using **Azure Cloud Services** and **MongoDB** for data ingestion, transformation, storage, and visualization.

## Tech Stack
- **Azure Data Factory** – Data ingestion from multiple sources (GitHub, SQL Tables).
- **Azure Data Lake Storage (ADLS Gen2)** – Storage for raw and transformed data.
- **Azure Databricks** – Data transformation and enrichment.
- **MongoDB** – Auxiliary database for data enrichment.
- **Azure Synapse Analytics** – Data processing and querying.
- **Power BI, Tableau, Fabric** – Data visualization and reporting.

## Workflow
1. **Data Ingestion:**
   - Extract data from **HTTP sources (GitHub)** and **SQL tables** using **Azure Data Factory**.
   - Store raw data in **Azure Data Lake Storage (ADLS Gen2)**.

2. **Data Transformation:**
   - Process raw data using **Azure Databricks**.
   - Perform data cleansing, aggregation, and enrichment using **MongoDB**.
   
3. **Storage & Processing:**
   - Store transformed data in **ADLS Gen2**.
   - Load structured data into **Azure Synapse Analytics** for querying and analytics.

4. **Visualization & Insights:**
   - Use **Power BI, Tableau, or Fabric** to create dashboards and visual reports.

## Features
✅ Automated data pipeline using **Azure Data Factory**.
✅ Real-time data processing and enrichment with **Azure Databricks** & **MongoDB**.
✅ Scalable cloud-based architecture for large datasets.
✅ Interactive dashboards for business intelligence and reporting.

## Folder Structure
1.DataIngestiontoDB
Helps connect with the database deployed on Filess.io.
Uploads data from local host in CSV format to SQL on Filess.io.
**Further files are under progress.



## Installation & Setup
### Prerequisites:
- Azure subscription with access to **Azure Data Factory, Databricks, Synapse, and ADLS Gen2**.
- MongoDB instance (local or cloud-based).
- Power BI/Tableau/Fabric for visualization.

### Steps:
1. Clone this repository:
   ```sh
   git clone https://github.com/anshul-jain-devx108/Big_Data_Engineering.git
   ```
2. Set up **Azure Data Factory** to fetch data from your sources.
3. Configure **ADLS Gen2** to store raw and transformed data.
4. Deploy **Databricks notebooks** for data processing.
5. Set up **MongoDB** for enrichment tables.
6. Load transformed data into **Synapse Analytics**.
7. Connect **Power BI/Tableau/Fabric** for visualization.

## Future Improvements
- Implement **CI/CD pipelines** for automated deployment.
- Add **real-time streaming** capabilities with **Azure Stream Analytics**.
- Optimize **cost and performance** by leveraging **serverless computing**.

## Contributing
Feel free to fork this repository and contribute by submitting a pull request.

## License
This project is licensed under the MIT License.
