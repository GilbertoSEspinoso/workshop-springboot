# Projeto web services com Spring Boot e JPA / Hibernate
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/GilbertoSEspinoso/workshop-springboot/blob/main/LICENSE) 

# Sobre o projeto



Este porjeto backend se trata de um Workshop feito com Spring boot 3.1, construído durante o curso de Java Completo da DevSuperior com os obejtivos de:

- Implementar modelo de domínio
- Estruturar camadas lógicas: resource, service, repository
- Configurar banco de dados de teste (H2)
- Povoar o banco de dados
- CRUD - Create, Retrieve, Update, Delete
- Tratamento de exceções



## Modelo conceitual
![Modelo Conceitual](https://raw.githubusercontent.com/GilbertoSEspinoso/assets/main/web-services-spring-boot-jpa-hibernate/Captura%20de%20Tela%202023-06-17%20%C3%A0s%2011.11.09.png?token=GHSAT0AAAAAACDJ3U3LVWZFZ76LOUOLLE5WZEN2PRA)

# Tecnologias utilizadas
## Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
- Banco de dados: H2

# Como executar o projeto


Pré-requisitos: Java 17

```bash
# clonar repositório
git clone https://github.com/GilbertoSEspinoso/workshop-springboot.git

# entrar na pasta do projeto 
cd workshop-springboot

# executar o projeto
./mvnw spring-boot:run

# acessar o banco H2
http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb
User Name: sa
Password: n/a
```

# Endpoints
`GET/categories`

`GET/categories/{id}`
````
Retorna uma lista com todas as categorias cadastradas ou uma categoria pelo id.
````
`GET/products`

`GET/products/{id}`
````
Retorna uma lista com todos os produtos cadastrados ou um produto pelo id.
````

`GET/orders`

`GET/orders/{id}`
````
Retorna uma lista com todos os serviços cadastrados ou um serviço pelo id.
````
`GET/users/{id}`
````
Retorna um usuário cadastrado pelo id.
````
`POST/users`
````
Criar um novo usuário.

{
    "name": " nome",
    "email": "email@email.com",
    "phone": "2199999999",
    "password": "123456"
}
````
`PUT/users/{id}`
````
Atualiza um usuário existente.

{
    "name": " nome",
    "email": "email@email.com",
    "phone": "2199999999"
}
````
`DELETE/users/{id}`
````
Excluir um usuário cadastrado pelo id.
````

  

# Autor

Gilberto da Silva Espinoso

[LinkedIn] https://www.linkedin.com/in/gilbertoespns/

