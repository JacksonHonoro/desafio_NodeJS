# Desafio NodeJS

Desafio NodeJS:

Crie uma lista de tarefas (array).

por exemplo: todo = [].

Crie as rotas com os métodos:
- GET /todo           - Listar todas tarefas.
- GET /todo/:index    - Listar uma tarefa.
- POST /todo          - Criar uma tarefa passando apenas o nome.
- PUT /todo/:index    - Editar o nome da tarefa através do índice passado nos parâmetros da rota.
- DELETE /todo/:index - Deletar a tarefa através do índice passado nos parâmetros da rota.

Crie um middleware que será utilizado apenas nas rotas que recebem index pelos parametros da URL, que verifica se a tarefa com aquele índice existe. Se existir permita que a requisição continue, se não existir mostre um erro.
