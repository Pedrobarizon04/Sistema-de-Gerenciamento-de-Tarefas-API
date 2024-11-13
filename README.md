<div align="center">

# Sistema de Gerenciamento de Tarefas (API)

### Esse repositório contém uma API solicitada para prática e avaliação da matéria de PHP e API's.

</div>

</br>

**Instruções**

- ``` git clone ``` (link do repositório)
- ``` composer install ``` (execute no terminal para baixar as dependências do projeto)
- Inicie no XAMPP o Apache e o MySQL
-  ``` php artisan migrate  ```
- ``` php artisan serve ``` (execute no terminal para iniciar o servidor)

----

**Postman**

- Criar uma nova collection
- Adicionar 5 requests
 1. Lista todas tarefas - Get
 2. Detalhes de tarefa específica - Get
 3. Adiciona nova tarefa - Post
 4. Atualiza dados da tarefa - Put
 5. Exclui tarefa - Del

![requisições postman](https://github.com/Pedrobarizon04/Sistema-de-Gerenciamento-de-Tarefas-API/assets/124714182/2e1da62f-ce84-429a-91c1-3178fba017af)

- Insira o URL que foi gerado no comando _php artisan serve_
 1. Get - URL/tasks
 2. Get - URL/tasks/{id}
 3. Post - URL/tasks
 4. Put - URL/tasks/{id}
 5. Del - URL/tasks/{id}

- No método Post e Put vá em ***body***, selecione ***row*** e coloque em JSON

![método postman](https://github.com/Pedrobarizon04/Sistema-de-Gerenciamento-de-Tarefas-API/assets/124714182/025ed5ae-b10f-411a-b418-aeed233a11aa)

```
{
    "title": "Titulo da tarefa",
    "description": "Descrição da tarefa",
    "status": true
}
```

- Agora é só testar a API.
  
----

### Tutorial

[![](https://markdown-videos.vercel.app/youtube/B1JWzrHdaCI)]()
  
  </div>
</details>
