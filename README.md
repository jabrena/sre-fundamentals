# sre-fundamentals

## Metrics

### Host metrics

- CPU usage	
- Load average
- Memory usage	
- Disk usage	
- Disk IO
- Network traffic

**Links:**

- https://docs.appsignal.com/metrics/host.html
- https://micrometer.io/docs/concepts
- https://www.callicoder.com/spring-boot-actuator-metrics-monitoring-dashboard-prometheus-grafana/

### JVM Metrics

- Run count and elapsed times for all supported garbage collectors
- Memory usage for all memory pools, including off-heap memory
- File descriptor usage

![](https://imgix.datadoghq.com/img/blog/java-runtime-monitoring-with-jvm-metrics/jvm-runtime-monitoring-runtime-metrics-dashboard.png?auto=format&w=1140&dpr=2)

**Links:**

- https://metrics.dropwizard.io/3.1.0/manual/jvm/
- https://www.datadoghq.com/blog/java-runtime-monitoring-with-jvm-metrics/
- https://devcenter.heroku.com/articles/language-runtime-metrics-jvm

### App Metrics

- memory usage
- garbage collection
- thread usage
- request throughout
- number of sessions
- response time
- database connection pool
- error rates
- uptime

**Links:**

- https://stackify.com/tomcat-performance-monitoring/

## Tools

- https://github.com/jiaqi/jmxterm
- https://github.com/prometheus/jmx_exporter
