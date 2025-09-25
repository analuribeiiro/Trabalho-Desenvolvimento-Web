# Trabalho-Desenvolvimento-Web
Esse trabalho é uma API REST simples sem banco de dados feita em Node.js que permite gerenciar uma lista de tarefas (CRUD).  
Funcionalidades

-Criar uma nova tarefa (POST)
- Listar todas as tarefas (GET)
- Atualizar uma tarefa pelo ID (PUT)
- Deletar uma tarefa pelo ID (DELETE)

- ROTAS DA API
1. Criar tarefa

POST http://localhost:3000/tasks

Body (JSON):
{
  "title": "Estudar Node.js"
}

2. Listar tarefas

GET http://localhost:3000/tasks


3. Atualizar tarefa

PUT http://localhost:3000/tasks/1

Body (JSON):
{
  "title": "Estudar Node.js e Express",
  "done": true
}

4. Deletar tarefa

DELETE http://localhost:3000/tasks/1

