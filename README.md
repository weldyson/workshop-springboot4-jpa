Projeto Web Services com Spring Boot e JPA / Hibernate
Este projeto tem como objetivo a construção de uma aplicação web utilizando o framework Spring Boot com JPA/Hibernate. O foco principal é a criação de um serviço web robusto, seguindo as melhores práticas do desenvolvimento Java.

Objetivos
Criar projeto Spring Boot Java: Iniciar um projeto Spring Boot com a estrutura básica necessária para um serviço web.
Implementar modelo de domínio: Criar as entidades do projeto, definindo o modelo de dados que será persistido no banco.
Estruturar camadas lógicas: Separar as responsabilidades em camadas distintas:
Resource: Responsável pela comunicação com as interfaces REST.
Service: Contém as regras de negócio da aplicação.
Repository: Responsável pela comunicação com o banco de dados.
Configurar banco de dados de teste (H2): Configurar e utilizar o banco de dados em memória H2 para testes e desenvolvimento local.
Povoar o banco de dados: Inserir dados iniciais para a realização de testes.
CRUD - Create, Retrieve, Update, Delete: Implementar as operações básicas de persistência de dados.
Tratamento de exceções: Gerenciar e retornar respostas adequadas para erros e exceções.
Tecnologias Utilizadas
Java 21: Linguagem de programação.
Spring Boot 4: Framework para criação de aplicações Spring.
JPA / Hibernate: Frameworks de mapeamento objeto-relacional (ORM) para persistência de dados.
H2 Database: Banco de dados em memória para testes.
Maven: Gerenciador de dependências.
