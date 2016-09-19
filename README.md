# AutomationTest-Rest-API
AutomationTest-Rest-API
This project provides Backend APIs for properties rental websites , IOS and Android devices.

## Getting Started

### Prerequisites

- [Git](https://git-scm.com/) Source Code Management
- [JDK8](http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html) JDK 1.8
- [Spring Boot](http://projects.spring.io/spring-boot/) Get App up and running as quickly as possible.
- [Maven 3](https://maven.apache.org/download.cgi) Maven Build Tool
- [Junit 4](http://junit.org/junit4/) Unit Testing Tool
- [Mysql](https://www.mysql.com/) - Databse
- [Swagger](http://swagger.io/swagger-ui/) - Swagger UI is a dependency-free collection of HTML, Javascript, and CSS assets that dynamically generate beautiful documentation and sandbox from a Swagger-compliant API.
- [Postman](http://www.getpostman.com) - Postman, tool for API testing (Manual, Automation)

### Install Postman

1. Open a Google chrome.

2. Click on: http://www.getpostman.com, click the gray button 「Chrome App (Free)」 to install it.
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/install%20postman.PNG)

### Run Rent Api Application
Run `mvn spring-boot:run` to start Rest Rent APi service. After server starting, type `http://localhost:8080/api/swagger-ui.html` to check the APIs in the Swagger Pages.
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/18-09-16/Swagger.PNG)

### Prepare Test Cases

1. Open Postman form Chrome.

2. Click the new folder button 'Create a new collection' and named your project.
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/Create%20a%20new%20collection.PNG)

3. Create new case for API call in 'New Tab': 1) Select an URL

4. Create new case for API call in 'New Tab': 2) Select API Call (GET/Put/POST/DELETE)

5. Create new case for API call in 'New Tab': 3) Set Authorization, Header, Body Information accordingly your API call (Please refer `http://localhost:8080/api/swagger-ui.html` for detais)
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/Header.PNG)
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/Body.PNG)

6. Create new case for API call in 'New Tab': 4) Set Tests to verify according your API
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/Tests%20verify.PNG)

7. Create new case for API call in 'New Tab': 5) Click on send to perform your API call
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/click%20on%20send.PNG)

8. Save the case, you can add Each API call in collection.
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/Save%20request.PNG)

### How to set parameter to the test case?


### Run the test suite.
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/Postman%20run%20test%20suite.PNG)

### Testing REST API Report

After executing the test cases, postman auto generated report.
![](https://raw.githubusercontent.com/lilliancheng2012/lilliancheng2012.github.io/master/public/img/posts/19-09-16/Poseman%20report.PNG)