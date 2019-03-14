## 1. Your Github account showing that is has been forked from the depaulcdm/springpetclinic repository.
   ![Github account](https://github.com/webericzhang/spring-petclinic/blob/master/images/1.png)
   
2. Your Travis CI dashboard showing a successful first build.
   ![First build](https://github.com/webericzhang/spring-petclinic/blob/master/images/2.png)

3. The section of the POM file showing the coordinates after you’ve changed them.
   ![POM file](https://github.com/webericzhang/spring-petclinic/blob/master/images/3.png)

4. Your Travis CI dashboard showing a successful build after your change of the group ID.
   ![Successful build](https://github.com/webericzhang/spring-petclinic/blob/master/images/4.png)

5. The section of the POM file showing the coordinates after you’ve commented them out.
   ![Comment coordinates out](https://github.com/webericzhang/spring-petclinic/blob/master/images/5.png)

6. Your Travis CI dashboard showing the unsuccessful build after the breaking change.
   ![Unsuccessful build](https://github.com/webericzhang/spring-petclinic/blob/master/images/6.png)

7. Your Github repository with the readme.md file selected showing the build failed status after the Travis CI build fails.
   ![Build status](https://github.com/webericzhang/spring-petclinic/blob/master/images/7.png)

8. The section of the POM file showing the coordinates after you’ve fixed them.
   ![Fix coordinates](https://github.com/webericzhang/spring-petclinic/blob/master/images/8.png)

9. Your Travis CI dashboard showing the successful build after the breaking change has been fixed.
   ![Successful build](https://github.com/webericzhang/spring-petclinic/blob/master/images/9.1.png)
   ![All build](https://github.com/webericzhang/spring-petclinic/blob/master/images/9.2.png)

10. Your Github repository with the readme.md file selected showing the build success status after the Travis CI build has recovered.
   ![Successful build](https://github.com/webericzhang/spring-petclinic/blob/master/images/10.png)
   
## DOCKER
   [5 pts] Your dockerfile. Please provide a link to this file rather than a screen capture.
   ![Dockerfile](https://github.com/webericzhang/spring-petclinic/blob/master/Dockerfile-1)
   [5 pts] Your running docker instance as shown by a ps command.
   ![Docker instance](https://github.com/webericzhang/spring-petclinic/blob/master/images/docker/docker_instance.png)
   [5 pts] Your browser accessing the main page of the website from your local container.
   ![Browser](https://github.com/webericzhang/spring-petclinic/blob/master/images/docker/browser.png)
## DOCKER COMPOSE - MYSQL ONLY
   [5 pts] The output from the docker-compose up command.
   ![docker-compose up](https://github.com/webericzhang/spring-petclinic/blob/master/images/mysql/docker-compose-up.png)
   [5 pts] Your browser accessing the “Veterinarians” page of the website from your local container when you run the application from the host system.
   ![Browser](https://github.com/webericzhang/spring-petclinic/blob/master/images/mysql/browser.png)
   [5 pts] A section of the stack trace generated when you attempt to run the application container that has been updated to use MySQL.
   ![Stack trace](https://github.com/webericzhang/spring-petclinic/blob/master/images/mysql/trace1.png)
   ![Stack trace](https://github.com/webericzhang/spring-petclinic/blob/master/images/mysql/trace2.png)
## DOCKER COMPOSE - APP SERVER AND MYSQL
   [5 pts] Your updated docker-compose.yml file containing the application server, built from your local Dockerfile, and the existing MySQL configuration. Please provide a link to this file rather than a screen capture.
   ![docker-compose.yml](https://github.com/webericzhang/spring-petclinic/blob/master/docker-compose-3.yml)
   [5 pts] Your updated application-mysql.properties file containing the URL change for the database server. Please provide a link to this file rather than a screen capture.
   ![application-mysql.properties](https://github.com/webericzhang/spring-petclinic/blob/master/src/main/resources/application-mysql.properties)
   [5 pts] The output from the docker-compose up command.
   ![docker-compose up](https://github.com/webericzhang/spring-petclinic/blob/master/images/ApplicationANDMySQL/docker-compose-up1.png)
   ![docker-compose up](https://github.com/webericzhang/spring-petclinic/blob/master/images/ApplicationANDMySQL/docker-compose-up2.png)
   [5 pts] Your browser accessing the “Veterinarians” page of the website from your local container.
   ![Browser](https://github.com/webericzhang/spring-petclinic/blob/master/images/ApplicationANDMySQL/browser.png)