# Stock Market Kafka Real-Time Data Engineering Project
## Introduction
This project provides a comprehensive guide for executing an end-to-end data engineering project on real-time stock market data using Kafka. The project leverages various technologies, including Python, Amazon Web Services (AWS), Apache Kafka, Glue, Athena, and SQL, to create a robust and scalable solution.

## Architecture
<img src="Architecture.jpg">

The architecture of the project is designed to handle real-time stock market data efficiently. It incorporates components such as Apache Kafka for streaming, AWS S3 for storage, Athena for querying, Glue for ETL (Extract, Transform, Load) processes, EC2 for compute resources, and SQL for data analysis.

### Technology Used

- Programming Language - Python
- Amazon Web Service (AWS)
1. S3 (Simple Storage Service): Used for storing and managing datasets efficiently.
2. Athena Enables querying data stored in S3 using standard SQL syntax.
3. Glue Crawler Automatically discovers and organizes the dataset's structure for use in Glue jobs.
4. Glue Catalog A centralized metadata repository for managing data in AWS Glue.
5. EC2 (Elastic Compute Cloud): Provides resizable compute capacity for running applications.
- Apache Kafka A distributed event streaming platform that allows real-time data processing and communication between systems.

### Dataset Used
This project is designed to work with any stock market dataset. You can easily integrate your preferred dataset into the system to perform real-time data engineering tasks.

You can download the dataset from: https://github.com/hsjaggi/kafka-stock-market-data-engineering-project/blob/main/data/indexProcessed.csv

### Getting Started
Follow these steps to get started with the project:

#### Prerequisites:

1. Ensure you have Python installed on your system.
2. Set up an AWS account and configure your credentials.
3. Install Apache Kafka and set up the required topics.
4. Clone the Repository: <br>
    "git clone https://github.com/your-username/kafka-stock-market-data-engineering-project.git" <br>

5. Configure AWS: <br>
    Update the AWS configuration with your credentials in the project files.

6. Run the Project: <br>
    Execute the main Python script to start the real-time data processing pipeline.

7. Explore the Results: <br>
    Utilize Athena and other tools to query and analyze the processed data.
