# timeseries_database_utils
time series databases 

# Time Series databases:
1. InfluxDB
2. Prometheus
3. ElasticSearch
4. OpenTSDB
5. Postgress
6. BigTable

# Why InfluxDB:
1. Lighweight
2. Schemaless
3. Allow indexing via specific filed in the data
4. Fast data ingestion (Write) and aggregation(read0)
5. High Avaibility
6. InfluxData Stack(Kapacitor,Chronograf,Telegraf)
7.

# High Level Design Flow
 
 1. Kafka --> LogStash/Telegraf (Data Ingestion) ---> InfluxDB --->Kapacitor(Alerting) ---> InfluxDB ---> Grafana/Chronograf(UI)
 2. Faust APP (Anomaly Detection)

# InfluxDB Stack
1. UI:        Chronograf
2. Ingestion: Telegraf 
3. Alerting: Kapacitor

