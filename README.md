Criando API Rest em Java, utilizando:
- Ambiente Docker
- PostgreSQL
- JWT
- Spring Boot
- Spring Jdbc 

O projeto foi criado afim de estudos, seguindo como passos:
- Configuração do projeto e setando informações do PgSQL
- Informações do usuário persistente no registro
- Login e senha de hash
- Autenticação JWT
- Adicionando novas categorias
- Categoria - Funcionalidade de localização e atualização
- Adicionando transações de categoria
- Transação - Localizar e atualizar
- Excluindo - Categoria e transações
- CORS e teste do cliente da Web

Por favor, insira suas credencias de banco de dados e utilize a configuração de virtualização de ambiente em nuvem de acordo com seu projeto, de acordo com:
- src/main/resources/application.properties de acordo:
******************************************************
- spring.datasource.url=jdbc:postgresql://localhost:5432/expensetrackerdb
- spring.datasource.username=expensetracker
- spring.datasource.password=password
