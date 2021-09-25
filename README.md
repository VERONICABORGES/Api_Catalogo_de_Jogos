### Api_Catálogo_de_Jogos
### Foi Criada uma API de catálogo de jogos, usando boas práticas de arquitetura com .NET
#### Esse foi um Projeto prático, realizado no Bootcamp da Digital Innovation One.
#### Tecnologias utilizada : AspNet core API, Swagger, SqlServer
 
#### Implementação de Features Novas, melhorias no projeto inicial: 
- Criei mensagens personalizada no retorno do Status Code (Post e Put)
- Adicionei mais de uma pagina no indice de paginação

#### Rodando esse projeto: 
O projeto utiliza o banco SQL Server, Você também poderá fazer uso em Memoria, para isso deverá Ir na classe startup e comentar a linha da conexão SQL (services.AddScoped<IJogoRepository, JogoSqlServerRepository) e descomentar a linha na classe startup (services.AddScoped<IJogoRepository, JogoRepository) e executar o projeto.

