# Atividade-Projeto-Next-Backend-TC

### Atividade realizada por:
* Christian Ferreira Toledo - 2025014378
* Thiago Santos Fonseca Amaral - 2025004649


Para que o projeto o backend possa rodar junto com o frontend é necesário seguir esse passo a passo:

Para instalar as dependências.

* npm i

Criar o arquivo .env na raiz do projeto:

* Adicionar a variável DATABASE_URL="file:./app.db"

Para gerar o banco de dados:

* npx prisma generate

Para rodar o projeto:

* npm run dev

Para abrir o prisma studio no navegador:

* npx prisma studio