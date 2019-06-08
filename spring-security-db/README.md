# springboot-seurity-db-ui

## Spring Security Using Mysql Authorization in a Spring Boot App

This example covers the following:
- Authentication using MySql DB Connectivity using custom user details service.
- Authorization using GrantedAuthority roles for method level security
- Leveraging Spring Security's login page for injecting login details

http://localhost:8080/rest/hello/all

![hello all accessed by every one](img/helloall.png "Hello all")


http://localhost:8080/rest/hello/secured/all

![secured all accessed by users with admin role](img/secured-all.png "secured all")
username - Sam (with ADMIN Role)
password - sam


![secured all accessed by Sam](img/secured-all-success.png "secured all")

user youtube/youtube will not be able to login and he will see error page

![secured all can not be accessed by youtube with non ADMIN role](img/error.png "secured all")