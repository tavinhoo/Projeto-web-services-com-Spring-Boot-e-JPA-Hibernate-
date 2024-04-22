# Projeto Web Services com Spring Boot e JPA/Hibernate

Este é um projeto de exemplo que utiliza Spring Boot e JPA/Hibernate para criar um conjunto básico de operações CRUD (Create, Retrieve, Update, Delete) em um web service.

## Objetivos

- Criar um projeto Spring Boot em Java.
- Implementar um modelo de domínio.
- Estruturar as camadas lógicas: resource, service, repository.
- Configurar um banco de dados de teste (H2).
- Povoar o banco de dados.
- Implementar as operações CRUD.
- Tratar exceções.

## Dependências

O projeto utiliza as seguintes dependências:

```xml
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-web</artifactId>
</dependency>
<dependency>
    <groupId>org.springframework.boot</groupId>
    <artifactId>spring-boot-starter-test</artifactId>
    <scope>test</scope>
</dependency>
<dependency>
    <groupId>org.projectlombok</groupId>
    <artifactId>lombok</artifactId>
    <optional>true</optional>
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
<dependency>
    <groupId>org.postgresql</groupId>
    <artifactId>postgresql</artifactId>
    <scope>runtime</scope>
</dependency>
```


### Certifique-se de ter configurado corretamente as propriedades do banco de dados no arquivo application.properties para usar o H2 ou PostgreSQL conforme necessário.

## Executando o Projeto
Para executar o projeto, siga estas etapas:

1. Clone este repositório para o seu ambiente local.
2. Certifique-se de ter as dependências do Maven baixadas.
3. Execute a aplicação usando sua IDE ou execute o comando mvn spring-boot:run na raiz do projeto.
4. Acesse os endpoints REST para testar as operações CRUD.
##  Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para fazer um fork do projeto, implementar melhorias e enviar um pull request.

## Licença
Este projeto está licenciado sob a Licença MIT.
