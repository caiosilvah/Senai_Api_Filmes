📌 API FILMES SENAI

Neste projeto fizemos o banco de dados e as funcionalidades basicas do projeto.

🚀 Tecnologias Utilizadas

SQL / Visual Studio 2022

Banco de Dados (MySQL)

Outras bibliotecas relevantes

📦 Funcionalidades

[✔] Criar registros

[✔] Ler registros

[✔] Atualizar registros

[✔] Deletar registros

🏗 Estrutura do Projeto

📂 api-filmes
├── 📂 api-fimles-senai
│   ├── 📂 .github
│   ├── 📂 bin
│   ├── 📂 Context
│   ├── 📂 controllers
│   ├── 📂 domains
│   ├── 📂 interfaces
│   ├── 📂 Migrations
│   ├── 📂 obj
│   ├── 📂 Propetis
│   ├── 📂 Repositories
│   ├── index.js
├── 📄 .env.example
├── 📄 README.md
├── 📄 package.json

🔧 Configuração e Instalação

Pré-requisitos

Certifique-se de ter instalado:

Node.js

Banco de Dados, se necessário

Passo a Passo

Clone o repositório:

git clone https: //github.com/caiosilvah/api_filmes_senai.git

Acesse a pasta do projeto:

cd projeto-api

Instale as dependências:

npm install

Configure as variáveis de ambiente:

Renomeie o arquivo .env.example para .env

Preencha os valores necessários, como as credenciais do banco de dados

Execute as migrações do banco (caso utilize ORM como Sequelize ou Prisma):

npx sequelize db:migrate
# ou
npx prisma migrate dev

Inicie o servidor:

npm start

🔌 Endpoints da API

🟢 Criar um registro

POST /api/recurso

{
  "campo1": "valor",
  "campo2": "valor"
}

🔵 Obter todos os registros

GET /api/recurso

🟡 Atualizar um registro

PUT /api/recurso/:id

{
  "campo1": "novo valor"
}

🔴 Deletar um registro

DELETE /api/recurso/:id

🤝 Contribuição

Sinta-se à vontade para contribuir com melhorias e sugestões! Faça um fork do repositório e envie um pull request.

📜 Licença

Este projeto está licenciado sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

                                                                                                                                                                                                                                                                                                                                                 
