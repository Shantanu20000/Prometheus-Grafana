# prometheus-monitoring
Service        Port no
prometheus     9090,
node-exporter  9100,
grafana        3000.

# MasterNode (Promethesus & Grafana)
```
git clone https://github.io/shantanu20000/Prometheus-Grafana
cd Prometeus-Grafana
./install-pormetheus.sh
./install-grafana.sh
```
# WorkersNode (Node-Exporter)
```
git clone https://github.io/shantanu20000/Prometheus-Grafana
cd Prometeus-Grafana
./install-node-exporter.sh
```
# Note:-
1. Nodes Detail Stored in bellow file
```
vim /etc/prometheus/prometheus.yml
```
2. Grafana requried setup of Promotheus
```
   system>promotheus>fill feild as mention in images>save it
```
