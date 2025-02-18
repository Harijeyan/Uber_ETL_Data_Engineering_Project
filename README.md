# Uber Data Analytics | Modern Data Engineering GCP Project

## Introduction
This project focuses on performing data analytics on Uber trip data using modern data engineering tools and technologies within the Google Cloud Platform (GCP) ecosystem. The goal is to extract, transform, and analyze Uber trip data efficiently while leveraging cloud-based solutions for scalability and performance.

## Project Architecture
![Uber ETL Architecture](https://github.com/user-attachments/assets/62e04053-128f-47f9-90f3-75af5521abe2)

The architecture of this project follows an end-to-end data pipeline approach, incorporating:
- **Data Ingestion**: Extracting raw Uber trip data from the source.
- **Data Storage**: Storing raw and processed data in Google Cloud Storage.
- **Data Processing & Transformation**: Using Mage.ai to build and orchestrate data pipelines.
- **Data Warehousing**: Loading transformed data into BigQuery for analytical queries.
- **Data Visualization**: Creating interactive dashboards in Looker Studio to analyze key insights.

## Technologies Used
### **Programming Language**
- Python

### **Google Cloud Platform (GCP)**
- **Google Cloud Storage** – Stores raw data files.
- **Compute Engine** – Runs the ETL pipeline and processing scripts.
- **BigQuery** – Stores transformed data for analysis.
- **Looker Studio** – Creates interactive visualizations and dashboards.

### **Modern Data Pipeline Tool**
- **Mage.ai** – An open-source data pipeline tool used for ETL orchestration and automation.

## Dataset Used
This project utilizes the **TLC Trip Record Data**, which includes trip details for yellow and green taxi services in New York City. The dataset contains information such as:
- Pickup and drop-off dates/times
- Pickup and drop-off locations
- Trip distances
- Itemized fare details
- Rate types and payment types
- Driver-reported passenger counts

### **Dataset Source**
- [TLC Trip Record Data](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
- [Data Dictionary](https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf)
- [Sample Dataset Used](https://github.com/darshilparmar/uber-etl-pipeline-data-engineering-project/blob/main/data/uber_data.csv)

## Project Workflow
1. **Extracting Data**: Downloading Uber trip data from NYC TLC.
2. **Loading Data**: Storing raw data in Google Cloud Storage.
3. **Processing Data**: Using Mage.ai to transform, and load data into BigQuery.
4. **Analyzing Data**: Running SQL queries in BigQuery to extract meaningful insights and build an analytics table.
5. **Visualizing Data**: [Building interactive dashboards in Looker Studio](https://lookerstudio.google.com/reporting/e815903b-e377-48f9-ab87-fdcc5950fe0e).

Thanks to Darshil Parmar for the [Tutorial](https://youtu.be/WpQECq5Hx9g?si=H7hxkc8oLfA50Gse)
