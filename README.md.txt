To run this project:
1. Copy the below values over to `application.properties`
2. Modify the values if needed

spring.datasource.url=jdbc:h2:mem:testdb
spring.datasource.username=sa
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=update
spring.h2.console.enabled=true
spring.h2.console.path=/h2-console

1. Copy the below values over to `application-prod.properties`
2. Modify the values if needed

spring.datasource.url=jdbc:postgresql://booksapi
spring.datasource.username=admin
spring.datasource.password=smth123