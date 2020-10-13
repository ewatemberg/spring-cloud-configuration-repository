# Spring Cloud Configuration Repository
Spring Cloud Config nos proporciona varias opciones a la hora de definir nuestro servidor centralizado de configuración (archivo local de configuración, archivo remoto, repositorio git…). Desde el punto de vista de un sistema en producción, lo más recomendable es tener la configuración almacenada en un repositorio Git (Github/Gitlab/Bitbucket, etc.)

##Spring Cloud Config
Uno de los problemas comunes a los que nos enfrentamos es asegurarnos que la configuración de todos nuestros microservicios sea correcta y que pueda modificarse de una manera fácil y segura.
Para dar solución a este problema contamos con la ayuda del ecosistema Spring Cloud, el cual nos recomienda la utilización de un patrón denominado configuración distribuida. Este patrón resuelve el problema de la configuración de varios microservicios mediante la creación de un servidor de configuración, accesible por todos los microservicios y en el cual se encuentra la configuración de todos los elementos de nuestro sistema. Y cómo podemos poner en práctica dicho patrón? Pues mediante uno de los componentes integrados de la plataforma Spring Cloud, concretamente Spring Cloud Config.

![alt text](https://raw.githubusercontent.com/ewatemberg/spring-cloud-configuration-repository/master/doc/img/java-microservices-with-netflix-oss-spring.jpg)

### Related
* [Configuracion Centralizada mediante Spring Cloud](https://github.com/ewatemberg/spring-cloud-configuration-server-example)
* [Servicio de Registro y Descubrimiento basado en Eureka](https://github.com/ewatemberg/eureka-discovery-server)
* [Servicio Gateway mediante Zuul](https://github.com/ewatemberg/zuul-gateway-server)
* [Microservicio Echo](https://github.com/ewatemberg/eureka-client-microservice)

###### Fuente:
[Miguel Doctor Yuste](https://medium.com/@migueldoctor/spring-cloud-series-spring-cloud-config-server-con-github-paso-a-paso-135d2b4aaf4c)