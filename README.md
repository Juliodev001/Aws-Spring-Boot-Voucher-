# AWS Spring Boot Voucher

API REST desenvolvida com Spring Boot para gerenciamento de vouchers, com integração à AWS.

## Tecnologias

| Tecnologia | Versão |
|---|---|
| Java | 17 |
| Spring Boot | 2.6.8 |
| Spring Boot Starter Web | 2.6.8 |
| Spring Boot Starter Data JPA | 2.6.8 |
| Spring Boot DevTools | 2.6.8 |
| Maven | 3.8+ |

## Pré-requisitos

- Java 17+
- Maven 3.8+

## Como executar

```bash
./mvnw spring-boot:run
```

A aplicação sobe em `http://localhost:8080`.

## Build

```bash
./mvnw clean package
```

O JAR gerado estará em `target/demo-0.0.1-SNAPSHOT.jar`.

```bash
java -jar target/demo-0.0.1-SNAPSHOT.jar
```

## Estrutura do projeto

```
src/
├── main/
│   ├── java/com/example/demo/
│   │   └── DemoApplication.java
│   └── resources/
│       └── application.properties
└── test/
    └── java/com/example/demo/
        └── DemoApplicationTests.java
```

## Autor

[Juliodev001](https://github.com/Juliodev001)