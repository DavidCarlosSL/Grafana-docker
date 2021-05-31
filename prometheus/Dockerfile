FROM prom/prometheus:latest
ADD prometheus.yml /etc/prometheus/
RUN mkdir -p /etc/prometheus/container_prometheus_data
EXPOSE 9090