## MySql Properties
spring.datasource.url=jdbc:mysql://localhost:3306/clientManager
spring.datasource.username=root
spring.datasource.password=
spring.jpa.hibernate.ddl-auto=create-drop

## Hibernate Properties
# The SQL dialect makes Hibernate generate better SQL for the chosen database
spring.jpa.properties.hibernate.dialect = org.hibernate.dialect.MySQL5InnoDBDialect

spring.jpa.properties.hibernate.format_sql=true
spring.jpa.show-sql=true
