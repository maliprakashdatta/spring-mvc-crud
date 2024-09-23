# Spring-mvc crud operation
# using tomcat server 
```shell
Go to the Command Prompt->C:\Users\sona>startup Than Enter..

```
# Deploy The war file 
First to setup proper ,than copy the war file paste webapps folder
```shell
D:\setup\apache-tomcat-10.1.28\webapps
```
# Add Dependency 
```shell
<dependency>
      <groupId>com.h2database</groupId>
      <artifactId>h2</artifactId>
      <version>2.2.224</version>
      <scope>runtime</scope>
    </dependency>
```
## DataBase H2 
```shell

    <bean id="dataSource" class="org.springframework.jdbc.datasource.DriverManagerDataSource">
        <property name="driverClassName" value="org.h2.Driver"/>
        <property name="url" value="jdbc:h2:mem:testdb;DB_CLOSE_DELAY=-1"/>
        <property name="username" value="sa"/>
        <property name="password" value=""/>
    </bean>
```
 
## Add emp Screen Shot
http://localhost:8080/emp-management/add

<image src="https://github.com/user-attachments/assets/2674e991-b940-489e-bf04-10b44da20f1b" width="750" height="350">


## Add view Screen Shot
http://localhost:8080/emp-management/view

<image src="https://github.com/user-attachments/assets/1ffa097f-51d9-4458-8ba5-4c29d5f124a5" width="750" height="350">

