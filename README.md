# Documentação do Projeto

## Introdução
Este projeto consiste em uma aplicação backend para um sistema de gerenciamento de produtos. Ele fornece endpoints para realizar operações CRUD (Create, Read, Update, Delete) em uma entidade de produtos.

## Tecnologias Utilizadas
- ASP.NET Core
- Entity Framework Core
- SQL Server
- C#
- RESTful API

## Estrutura do Projeto
O projeto é estruturado da seguinte forma:

- **Backend**: Contém todo o código fonte da aplicação backend.
  - **Controllers**: Contém os controladores da API RESTful, responsáveis por gerenciar as requisições HTTP.
  - **Data**: Contém a configuração do contexto do banco de dados e as migrações.
  - **Models**: Contém as classes que representam as entidades do sistema.
  - **Migrations**: Contém as migrações do banco de dados.
- **GameStore.sln**: Solução do projeto.

## Configuração do Banco de Dados
O banco de dados utilizado é o SQL Server. As configurações de conexão podem ser encontradas no arquivo `appsettings.json` na raiz do projeto. Certifique-se de atualizar a string de conexão conforme necessário.

## Endpoints da API
A API fornece os seguintes endpoints para interação:

1. **GET /api/Products**: Retorna todos os produtos cadastrados.
2. **GET /api/Products/{id}**: Retorna um produto específico com o ID fornecido.
3. **POST /api/Products**: Cria um novo produto.
4. **PUT /api/Products/{id}**: Atualiza um produto existente com o ID fornecido.
5. **DELETE /api/Products/{id}**: Remove um produto existente com o ID fornecido.

## Uso da API
Para utilizar a API, siga os seguintes passos:

1. Clone o repositório para sua máquina local.
2. Certifique-se de ter o .NET Core SDK instalado em seu sistema.
3. Configure o banco de dados conforme descrito acima.
4. Navegue até o diretório do projeto no terminal.
5. Execute o comando `dotnet run` para iniciar a aplicação.
6. Acesse os endpoints da API usando um cliente HTTP ou ferramenta de sua escolha.

## Contribuição
Contribuições são bem-vindas! Se você encontrar algum problema ou desejar adicionar novos recursos, sinta-se à vontade para abrir uma issue ou enviar um pull request.

---
Este projeto foi desenvolvido por Igor Teixeira.
