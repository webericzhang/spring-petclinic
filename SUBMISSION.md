## DOCKER
### [5 pts] Your dockerfile. Please provide a link to this file rather than a screen capture.
    [Dockerfile](https://github.com/webericzhang/spring-petclinic/blob/master/Dockerfile-1){:target="_blank"} 
### [5 pts] Your running docker instance as shown by a ps command.
   ![Docker instance](https://github.com/webericzhang/spring-petclinic/blob/master/images/docker/docker_instance.png)
### [5 pts] Your browser accessing the main page of the website from your local container.
   ![Browser](https://github.com/webericzhang/spring-petclinic/blob/master/images/docker/browser.png)
## DOCKER COMPOSE - MYSQL ONLY
### [5 pts] The output from the docker-compose up command.
   ![docker-compose up](https://github.com/webericzhang/spring-petclinic/blob/master/images/mysql/docker-compose-up.png)
### [5 pts] Your browser accessing the “Veterinarians” page of the website from your local container when you run the application from the host system.
   ![Browser](https://github.com/webericzhang/spring-petclinic/blob/master/images/mysql/browser.png)
### [5 pts] A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL.
   ![Stack trace](https://github.com/webericzhang/spring-petclinic/blob/master/images/mysql/trace1.png)
   ![Stack trace](https://github.com/webericzhang/spring-petclinic/blob/master/images/mysql/trace2.png)
## DOCKER COMPOSE - APP SERVER AND MYSQL
### [5 pts] Your updated docker-compose.yml file containing the application server, built from your local Dockerfile, and the existing MySQL configuration. Please provide a link to this file rather than a screen capture.
    [docker-compose.yml](https://github.com/webericzhang/spring-petclinic/blob/master/docker-compose-3.yml){:target="_blank"} 
### [5 pts] Your updated application-mysql.properties file containing the URL change for the database server. Please provide a link to this file rather than a screen capture.
    [application-mysql.properties](https://github.com/webericzhang/spring-petclinic/blob/master/src/main/resources/application-mysql.properties){:target="_blank"} 
### [5 pts] The output from the docker-compose up command.
   ![docker-compose up](https://github.com/webericzhang/spring-petclinic/blob/master/images/ApplicationANDMySQL/docker-compose-up1.png)
   ![docker-compose up](https://github.com/webericzhang/spring-petclinic/blob/master/images/ApplicationANDMySQL/docker-compose-up2.png)
### [5 pts] Your browser accessing the “Veterinarians” page of the website from your local container.
   ![Browser](https://github.com/webericzhang/spring-petclinic/blob/master/images/ApplicationANDMySQL/browser.png)