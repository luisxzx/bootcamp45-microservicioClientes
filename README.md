# bootcamp45-microservicioClientes
en application.properties:se ha comentado la linea del configserver solo para poder deployarlo  a docker hub si se va realizar las pruebas en un entorno local para que funcione correctamente 
hacer los siguientes cambios al archivo application.properties




--copiar lo de abajo y reemplazar 
server.port=8080
spring.application.name=microservicios-clientes
spring.config.import=configserver:http://localhost:8888
eureka.client.serviceUrl.defaultZone=http://localhost:8761/eureka/
spring.cloud.config.enabled=true
