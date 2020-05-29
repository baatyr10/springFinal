# Ala-Too University

<img src="https://user-images.githubusercontent.com/44166990/56513684-0dd1f580-6555-11e9-8ac0-6466ed3238c2.png">

Spring Boot - Thymeleaf
------------

INTRODUCTION
------------

This project demonstrate sample spring boot to-do application with Thymeleaf

DESCRIPTION
------------

Task Execution and Scheduling


REQUIREMENTS
------------
JDK 1.8+, <br/>
Maven 3.2+,<br/>
Mysql 5.7+,<br/>
Bootstrap 3.3+, Jquery 2.1+ and Datetimepicker for Bootstrap 3
if you use JDK9 this dependency required

    ```
      <dependency>
        <groupId>javax.xml.bind</groupId>
        <artifactId>jaxb-api</artifactId>
      </dependency>
    ```
INSTALLATION
------------
 1. Clone project and import as maven project.
 2. Update MYSQL usernane and password under the <strong>application.properties</strong> 
 `spring.datasource.username=` and 
 `spring.datasource.password=`
 3. change log directory as you wish under te <strong>log4j2-spring.xml</strong> 
 `<Property name="log-path">`
 
Run Application
------------
1. You can run application
    1. `tr.com.jowl.Application class` or
    2. `mvn spring-boot:run` or
    3. run  `mvn package` then ` cd target java -jar todoApp.jar` <br/>
    <strong>Hint:</strong> `spring-boot-maven-plugin` is required for java -jar options 
    
    ```
     <plugin>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-maven-plugin</artifactId>
     </plugin>
    ```
2. [Go-to main page](http://localhost:8080/home) you will be redirected login page
    1. Click registration tab and register with any usermane and password [Go-to register page](http://localhost:8080/register) 
3. Login with your username and password [Go-to login page](http://localhost:8080/login) 
4. Add new task tab is active by default. You can add new tasks or modify existing tasks 
5. Deleted task goes to trash box (Delete tab)
    1. Click delete icon delete permanently or
    2. Click restore restore deleted task.
    
[Deploy Application](https://spr1ngproject.herokuapp.com/)
------------
[Documentation](https://github.com/baatyr10/springFinal/wiki)
------------


## Links:
**E-mail**: baatyr.birnazarov@iaau.edu.kg
<br>
**VK**: https://vk.com/baatyr_10
<br>
**Instagram**: https://www.instagram.com/23baatyr/
<br>
**Facebook**: https://www.facebook.com/baatyr.10

## License
[Apache-2.0 License](LICENSE).
<br>
[![License](https://img.shields.io/badge/License-Apache%202.0-green.svg)](https://opensource.org/licenses/Apache-2.0)
<br>
© Baatyr Birnazarov
