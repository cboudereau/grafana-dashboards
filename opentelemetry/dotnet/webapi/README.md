# OpenTelemetry dotnet webapi

OpenTelemetry dotnet webapi dashboard using [RED method](https://grafana.com/blog/2018/08/02/the-red-method-how-to-instrument-your-services/)

## Blog post with live demo
A complete [live demo](https://github.com/o11y-weekly/o11y-weekly.github.io/tree/main/2024-02-28_OpenTelemetry_Looks_Good_To_Me_dotnet) and [blog post](https://o11y-weekly.github.io/2024-02-28_OpenTelemetry_Looks_Good_To_Me_dotnet/) with docker compose is available at [github](https://github.com/o11y-weekly/o11y-weekly.github.io/tree/main/2024-02-28_OpenTelemetry_Looks_Good_To_Me_dotnet).

## Stats
![Stats](./1-Stats.png)

## RED
![RED](./2-RED.png)

## Metrics to traces
![Metrics to traces](./8-Metrics_to_Traces.png)

## HTTP Server
![HTTP Server](./3-HTTP-Server.png)
![HTTP Server 2](./3-HTTP-Server-2.png)

## Process
![Process](./4-Process.png)

## Runtime
![Runtime](./5-Runtime.png)

## HTTP Client
![HTTP Client](./6-HTTP-Client.png)

## Logs
![Logs](./7-Logs.png)

## Setup dotnet dependencies
```bash
dotnet add package OpenTelemetry.Exporter.OpenTelemetryProtocol
dotnet add package OpenTelemetry.Instrumentation.AspNetCore
dotnet add package OpenTelemetry.Instrumentation.Http
dotnet add package OpenTelemetry.Instrumentation.Runtime
dotnet add package System.Diagnostics.DiagnosticSource
dotnet add package OpenTelemetry.Instrumentation.Process
```