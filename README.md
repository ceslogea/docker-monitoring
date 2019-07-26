# Docker Monitoring Stack

A monitoring solution for Docker hosts and containers with Prometheus, Grafana, cAdvisor, NodeExporter.

## Getting Started

Clone and run stack

* git clone https://github.com/ceslogea/docker-monitoring.git
* docker-compose -f docker-monitoring/monitoring/docker-compose.yml up -d

Containers:

* Prometheus (metrics database) http://<host-ip>:9090 
* Grafana (visualize metrics) http://<host-ip>:3000
* NodeExporter (host metrics collector) http://<host-ip>:9100
* cAdvisor (containers metrics collector) http://<host-ip>:8080

Grafana is preconfigured with dashboards and Prometheus as the default data source.

## Built With

* [cAdvisor](https://github.com/google/cadvisor) - Used to provide container metrics.
* [Node Exporter](https://github.com/prometheus/node_exporter) - Used to provide hardware and OS metrics.
* [Prometheus](https://prometheus.io/) - Used as Time series database and monitoring system.
* [Grafana](https://grafana.com/) - Used for Data visualization & Monitoring.
