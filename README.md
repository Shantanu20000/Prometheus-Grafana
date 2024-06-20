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
   System > Promotheus > Fill feild as mention in images > Save it
```
![Screenshot (844)](https://github.com/Shantanu20000/Prometheus-Grafana/assets/163661534/49474573-ec5c-49f7-90c3-e8743f77c912)
