#talk-performance

OOP 2021 Performance Testing talk resources

grafana dashboard: https://grafana.com/grafana/dashboards/9935
demo docker influxdb/grafana: https://github.com/polarnik/gatling-grafana-dashboard/

for simplicity all in one repo:

### gatling

gatling/ 
  - gatling gradle plugin with AuthService test scenarios in src/gatling/scala/authservice
  - gatling.conf enhanced for local graphite reporting

```
./gradlew gatlingRun
```

### wiremock

wiremock/
  - wiremock standalone mappings 

download wiremock-standaline.jar and save next to mappings folder

```bash
  java -jar wiremock-standalone.jar
```

### slides

performance_OOP.pdf 
