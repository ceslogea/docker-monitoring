# Docker Monitoring Stack

Monitoring Stack for Docker.

## Getting Started

git clone https://github.com/ceslogea/docker-monitoring.git
docker-compose -f docker-monitoring/monitoramento/docker-compose.yml up -d

## Built With

* [cAdvisor](https://github.com/google/cadvisor) - Used to provide container metrics.
* [Node Exporter](https://github.com/prometheus/node_exporter) - Used to provide hardware and OS metrics.
* [Prometheus](https://prometheus.io/) - Used as Time series database and monitoring system.
* [Grafana](https://grafana.com/) - Used for Data visualization & Monitoring.
