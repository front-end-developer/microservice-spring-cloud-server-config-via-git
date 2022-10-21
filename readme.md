### Java Spring boot microservices
#### for learning only
##### Author: Mark W

Primarily, this example app stores settings, from which an app on another git repo calls to get this setting:
namely : https://github.com/front-end-developer/microservice-spring-cloud-server-config-via-git


to run do:

    ./mvnw spring-boot:run

then in postman test:
- http://localhost:8888/app1/default
- http://localhost:8888/app2/default
- http://localhost:8888/app3/default