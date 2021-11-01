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

# Telegraf Flow
![image](https://user-images.githubusercontent.com/5849522/139688338-1b5d06f0-ab82-4953-923c-1d93a3e1dd65.png)




# Prometheus
1. Pulls metrics data from instrumented targets with the Prometheus server
2. Visulizes metrics with the Prometheus UI
3. Send alert with the Prometheus Alert Manager
4. Receives metrics data from the Prometheus Push gateway

![image](https://user-images.githubusercontent.com/5849522/139748053-fd6a0998-6eba-43e3-bfbb-6d93de69f446.png)



