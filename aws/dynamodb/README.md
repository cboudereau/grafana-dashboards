# DynamoDB

Reference: https://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Monitoring-metrics-with-Amazon-CloudWatch.html

DynamoDB, Kinesis Data Streams, DynamoDB Streams metrics and Global Table metrics.

## Tables metrics
A header graphs which display important metrics for all tables in the account (datasource)
![Tables metrics](./tables.png)

## Table metrics

### Errors / Throttles / Rates / Durations
![Errors / Throttles / Rates / Durations metrics](./table-0.png)

### Table and Global Secondary Indexes Reads / Write
![Table Reads / Write](./table-1.png)
![Global Secondary Indexes Reads / Write](./table-2.png)

## Account metrics
DynamoDB is a SAAS product from AWS and comes with quotas and rate limiting.

![Account metrics](./account.png)