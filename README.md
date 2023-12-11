# API de Produtos

## Descrição

Esta API foi desenvolvida utilizando o framework SpringBoot e fornece um serviço para gerenciamento de produtos.

## Requisitos

- [x] Java 17

- [x] Maven

- [x] PostgreSQL

## Instalação

Para instalar a API, siga os seguintes passos:

### Clone o repositório do GitHub:
```bash
git clone https://github.com/MarcelFeo/spring-products-api.git
```

### Entre na pasta do projeto:
```bash
cd spring-products-api
```

### Execute o comando para buildar a aplicação:
```bash
mvn clean install
```

### Crie um banco de dados PostgreSQL com o nome api_produtos.

### Inicie a aplicação:
A aplicação estará disponível em ```http://localhost:8081```

## Endpoints

A API possui os seguintes endpoints:

### GET /produtos
Lista todos os produtos.

### GET /produtos/{id}
Retorna um produto específico pelo ID.

### POST /produtos
Cria um novo produto.

### PUT /produtos/{id}
Atualiza um produto existente.

### DELETE /produtos/{id}
Exclui um produto.
