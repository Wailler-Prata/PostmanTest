# PostmanTest

        Relatório da execução dos testes disponível em https://wailler-prata.github.io/PostmanTest/

### Criação do teste.

Neste exemplo, usamos a api [Pet Store](https://petstore.swagger.io/) para a elaboração de cenários de testes independentes que são executados via Postman. Nesta execução estamos testando os EndPoints referentes a manutenção de usuários da Pet Store.

### Geração do relatório

Para a geração de report, foi utilizado ```Node.js``` e ```Newman``` com a geração através da extensão ```htmlextra```

* Comandos de execução e geração de relatório 
    ```newman run PetStore.postman_collection.json -e PetStore.postman_environment.json -r htmlextra,cli```