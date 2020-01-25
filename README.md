### Monitoring and Metrics Library of Anar Framework with Grafana and Prometheus


#### Usage Guide: 

add the following dependency to pom.xml 


```
		<dependency>
			<groupId>af.gov.anar.core</groupId>
			<artifactId>anar-core</artifactId>
			<version>${project.version}</version>
		</dependency>
```


add following properties in `application.properties`

```properties

#Metrics related configurations
management.endpoint.metrics.enabled=true
management.endpoints.web.exposure.include=*
management.endpoint.prometheus.enabled=true
management.metrics.export.prometheus.enabled=true
```