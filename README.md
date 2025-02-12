# Projeto Teddy Open Finance

Projeto back-end idealizado para fins de teste de aplicação a vaga como Eng. Software Full-Stack Pleno.

![Teddy Open Finance](./screenshots/screen001.png)
![Teedy Open Finance](./screenshots/screen002.png)

- Aplicado TypeORM.
- Usei Postgres como banco de dados
- Utiliezei Docker para criar o banco e o PgAdmin
- Foi implementado sistema de auth e guard nas rora principais de criaçào de clientes.
- Organizaçào do projeto seguindo conceitos de clean architecture

Obg: Por motivos de que eu preferi focar nas funcionalidades por causa de prazo
do teste da aplicação os testes unitário não foram aplicados ao projeto.

<hr />

**O que foi usado para ter esse projeto base:**

- NestJS
- TypeORM
- JWT
- Swagger
- Postgres
- Docker
- MSW
- BCrypt

<hr />

**Variavéis de ambiente local para o projeto**

```
DB_HOST=localhost
DB_PORT=5432
DB_USER=teddy
DB_PASSWORD=teddy
DB_NAME=teddydb
DB_SYNCHRONIZE=true
DB_LOGGING=true
JWT_SECRET=COLOQUE AQUI O SEU JWT SECRET
```

**Configurando para rodar em sua máquina:**

```
1 - Clone ou baixe o repositório <br />
2 - Tenha instalado e rodando o Docker em sua máquina
3 - Execute o comando para instalar os pacotes necessários: `npm run install` <br />
4 - Rode o comando para executar os containers e subir o banco: `docker compose up -d`
3 - Rode o projeto executando o comando: `npm run start:dev` <br />
```

**PgAdmin: localhost:5050**

Acesso a documentaçao com Swagger

```
Acessar a rota: localhost/api
```

**PgAdmin: localhost:5050**

Ao abrir o PgAdmin usar as seguintes informações:

```
Aba Geral
 - Nome: O de sua escolha

Aba Conexão
 - Host name/address: db
 - Username: teddy
 - Senha: teddy
```
