# Uber_Data_Analytics

This repository contains the code and documentation for my Uber Data Analytics Project. The project focuses on extracting, transforming, and visualizing Uber trip data using various tools and services provided by Google Cloud Platform (GCP). Below is a detailed overview of the project workflow, tools used, and insights derived.

## Project Overview
The goal of this project is to process and analyze Uber trip data to uncover trends, patterns, and actionable insights. By leveraging modern cloud-based technologies and data visualization tools, the project demonstrates a comprehensive data pipeline—from data ingestion to dashboard creation.

## Dataset Used
TLC Trip Record Data: Yellow and green taxi trip records include fields capturing pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. During the pipeline stage, data modeling was applied by creating different tables to organize and categorize the data effectively. This approach facilitated easier and more efficient analysis in subsequent stages.

## Tools and Technologies
- **Google Cloud Platform (GCP):** Used for data storage, server setup, and analysis.
- **Mage:** A tool for building and managing ETL (Extract, Transform, Load) pipelines.
- **Google BigQuery:** A fully-managed, serverless data warehouse for querying and analyzing large datasets.
- **Looker Studio (formerly Google Data Studio):** A dashboarding tool used to create interactive visualizations.

## Project Workflow

1. **Data Access and Storage:**
   - The raw Uber trip data was uploaded to a GCP storage bucket.
   - GCP storage provided scalable and secure storage for the dataset.

2. **Server Setup:**
   - A virtual machine instance was created on GCP to host the server.
   - Required software and dependencies for the project were installed and configured on the server.

3. **Pipeline Development:**
   - **Mage** was used to design and implement the data pipeline.
   - The pipeline included steps for data cleaning, transformation, and validation.
   - Automated processes ensured consistency and accuracy during data processing.

4. **Data Analysis:**
   - Processed data was uploaded to Google BigQuery.
   - SQL queries in BigQuery were used to analyze and extract meaningful insights from the data.

5. **Dashboard Creation:**
   - The analyzed data was visualized using Looker Studio.
   - An interactive dashboard was designed to showcase trends, metrics, and key insights from the Uber data.

## Insights and Findings
 - **Payment Types**: Majority of trips were paid using credit cards, followed by cash transactions.
 - **Trip Distribution**: Most trips occurred within the New York area, with hotspots around key locations like JFK.
 - **Rate Codes**: Standard rate trips dominated, while other rates like Newark, JFK, and Negotiated fares were significantly fewer in number.

## Dashboard
The final dashboard provides an interactive view of:
 - Filters for trip data by vendor, payment type, rate code, and trip distance.
 - Summary metrics such as total revenue, record count, average tip amount, average trip distance, and average fare amount.
 - A pickup location map displaying hotspots for ride activity.
 - Bar charts visualizing the distribution of rate codes and payment types.

## Future Work
- Expand the dataset to include more cities and time frames.
- Integrate machine learning models to predict ride demand.
- Automate the entire pipeline for real-time analytics.

