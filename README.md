# eck-kafka-observability-with-sidecars

(WIP)

On this repo, you are going to find the following resources:

- ECK setup
- Kafka running on Kubernetes with 3 brokers
- Kafka container producing webtraffic data to Kafka Cluster
- 3 Elasticsearch instances 
- 1 Kibana instance
- 1 Logstash with kafka input to grab data from LS and insert into ES
- Explanation how logstash kafka input works
- Commom Kafka <> Logstash issues
- Configure an ESS cluster to store monitoring data collect from ECK & Kafka cluster
- Collect Elasticsearch & Kafka using metricbeat/filebeat as a sidecard container (7.14.0)
- Configure a second ECK cluster to store a new kind of data
- Configure CCR/CCS between ECK clusters
