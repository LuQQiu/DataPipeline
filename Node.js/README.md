# Node.js
## index.js --received data from redis
a simple webpage shows the real-time dynamic stock data.
### Dependencies

socket.io http://socket.io/

redis https://www.npmjs.com/package/redis

smoothie https://www.npmjs.com/package/smoothie

minimist https://www.npmjs.com/package/minimist
```
npm install
```
### Run code
```
node index.js --port=3000 --redis_host=192.168.99.100 --redis_port=6379 --subscribe_topic=average-stock-price
```
## redis-kafka  --received data directly from kafka
```
node index.js --port=3000 --kafka_topic=average-stock-price --kafka_broker=192.168.99.100:2181
```
