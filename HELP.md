## Spring Boot Config Server

##### Further information can be found on:
* [cloud.spring.io/spring-cloud-config/config-server](https://cloud.spring.io/spring-cloud-config/multi/multi__spring_cloud_config_server.html)
* [baeldung.com/spring-cloud-config/config-server](https://www.baeldung.com/spring-cloud-configuration)

##### Getting started
* Locally the application will be exposed on ``localhost:8888``
* You may need to run with Spring profile ``ldev``
* Configuration repository can be found here: [github.com/jbilandzija/spring-boot-microservice-demo-configs](https://github.com/jbilandzija/spring-boot-microservice-demo-configs)

##### Run application
* `mvn springboot:run`
* via Docker
    * run  `./docker-build.sh` to build a docker image
    * run  `./docker-run.sh` to run the spring boot container
    * stop the container with `./docker-stop.sh`
    * make sure you give your shell scripts execution rights: `` chmod +x``

