# pi-monitoring
Prometheus/Grafana kubernetes monitoring on pi-k3s cluster

This chart is a custom variation of the kube-prometheus-stack from the prometheus community.    
The main variations are the usage of arm64 images for each component, and a simpler ingress management for a classic nginx ingress controller.    

This helm chart is currently used to monitor my k3s cluster on 5 raspberry pi machines. The Grafana endpoint is accessible from outside at [grafana.k3s.thulot.fr](https://grafana.k3s.thulot.fr)