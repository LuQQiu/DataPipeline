# Redis code

## redis-producer.py
Redis producer : consume message from kafka and publish to redis PUB.

## Code dependencies
kafka-python https://github.com/dpkp/kafka-python

redis https://pypi.python.org/pypi/redis
```
pip install -r requirements.txt
```
## Run code
I run my codes in a docker-machine called bigdata, and its ip is 192.168.99.100
```
python redis-publisher.py average-stock-price 192.168.99.100:9092 average-stock-price 192.168.99.100 6379
```
The first average-stock-price is my kafka topic.

The first IP address is my docker-machine address.

The second average-stock-price is my redis channel followed by redis host and redis port.
