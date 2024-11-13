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


- Insira o URL que foi gerado no comando _php artisan serve_
 1. Get - URL/tasks
 2. Get - URL/tasks/{id}
 3. Post - URL/tasks
 4. Put - URL/tasks/{id}
 5. Del - URL/tasks/{id}

- No método Post e Put vá em ***body***, selecione ***row*** e coloque em JSON


```
{
    "title": "Titulo da tarefa",
    "description": "Descrição da tarefa",
    "status": true
}
```

- Agora é só testar a API.


## Testando a API 
https://github.com/user-attachments/assets/dcf54ffa-5b70-45dd-b715-3d3ae21baa91



  </div>
</details>
