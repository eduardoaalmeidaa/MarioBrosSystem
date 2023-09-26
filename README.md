# Mario Bros CRUD MVC

![image](https://github.com/eduardoaalmeidaa/MVCCRUD/assets/89856553/485a5855-0a78-4b46-809c-2c411f738609)
![image](https://github.com/eduardoaalmeidaa/MVCCRUD/assets/89856553/8ddf6a7a-5c1b-40f0-9bb1-03396697b9ec)
![image](https://github.com/eduardoaalmeidaa/MVCCRUD/assets/89856553/043d7cbe-6982-4808-8663-da3a4b748aa2)
![image](https://github.com/eduardoaalmeidaa/MVCCRUD/assets/89856553/8f6cb296-f666-4c5d-94a1-0ee85173508a)
![image](https://github.com/eduardoaalmeidaa/MVCCRUD/assets/89856553/78b756ca-0d87-4ad8-b2e0-b6e1c1474fb3)

Este é um projeto CRUD MVC para uma lista de contatos inspirado no universo do Mario Bros, desenvolvido usando C#, HTML, CSS, JavaScript e banco de dados SQL Server.

## Visão Geral

- **C**reate: Adicionar contatos ao banco de dados.
- **R**ead: Visualizar informações detalhadas do contato, como; Nome, Email e Telefone.
- **U**pdate: Atualizar informações do contato.
- **D**elete: Excluir contato do banco de dados.

## Pré-requisitos

Antes de começar, certifique-se de ter o seguinte instalado:

- Visual Studio ou outro IDE de sua escolha para desenvolvimento em C#.
- SQL Server para armazenar os dados.
- Um navegador web.

## Configuração

1. Clone este repositório para sua máquina local:

   ```bash
   git clone https://github.com/eduardoaalmeidaa/MVCCRUD.git

## Abra o projeto no Visual Studio.

- Configure a conexão com o banco de dados SQL Server em appsettings.json:

json
Copy code
"ConnectionStrings": {
    "DefaultConnection": "-string-de-conexao"
}

 - Execute o comando de migração para criar o banco de dados:

Copy code
dotnet ef database update

- Inicie o servidor de desenvolvimento:

Copy code
dotnet run
