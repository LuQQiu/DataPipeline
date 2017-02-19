# Big Data Pipeline

This repo shows my project about real-time stock data pipeline. All the code is written in PYTHON. In this project, I play with various big data frameworks including Kafka, Zookeeper, Cassandra, Spark, Redis, Node.js, Bootstrap, jQuery and D3.js.  Kafka for data transportation, Spark for distributed computation, Cassandra for data storage and Node.js for data visualization.
# Project Outline
First, I received stock data from google finance and transformed them using Kafka. After receiving data from Kafka, Spark computed the average stock price of each stock each timestamp and sent the data back to Kafka. The data then flowed into Redis publisher and subscribed by Redis client. Finally, we display the real-time average stock price using Node.js, Bootstrap, jQuery and D3.js.
![picture1](https://cloud.githubusercontent.com/assets/25273483/23103566/c3e0653c-f68a-11e6-8102-1380af17091b.png)

# Final Webpage
![3stocks](https://cloud.githubusercontent.com/assets/25273483/23103805/251d7412-f68f-11e6-9198-086f3e795777.jpeg)
![goog](https://cloud.githubusercontent.com/assets/25273483/23103807/2685dd62-f68f-11e6-9347-ea372de98628.jpeg)
![amzn](https://cloud.githubusercontent.com/assets/25273483/23103808/277a3902-f68f-11e6-8f02-92c59fd03163.jpeg)
