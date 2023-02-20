# LAB-H2-IETI
Configuracion Base de Datos H2 en Springboot

# Dependencies

```
    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-web</artifactId>
    </dependency>

    <dependency>
        <groupId>org.springframework.boot</groupId>
        <artifactId>spring-boot-starter-data-jpa</artifactId>
    </dependency>

    <dependency>
        <groupId>com.h2database</groupId>
        <artifactId>h2</artifactId>
        <scope>runtime</scope>
    </dependency>
```

# Configure application properties:
```
    spring.datasource.url=jdbc:h2:mem:testdb
    spring.jpa.defer-datasource-initialization=true
    spring.h2.console.enabled=true
    spring.datasource.driverClassName=org.h2.Driver
    spring.datasource.username=sa
    spring.datasource.password=
    spring.jpa.database-platform=org.hibernate.dialect.H2Dialect
```

# Author

Yesid Camilo Mora Barbosa
