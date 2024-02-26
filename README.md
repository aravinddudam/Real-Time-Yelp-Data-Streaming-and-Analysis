## Real-Time Yelp Data Streaming and Analysis Pipeline with Apache Spark, Kafka, and Elasticsearch

## Overview
This project provides an in-depth walkthrough for constructing a complete data engineering pipeline, utilizing TCP/IP Socket, Apache Spark, OpenAI LLM, Kafka, and Elasticsearch. It encompasses every phase, including data gathering, processing, performing sentiment analysis with ChatGPT, streaming to Kafka topics, and integrating with Elasticsearch.

 ## Project design

- **Data Source**: We use `yelp.com` dataset for our pipeline.
- **TCP/IP Socket**: Used to stream data over the network in chunks
- **Apache Spark**: For data processing with its master and worker nodes.
- **Confluent Kafka**: Our cluster on the cloud
- **Control Center and Schema Registry**: Helps in monitoring and schema management of our Kafka streams.
- **Kafka Connect**: For connecting to elasticsearch
- **Elasticsearch**: For indexing and querying

## System Design

- Setting up data pipeline with TCP/IP 
- Real-time data streaming with Apache Kafka
- Data processing techniques with Apache Spark
- Realtime sentiment analysis with OpenAI ChatGPT
- Synchronising data from kafka to elasticsearch
- Indexing and Querying data on elasticsearch

## Tech Stack

- Python
- TCP/IP
- Confluent Kafka
- Apache Spark
- Docker
- Elasticsearch

## Run the project locally

1. Clone the repository:
    ```bash
    git clone https://github.com/airscholar/E2EDataEngineering.git
    ```

2. Navigate to the project directory:
    ```bash
    cd E2EDataEngineering
    ```

3. Run Docker Compose to spin up the spark cluster:
    ```bash
    docker-compose up
    ```

For more detailed instructions, please check out the video tutorial linked below.
