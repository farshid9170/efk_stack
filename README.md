# efk_stack

elasticsearch-fluentbit-kibana

Welcome to the `efk-stack-fluent-bit-elasticsearch-kibana` Git project!

This project aims to provide clear instructions and configuration files for setting up an EFK (Elasticsearch, Fluent Bit, Kibana) Stack for log aggregation and analysis.

The following is a brief overview of the components and configuration files included in this project:

- **Elasticsearch**: A distributed, RESTful search and analytics engine, used to store log data
- **Fluent Bit**: A fast and lightweight log processor and forwarder, used to collect, filter, and forward log data from various sources to Elasticsearch
- **Kibana**: A browser-based analytics and search dashboard, used to visualize and analyze log data stored in Elasticsearch

The configuration files included in this project are:

- `docker-compose.yml`: Defines the Docker services for Elasticsearch, Kibana, and Fluent Bit, as well as their configuration options and links.
- `fluent-bit.conf`: The Fluent Bit configuration file, used to specify input plugins, filters, and output plugins.
- `kibana.yml`: The Kibana configuration file, used to configure the Kibana server and connect to Elasticsearch.

To use this project, follow these steps:

run docker-compose.yml(you can change the password before start)


for fluentbit configuration most popular configuration is syslog and tail 
you can use from both sample configuration


