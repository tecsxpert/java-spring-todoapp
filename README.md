### 1. Configuration for application.properties

Please use this for setting up the variables in the application.properties file

```
#Server Configuration
spring.application.name=todo-app
server.port=8080

#DevTools
spring.devtools.restart.enabled=true
spring.devtools.livereload.enabled=true


#MYSQL Database Configuration
spring.datasource.url=jdbc:mysql://127.0.0.1:3306/todo_db
spring.datasource.username=root
spring.datasource.password=
spring.datasource.driver-class-name=com.mysql.cj.jdbc.driver

#JPA/Hibernate Configurations
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
spring.jpa.properties.hibernate.format-sql=true
spring.jpa.properties.hibernate.dialect=org.hibernate.dialect.MySQLDialect

#Logging
logging.level.org.springframework=INFO
logging.level.com.campuspe=DEBUG
logging.level.org.hibernate.SQL=DEBUG
logging.level.org.hibernate.type.descriptor.sql.BasicBinder=TRACE
```