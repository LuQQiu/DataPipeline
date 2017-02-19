# SPARK
## Dependencies

pyspark http://spark.apache.org/docs/latest/api/python/

kafka-python https://github.com/dpkp/kafka-python
## Stream processing
```
spark-submit --jars spark-streaming-kafka-0-8-assembly_2.11-2.0.0.jar stream-processing.py stock-analyzer average-stock-price 192.168.99.100:9092

```
