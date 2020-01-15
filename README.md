# `module.elk` - ContEco

An ElasticSearch based module with Kibana and Grafana.
See `conteco.docs.overview` for more information on the ContEco ecosystem.

This module provides the option of port 80 access to ElasticSearch, Grafana and Kibana using standard URL patterns.

## Configuration

The module consists of the following stacks:
* ekg - stack.ekg: ElasticSearch, Kibana and Grafana
* elasticsearch - nginx.rewrite: exposing ElasticSearch on /elk/elasticsearch
* grafana - nginx.rewrite: exposing Grafana on /elk/grafana
* kibana - nginx.rewrite: exposing Kibana on /elk/kibana

## Tags

* v1.0.0
