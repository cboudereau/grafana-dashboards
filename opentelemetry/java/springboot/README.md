# OpenTelemetry JVM Spring Boot dashboard

![overview](./overview.png)

Metrics are sent via micrometer-otlp.
Logs are sent via the opentelemetry exporter.

This dashboard has been built by following:
- [USE method by Brendan Gregg](https://www.brendangregg.com/usemethod.html#:~:text=The%20Utilization%20Saturation%20and%20Errors,identifying%20resource%20bottlenecks%20or%20errors.)
- [RED method](https://grafana.com/blog/2018/08/02/the-red-method-how-to-instrument-your-services/)

## Blog post with live demo
A complete [live demo](https://o11y-weekly.github.io/2024-01-31_OpenTelemetry_Looks_Good_To_Me/demo/) and [blog post](https://o11y-weekly.github.io/2024-01-31_OpenTelemetry_Looks_Good_To_Me/) with docker compose is available at [github](https://github.com/cboudereau/grafana-dashboards/tree/main/opentelemetry/java/springboot).

## Stats
![Stats](./top_10_1.png)

## RED
![RED](./top_10_2.png)

## Logs
![Logs](./top_10_8.png)

## Saturation
![Saturation](./top_10_3.png)

## Utilization (JVM)
![Utilization (JVM) part 1](./top_10_4.png)
![Utilization (JVM) part 1](./top_10_5.png)

## JVM Garbage Collection and Memory
![JVM Garbage Collection and Memory part1](./top_10_6.png)
![JVM Garbage Collection and Memory part2](./top_10_7.png)
