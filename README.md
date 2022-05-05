# json-server

## Endpoints

link da API (https://json-aula.herokuapp.com/)

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


### Rotas 
Conter uma rota na qual todos os usuários poderão ter acesso a leitura
GET /posts

### Rotas
Conter uma rota na qual apenas os usuários logados poderão ter acesso a leitura;
GET /books
GET /bio
