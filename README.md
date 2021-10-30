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

POST /products - FORMATO DA REQUISIÇÃO

{
"title": "Hamburguer",
"type": "Sanduíches",
"price": 14,
"image": "https://i.ibb.co/DfdVC0F/202109090436-skn5yx754p-1.png",
"id": 1
}

Qualquer usuario pode ter acesso aos dados.

GET /cart - FORMATO DA REQUISIÇÃO
POST /cart - FORMATO DA REQUISIÇÃO

{
"title": "Hamburguer",
"type": "Sanduíches",
"price": 14,
"image": "https://i.ibb.co/DfdVC0F/202109090436-skn5yx754p-1.png",
"id": 1,
"quantity", 1,
"total": 0,
"userId": ${id}
}

O usuário deve estar logado para acessar esses dados e possuir o recuso gravar para fazer alterações.

DELETE /cart - FORMATO DA REQUISIÇÃO

{
"userId": ${id}

}

# json-server-base

# json-server-hamburgueria
