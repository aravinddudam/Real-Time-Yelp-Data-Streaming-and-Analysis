## Real-Time Yelp Data Streaming and Analysis Pipeline with Apache Spark, Kafka, and Elasticsearch

## Overview
This project provides an in-depth walkthrough for constructing a complete data engineering pipeline, utilizing TCP/IP Socket, Apache Spark, OpenAI LLM, Kafka, and Elasticsearch. It encompasses every phase, including data gathering, processing, performing sentiment analysis with ChatGPT, streaming to Kafka topics, and integrating with Elasticsearch.

## Project Architecture

1. Data Source: The dataset from yelp.com is utilized in our data pipeline.
2. TCP/IP Socket: Employs streaming of data across the network in segmented packets.
3. Apache Spark: Engaged for processing data using its master and worker architecture.
4. Confluent Kafka: Utilized as our cloud-based cluster.
5. Control Center and Schema Registry: Assists in the surveillance and schema administration of our Kafka streams.
6. Kafka Connect: Utilized for integration with Elasticsearch.
7. Elasticsearch: Employed for data indexing and search capabilities.

## System Configuration
1. Construction of a data pipeline using TCP/IP.
2. Streaming of real-time data through Apache Kafka.
3. Implementation of data processing strategies with Apache Spark.
4. Conducting real-time sentiment analysis using OpenAI ChatGPT.
5. Data synchronization from Kafka to Elasticsearch.
6. Performing data indexing and searches on Elasticsearch.

## Technology Stack
Python
TCP/IP
Confluent Kafka
Apache Spark
Docker
Elasticsearch

## Run the project locally

1. Clone the repository:
    ```bash
    git clone https://github.com/aravinddudam/Reddit-Data-Extraction-Transformation-and-Analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Reddit-Data-Extraction-Transformation-and-Analysis
    ```

3. Run Docker Compose to spin up the spark cluster:
    ```bash
    docker-compose up
    ```
