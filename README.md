# Welcome to my SpringBoot MVC DB CRUD!
## Technologies used:
* Java openjdk-17
* IntelliJ CE
* Lombok 1.18.24
* Maven 3.9.6
* Spring Web 3.1.2
* Spring Data JPA 3.1.2
* Spring Validation 3.1.2
* Docker
  * mariadb:11.2

# How to run it? 
### Docker - mariadb
*Open a new terminal and exec this commands:*
* ```$ docker pull mariadb:11.2 ```
* ```$ docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=myDB --rm --name mariadb mariadb:11.2 ```
#### do you want to stop the mariadb container? ``` docker stop mariadb ```
### Run project on IntelliJ 
* Terminal: *Open a new terminal and exec this command*
    * ```$ git clone https://github.com/AlexLopezz/BootcampAWSoftware.git ```
    * ```$ cd BootcampAWSoftware/docker_springbootMVC_DB-CRUD ``` 
    * ```$ mvn clean spring-boot:run ```
  #### do you want to stop the project? ``` ctrl + c ```
* IntelliJ Graphical Option:

[Run SpringBoot project.webm](https://github.com/AlexLopezz/BootcampAWSoftware/assets/90531107/8214495f-2dd1-48d0-bad9-4b97020714e9)

### After running the project, you must go to the browser and type the following link: [http://localhost:8080](http://localhost:8080/)
###### Done!
![image](https://github.com/AlexLopezz/BootcampAWSoftware/assets/90531107/8836ab56-50c1-46b7-af12-7238afb9d7bd)