# Log-visualization-using-Grafana-Loki-and-Prometheus
Real time log visualization using Grafana, Loki and Prometheus

![image](https://github.com/sumanprasad007/Log-visualization-using-Grafana-Loki-and-Promtail/assets/55047333/bbec4fd1-060d-4ac3-8857-241f6775e9d0)

# **📍** Introduction:


### **🔹** Grafana:

It is an open-source platform for monitoring and observability. It provides a powerful and flexible interface for visualizing data from various sources. Loki is a horizontally-scalable, highly-available, multi-tenant log aggregation system inspired by Prometheus. Promtail is an agent that ships the logs from the application to Loki.

Hands-on Monitoring and Visualization Project In this project, we will be monitoring a sample application and visualizing its logs using Grafana, Loki, and Promtail. The application is a simple web server that generates logs for each request it receives.

### **🔹** Loki Setup and Connection:

The first step is to set up Loki. We will be using Docker to run Loki. Once Loki is up and running, we need to configure Promtail to ship the logs to Loki. We will create a configuration file for Promtail that specifies the location of the logs and the address of the Loki server. Once the configuration is set up, we can start Promtail and verify that the logs are being shipped to Loki.

### **🔹** Promtail Setup and Connection:

The next step is to set up Promtail. We will be using Docker to run Promtail. Once Promtail is up and running, we need to configure it to ship the logs to Loki. We will create a configuration file for Promtail that specifies the location of the logs and the address of the Loki server. Once the configuration is set up, we can start Promtail and verify that the logs are being shipped to Loki.

### **🔹** Grafana Project:

The final step is to set up Grafana and create a dashboard to visualize the logs. We will be using Docker to run Grafana. Once Grafana is up and running, we need to configure it to connect to Loki. We will create a data source in Grafana that points to Loki. Once the data source is set up, we can create a dashboard and add a panel to visualize the logs.
