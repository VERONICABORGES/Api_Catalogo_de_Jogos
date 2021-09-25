### Api_Catálogo_de_Jogos
### Foi Criada uma API de catálogo de jogos, usando boas práticas de arquitetura com .NET
#### Esse foi um Projeto prático, realizado no Bootcamp da Digital Innovation One.
#### Tecnologias utilizada : AspNet core API, Swagger, SqlServer
 
#### Implementação de Features Novas, melhorias no projeto inicial: 
- Criei mensagem personalizada no retorno do Status Code (Put)
- Adicionei mais de uma pagina para o indice de paginação

#### Executando esse projeto: 
O projeto utiliza banco de dados SQL Server, Você também poderá fazer uso do banco de dados em Memoria, para isso deverá Ir na classe startup e comentar a linha da conexão SQL (services.AddScoped<IJogoRepository, JogoSqlServerRepository) e descomentar a linha na classe startup (services.AddScoped<IJogoRepository, JogoRepository) e executar o projeto.

#### Visualização:
- Dados iniciais do banco - Id foi criado no formato GUID
![image](https://user-images.githubusercontent.com/74335070/134765258-642f784c-947d-45f7-92d6-5e5498e44e19.png)

- Executando o projeto e fazendo consulta pelo Swagger
![image](https://user-images.githubusercontent.com/74335070/134764704-257be301-fe37-423a-984a-1ee076655db8.png)
 
 - Fazendo um Post, Criando um cadastro de jogo no banco de dados
 ![image](https://user-images.githubusercontent.com/74335070/134764844-d61b2564-f33b-43ef-b1e2-66ed56b88b27.png)
 
 - Fazendo Consulta pelo Id do novo jogo cadastrado
 ![image](https://user-images.githubusercontent.com/74335070/134765042-ccafa719-128d-4c95-a08a-bd00bffbdd85.png)
 
 - Atualizando Preço do jogo
 ![image](https://user-images.githubusercontent.com/74335070/134765063-7739f5cb-0b6c-46a2-8d08-63df266778c8.png)
 
 - Consultando a alteração realizada
 ![image](https://user-images.githubusercontent.com/74335070/134765108-b48cc161-6b21-426d-8f93-012f432aac1d.png)
 
 - Verificando no banco SQL, o cadastro do novo jogo
 ![image](https://user-images.githubusercontent.com/74335070/134765215-550671ec-b0f5-42a5-ac18-9eb325437a5a.png)




