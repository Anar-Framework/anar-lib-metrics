### Monitoring and Metrics Library of Anar Framework with Grafana and Prometheus


#### Usage Guide: 

add the following dependency to pom.xml 


```
		<dependency>
	               <groupId>af.gov.anar.lib</groupId>
	               <artifactId>anar-lib-metrics</artifactId>
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

### Documentation 

For more information refer to wiki section of this repository