# DSCommerce API

## Sobre o projeto

API REST desenvolvida com Java e Spring Boot para simular um sistema de e-commerce, incluindo gerenciamento de usuários, produtos, pedidos e pagamentos.

O projeto foi construído com foco em boas práticas de arquitetura backend, organização em camadas e aplicação de conceitos de orientação a objetos, Clean Code e SOLID.

---

## Tecnologias utilizadas

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* Banco de dados H2
* Maven

---

## Conceitos aplicados

* Arquitetura em camadas (Controller, Service, Repository)
* Padrão DTO para transferência de dados
* Tratamento de exceções customizadas
* Validação de dados com Bean Validation
* Relacionamentos JPA:

  * OneToMany
  * ManyToOne
  * ManyToMany
* Boas práticas de Clean Code e SOLID

---

## Modelo de domínio

O sistema simula um e-commerce com as seguintes entidades:

* User
* Order
* Product
* Category
* Payment

Relacionamentos complexos foram implementados utilizando JPA/Hibernate, garantindo consistência e integridade dos dados.

---

## Endpoints principais

### Produtos

* GET /products
* GET /products/{id}

### Usuários

* GET /users
* GET /users/{id}

### Pedidos

* GET /orders
* GET /orders/{id}

---

## Como executar o projeto

```bash
# Clonar repositório
git clone https://github.com/RODR1GU3S/dscommerce-api

# Entrar na pasta
cd dscommerce-api

# Executar o projeto
./mvnw spring-boot:run
```

A aplicação estará disponível em:
http://localhost:8080

---

## Banco de dados H2

Acesse o console do banco em:
http://localhost:8080/h2-console

---

## Documentação

Você pode adicionar aqui:

* Swagger/OpenAPI (recomendado)
* Prints dos endpoints
* Coleções do Postman

---

## Objetivo do projeto

Este projeto foi desenvolvido como parte da especialização em backend Java, com foco na construção de APIs REST robustas e bem estruturadas, simulando cenários reais de negócio.

---

## Contexto profissional

O projeto também reflete experiência prática com análise de regras de negócio, adquirida ao longo de mais de 20 anos em ambiente corporativo, garantindo maior preocupação com consistência, validação e integridade dos dados.

---

## Melhorias futuras

* Implementação de autenticação com JWT
* Integração com PostgreSQL
* Documentação com Swagger/OpenAPI
* Deploy em ambiente cloud

---

## Autor

Ronaldo Rodrigues
Desenvolvedor Backend Java

* LinkedIn: https://www.linkedin.com/in/ronaldo-rodr1gu3s
* GitHub: https://github.com/RODR1GU3S
