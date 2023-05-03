# API Gerenciamento Pizzaria
* API com método CRUD básico desenvolvido em ASP.NET


## Descrição do código
Essa API é um sistema simples para gerenciamento de pedidos de pizza em uma pizzaria feita no Microsoft Learn.

A API possui endpoints para realizar operações como cadastrar, atualizar e excluir pedidos de pizza, bem como listar todos os pedidos existentes. A aplicação utiliza um banco de dados em memória para armazenar os pedidos.

* GET /api/pedidos: Retorna uma lista com todos os pedidos cadastrados.
* GET /api/pedidos/{id}: Retorna um pedido específico pelo seu ID.
* POST /api/pedidos: Cria um novo pedido.
* PUT /api/pedidos/{id}: Atualiza um pedido existente pelo seu ID.
* DELETE /api/pedidos/{id}: Exclui um pedido existente pelo seu ID.

## Como executar o código
* Clone este repositório para sua máquina local
* Abra a solução WebApiPizza.sln no Visual Studio.
* Execute a aplicação pressionando F5 ou através do menu Debug > Start Debugging.
* Acesse a interface de usuário da aplicação através do navegador no endereço https://localhost:{porta}.

## Tecnologia utilizada:

* [C#] (https://docs.microsoft.com/pt-br/dotnet/csharp/)
* [ASP.NET] (https://dotnet.microsoft.com/en-us/apps/aspnet)
* [.NET] (https://dotnet.microsoft.com/)

