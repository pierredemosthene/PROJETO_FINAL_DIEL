Projeto Diel - Calendário de Tarefas
Este é um projeto de calendário de tarefas desenvolvido com React.js no frontend e Node.js no backend. O banco de dados utilizado é o MySQL.
-----------------------------------------------------------------
Funcionalidades Implementadas
Cadastro de tarefas com título, descrição, data, hora e duração
Listagem de tarefas com filtro por título
Cadastro de tags com nome
Listagem de tags com filtro por nome
Busca de feriados nacionais brasileiros para o ano de 2023
Login e autenticação de usuários
Tecnologias Utilizadas
Frontend: React.js
Backend: Node.js
Banco de Dados: MySQL
--------------------------------------------------------------
Como Testar o Aplicação:
NoFrontend  :
Abra o terminal e navegue até a pasta frontend do projeto.
Execute o comando npm install para instalar as dependências do frontend.
Execute o comando npm start para iniciar o servidor de desenvolvimento do frontend.
Abra um navegador e acesse http://localhost:3000 para visualizar a interface do usuário.
-------------------------------------------------------------
No Backend :
Abra o terminal e navegue até a pasta backend do projeto.
Execute o comando npm install para instalar as dependências do backend.
Execute o comando node server.js para iniciar o servidor do backend.
Use uma ferramenta como Postman ou cURL para testar as rotas do backend.
Banco de Dados
Crie um banco de dados MySQL chamado diel.
Execute as queries SQL fornecidas no arquivo database.sql para criar as tabelas necessárias.
Rotas do Backend
/api/tarefas: Cria uma nova tarefa (POST) ou lista todas as tarefas (GET)
/api/tags: Cria uma nova tag (POST) ou lista todas as tags (GET)
/api/feriados: Busca feriados nacionais brasileiros para o ano de 2023 (GET)
/api/login: Realiza login e autenticação de usuários (POST)
------------------------------------------------------------------
Observações
Falta algumas coisa no backend!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
