# Big Data Pipeline

This repo shows my project about real-time stock data pipeline. All the code is written in PYTHON. In this project, I play with various big data frameworks including Kafka, Zookeeper, Cassandra, Spark, Redis, Node.js, Bootstrap, jQuery and D3.js.  Kafka for data transportation, Spark for distributed computation, Cassandra for data storage and Node.js for data visualization.
# Project Outline
First, I received stock data from google finance and transformed them using Kafka. After receiving data from Kafka, Spark computed the average stock price of each stock each timestamp and sent the data back to Kafka. The data then flowed into Redis publisher and subscribed by Redis client. Finally, we display the real-time average stock price using Node.js, Bootstrap, jQuery and D3.js.
![picture1](https://cloud.githubusercontent.com/assets/25273483/23103566/c3e0653c-f68a-11e6-8102-1380af17091b.png)
