# Twitter-Data-ETL-Pipeline-with-Apache-Airflow-on-AWS
This project demonstrates how to build a robust ETL (Extract, Transform, Load) pipeline that extracts Twitter data using the Twitter API, processes the data in Python, and loads it into AWS S3 storage. The pipeline is orchestrated using Apache Airflow and hosted on an AWS EC2 instance.

# Key Features
Data Extraction: Uses Tweepy to interact with the Twitter API and extract tweets.

Data Transformation: Leverages Python's Pandas library to clean and prepare data.

Data Loading: Stores the transformed data in AWS S3 for persistence and further analysis.

Automation and Orchestration: Utilizes Apache Airflow running on AWS EC2 for scheduling and automating the ETL pipeline.

# Technologies Used
Python: For scripting and data manipulation.

Apache Airflow: For workflow orchestration.

AWS EC2: As the computing environment to host Airflow.

AWS S3: For data storage.

Twitter API: For sourcing real-time data.
