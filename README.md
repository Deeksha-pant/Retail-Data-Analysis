# Retail-Data-Analysis
This project involves real-time analysis based on an Online Retail Data Set

## Introduction and Project Overview
This project involves real-time analysis of retail data using Spark Streaming and Kafka.
The objective is to process incoming JSON data from Kafka, compute various key performance indicators (KPIs) based on time and country, and output summarized data
to the console and JSON files.

![image](https://github.com/user-attachments/assets/4a6bf2ab-753b-4289-8a98-c08085759d5e)


## Setup and Environment
- Spark Setup: Ensure Spark is installed and configured properly on your environment.

- Kafka Setup: Kafka must be installed and running.

- Dependencies: Ensure that necessary dependencies are inplace, including the Spark Kafka package (org.apache.spark:spark-sql-kafka-0-10_2.12:3.2.0).

## Architecture of the Project
 
Broadly, performed the following tasks in this project:
1.	Reading the sales data from the Kafka server.
2.	Preprocessing the data to calculate additional derived columns such as total_cost etc
3.	Calculating the time-based KPIs and time and country-based KPIs
4.	Storing the KPIs (both time-based and time- and country-based) for a 10-minute interval into separate JSON files for further analysis
