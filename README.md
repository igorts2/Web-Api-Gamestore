# Documenta��o do Projeto

## Introdu��o
Este projeto consiste em uma aplica��o backend para um sistema de gerenciamento de produtos. Ele fornece endpoints para realizar opera��es CRUD (Create, Read, Update, Delete) em uma entidade de produtos.

## Tecnologias Utilizadas
- ASP.NET Core
- Entity Framework Core
- SQL Server
- C#
- RESTful API

## Estrutura do Projeto
O projeto � estruturado da seguinte forma:

- **Backend**: Cont�m todo o c�digo fonte da aplica��o backend.
  - **Controllers**: Cont�m os controladores da API RESTful, respons�veis por gerenciar as requisi��es HTTP.
  - **Data**: Cont�m a configura��o do contexto do banco de dados e as migra��es.
  - **Models**: Cont�m as classes que representam as entidades do sistema.
  - **Migrations**: Cont�m as migra��es do banco de dados.
- **GameStore.sln**: Solu��o do projeto.

## Configura��o do Banco de Dados
O banco de dados utilizado � o SQL Server. As configura��es de conex�o podem ser encontradas no arquivo `appsettings.json` na raiz do projeto. Certifique-se de atualizar a string de conex�o conforme necess�rio.

## Endpoints da API
A API fornece os seguintes endpoints para intera��o:

1. **GET /api/Products**: Retorna todos os produtos cadastrados.
2. **GET /api/Products/{id}**: Retorna um produto espec�fico com o ID fornecido.
3. **POST /api/Products**: Cria um novo produto.
4. **PUT /api/Products/{id}**: Atualiza um produto existente com o ID fornecido.
5. **DELETE /api/Products/{id}**: Remove um produto existente com o ID fornecido.

## Uso da API
Para utilizar a API, siga os seguintes passos:

1. Clone o reposit�rio para sua m�quina local.
2. Certifique-se de ter o .NET Core SDK instalado em seu sistema.
3. Configure o banco de dados conforme descrito acima.
4. Navegue at� o diret�rio do projeto no terminal.
5. Execute o comando `dotnet run` para iniciar a aplica��o.
6. Acesse os endpoints da API usando um cliente HTTP ou ferramenta de sua escolha.

## Contribui��o
Contribui��es s�o bem-vindas! Se voc� encontrar algum problema ou desejar adicionar novos recursos, sinta-se � vontade para abrir uma issue ou enviar um pull request.

---
Este projeto foi desenvolvido por Igor Teixeira.
