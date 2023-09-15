# Confluent Cloud otel metrics example setup

This example shows a setup for running a docker OTeL collector to scrape metrics from Confluent Cloud and post them the New Relic OTeL Collector Endpoint.


To run the example:

```shell
export NEW_RELIC_API_KEY=<your_api_key>
export NEW_RELIC_OTLP_ENDPOINT=https://otlp.nr-data.net
export CONFLUENT_API_ID=<your_api_id>
export CONFLUENT_API_SECRET=<your_api_secret>
export CLUSTER_ID=<your_cluster_id>
export CLUSTER_API_KEY=<your_cluster_api_key>
export CLUSTER_BOOTSTRAP_SERVER=<your_cluster_bootstrap_server>

docker compose up
```

# Notes

 For assistance on finding the above variables, check the links in [our documentation](https://docs.newrelic.com/docs/more-integrations/open-source-telemetry-integrations/opentelemetry/collector/collector-configuration-examples/opentelemetry-collector-kafka-confluentcloud/)

