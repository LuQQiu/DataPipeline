# Cassandra

## Dependencies

```
pip install -r requirements.txt
```
## Data storage
receive data from kafka and store data in Cassandra.

create keyspace and table using cqlsh.
```
CREATE KEYSPACE "stock" WITH replication = {'class': 'SimpleStrategy', 'replication_factor': 1} AND durable_writes = 'true';
USE stock;
CREATE TABLE stock (stock_symbol text, trade_time timestamp, trade_price float, PRIMARY KEY (stock_symbol,trade_time));
```
```
python data-storage.py stock-analyzer 192.168.99.100:9092 stock stock 192.168.99.100
```
