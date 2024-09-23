# Spring-mvc crud operation
# using tomcat server 
```shell
Go to the Command Prompt->C:\Users\sona>startup Than Enter..

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
