# Kafka
## Dependencies
```
pip install -r requirements.txt
```
## Simple data producer
A data producr which can grasp stock data each second and sent to kafka

## Flask data producer
A data producer which can grasp stock data for specific stock symbols based on HTTP POST and DELETE.

### Run the flask-data-producer.py
The `pwd`/config/dev.cfg file contains the information about kafka host, kafka topic, kafka port.
```
export ENV_CONFIG_FILE=`pwd`/config/dev.cfg
python flask-data-producer.py
```
