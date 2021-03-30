<div align="center">

  # Integration Spring Boot + Angular Template
  A litle project to understand how to integrate an Angular project with a Spring Boot project. keeping the Angular project embedded within the Spring Boot project. Following a monolithic architecture.


  ![](https://img.shields.io/badge/Autor-Johnatan%20Brayan-brightgreen)
  ![](https://img.shields.io/badge/Back--End-Spring%20Boot-brightgreen)
  ![](https://img.shields.io/badge/Front--End-Angular%209-brightgreen)
  
</div> 

## 🚀 Why Monolithic Architecture
If you have full-stack developers that will be working on both sides of the application a monolithic approach could make sense. If you have separate teams working on the frontend and backend splitting these projects into two independent projects might make sense. There are pros and cons to each and these should really be evaluated on a per-project basis.

Having a single deployable asset simplifies the deployment process which I know a lot of developers don't like to deal with. If you're a single developer or a team of full-stack developers this is a great option. There are some tricks to getting this all into a single project but that is exactly what you will test in this project.

### 🤔 What you need to execute

To clone and run this application, you will need [Git](https://git-scm.com), [NodeJs](https://nodejs.org/en/) - (Version: v14.16.0, npm:6.14.11) and [JKD11](https://www.oracle.com/br/java/technologies/javase-jdk11-downloads.html) installed on your computer.

### 🌀 Cloning the repository

```bash
# Cloning this repository
$ git clone https://github.com/johnatanbrayan/integration-spring-angular.git

# Access the root of the folder project on terminal/gitbash
$ cd integration-spring-angular
```

### 🎲 Running the Application

```bash
# Install the dependencies
$ ./mvnw clean install

# Run the Application in Development
$ ./mvnw spring-boot:run

# The server will start on the port:8080 - Access http://localhost:8080 to access the project.
```
### :memo: Articles that helped me
- https://bezkoder.com/integrate-angular-spring-boot/
- https://marco.dev/deploy-java-angular-one
- https://medium.com/@majdasab/integrating-an-angular-project-with-spring-boot-e3a043b7307b
- https://medium.com/@mfofana/how-to-use-angular-7-custom-elements-in-a-spring-boot-application-af84b11efc89
- https://www.danvega.dev/blog/2021/01/22/full-stack-java-vue/
- https://www.baeldung.com/spring-boot-angular-web
