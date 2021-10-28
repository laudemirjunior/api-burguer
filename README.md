# json-server-base

Esse é o repositório com a base de JSON-Server + JSON-Server-Auth já configurada, feita para ser usada no desenvolvimento das API's nos Capstones do Q2.

## Endpoints

Assim como a documentação do JSON-Server-Auth traz (https://www.npmjs.com/package/json-server-auth), existem 3 endpoints que podem ser utilizados para cadastro e 2 endpoints que podem ser usados para login.

### Cadastro

POST /register <br/>
POST /signup <br/>
POST /users

Qualquer um desses 3 endpoints irá cadastrar o usuário na lista de "Users", sendo que os campos obrigatórios são os de email e password.
Você pode ficar a vontade para adicionar qualquer outra propriedade no corpo do cadastro dos usuários.

### Login

POST /login <br/>
POST /signin

Qualquer um desses 2 endpoints pode ser usado para realizar login com um dos usuários cadastrados na lista de "Users"

---

Documentação.

POST /shirt - FORMATO DA REQUISIÇÃO

{
"title": "Nike",
"price": "100",
"userId" ${id}
}

O usuário deve estar logado e possuir o recuso gravar.

Para criação de uma nova "shirt", é necessário passar o "title", "price" e o "userID" que seria o id do usuario como parametro.

GET /shirt - FORMATO DA REQUISIÇÃO

O usuário deve estar logado para ler o recurso.

POST /shoes - FORMATO DA REQUISIÇÃO

{
"title": "Nike",
"price": "100",
"userId" ${id}
}

O usuário deve estar logado e possuir o recuso gravar.

Para criação de uma nova "shoes", é necessário passar o "title", "price" e o "userID" que seria o id do usuario como parametro.

GET /shoes - FORMATO DA REQUISIÇÃO

Todos podem ler o recurso.
# json-server-base
# json-server-hamburgueria
