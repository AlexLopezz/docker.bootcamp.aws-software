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
**Open a new terminal and exec this commands:**
* ```$ git clone https://github.com/AlexLopezz/docker.bootcamp.aws-software.git ```
* ```$ cd docker.bootcamp.aws-software/ ```
* 
### Docker - mariadb: Three ways!
##### 1) Through a mariadb docker image (RECOMMENDED)
* ```$ docker pull mariadb:11.2 ```
* ```$ docker run -d -p 3306:3306 -e MYSQL_ROOT_PASSWORD=root -e MYSQL_DATABASE=myDB --rm --name mariadb mariadb:11.2 ```

##### 2) Through a dockerfile:
* ```$ docker build -t custom-mariadb:11.2 . ```
* ```$ docker run -d -p 3306:3306 custom-mariadb:11.2 ```

##### 3) Through a docker-compose:
* ```$ docker-compose up -d ```

#### do you want to stop the mariadb container? ``` docker stop compose-docker-mariadb ```

## Run project on IntelliJ
* ```$ mvn clean spring-boot:run ```
  #### do you want to stop the project? ``` ctrl + c ```
* IntelliJ Graphical Option:

[Run project-IntelliJ.webm](https://github.com/AlexLopezz/docker.bootcamp.aws-software/assets/90531107/73635634-707e-4492-ab9b-df521878078e)

### After running the project, you must go to the browser and type the following link: [http://localhost:8080](http://localhost:8080/)
###### Done!
![image](https://github.com/AlexLopezz/docker.bootcamp.aws-software/assets/90531107/d6ad9cd9-fda9-403a-993b-c04ec992b0a7)
