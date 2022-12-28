
## 💻 Desafio Middlewares

Desafio Middewares : Validação das rotas, com a aplicação de todo já criada. Dessa vez o usuário terá um plano, onde o ele só pode criar até dez todos e um plano Pro que irá permitir criar todos ilimitados.


## :rocket:Instalação
Para rodar o repositório é necessário clonar o mesmo, dar o seguinte comando para instalar as dependencias:

```bash
$ yarn 
```

## Rodar o app

```bash
$ yarn dev
```
## Utilizar o teste

```
yarn test
```
## Rotas

    POST /users → criar um usuário.
    
    GET /users/:id → pesquisa um usuário pelo id
    
    PATCH /users/:id/pro → atualiza o plano do usuário para PRO caso não seja
   
    GET /todos → lista com todas as tarefas do usuário.
    
    POST /todos → criar um todo.
    
    PUT /todos/:id → atualiza um todo.
    
    PATCH /todos/:id/done → atualiza a propriedade done do todo para true.
    
    DELETE /todos/:id → deleta um todo pela id



![todo-list](https://user-images.githubusercontent.com/88260644/209749758-aa028c63-e379-4c57-957b-18a2ce0e07fa.gif)


<h4> 🛠 Projeto foi desenvolvido utilizando as seguintes tecnologias e conceitos: <h4>

    - Node.
    - JavaScript.
    - jest.
    - uuid
    - superTest
    - Nodemon.


