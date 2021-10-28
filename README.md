# continuous performance testing

All Day Devops 2021

OOP 2021


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

### grafana


* grafana dashboard: https://grafana.com/grafana/dashboards/9935
* demo docker influxdb/grafana: https://github.com/polarnik/gatling-grafana-dashboard/


### slides
[performance_en.pdf](https://github.com/cy4n/talk-performance/blob/main/performance_en.pdf)



