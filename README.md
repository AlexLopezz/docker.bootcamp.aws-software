# Welcome to my SpringBoot MVC DB CRUD!
## Technologies used:
* Java openjdk-17
* IntelliJ CE
* Lombok 1.18.24
* Maven 3.9.6
* Spring Web 3.1.2
* Thymeleaf 3.1.2
* Spring Data JPA 3.1.2
* Spring Validation 3.1.2
* H2-database 2.2.220

# How to run it?
### Docker - project: Two ways!

##### 1) Through a dockerfile:
* ```$ mvn clean install ```
* ```$ docker build -t spring-boot-app . ```
* ```$ docker run -d --name docker-spring-boot -p 8080:8080 spring-boot-app ```
#### do you want to stop the project container? ``` docker stop docker-spring-boot ```

##### 2) Through a docker-compose:
* ```$ mvn clean install ```
* ```$ docker-compose up -d --build ```

#### do you want to stop the project container? ``` docker stop compose-spring-boot-app ```

### After running the spring boot container, you must go to the browser and type the following link: [http://localhost:8080](http://localhost:8080/)
###### Done!
![image](https://github.com/AlexLopezz/docker.bootcamp.aws-software/assets/90531107/d6ad9cd9-fda9-403a-993b-c04ec992b0a7)