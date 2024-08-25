<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Projeto Web Services com Spring Boot e JPA / Hibernate</title>
</head>
<body>

<h1>Projeto Web Services com Spring Boot e JPA / Hibernate</h1>

<p>Este projeto tem como objetivo a construção de uma aplicação web utilizando o framework Spring Boot com JPA/Hibernate. O foco principal é a criação de um serviço web robusto, seguindo as melhores práticas do desenvolvimento Java.</p>

<h2>Objetivos</h2>
<ul>
    <li><strong>Criar projeto Spring Boot Java:</strong> Iniciar um projeto Spring Boot com a estrutura básica necessária para um serviço web.</li>
    <li><strong>Implementar modelo de domínio:</strong> Criar as entidades do projeto, definindo o modelo de dados que será persistido no banco.</li>
    <li><strong>Estruturar camadas lógicas:</strong> Separar as responsabilidades em camadas distintas:
        <ul>
            <li><strong>Resource:</strong> Responsável pela comunicação com as interfaces REST.</li>
            <li><strong>Service:</strong> Contém as regras de negócio da aplicação.</li>
            <li><strong>Repository:</strong> Responsável pela comunicação com o banco de dados.</li>
        </ul>
    </li>
    <li><strong>Configurar banco de dados de teste (H2):</strong> Configurar e utilizar o banco de dados em memória H2 para testes e desenvolvimento local.</li>
    <li><strong>Povoar o banco de dados:</strong> Inserir dados iniciais para a realização de testes.</li>
    <li><strong>CRUD - Create, Retrieve, Update, Delete:</strong> Implementar as operações básicas de persistência de dados.</li>
    <li><strong>Tratamento de exceções:</strong> Gerenciar e retornar respostas adequadas para erros e exceções.</li>
</ul>

<h2>Tecnologias Utilizadas</h2>
<ul>
    <li><strong>Java 21:</strong> Linguagem de programação.</li>
    <li><strong>Spring Boot 4:</strong> Framework para criação de aplicações Spring.</li>
    <li><strong>JPA / Hibernate:</strong> Frameworks de mapeamento objeto-relacional (ORM) para persistência de dados.</li>
    <li><strong>H2 Database:</strong> Banco de dados em memória para testes.</li>
    <li><strong>Maven:</strong> Gerenciador de dependências.</li>
</ul>

<h2>Como Executar</h2>
<ol>
    <li>Clone o repositório:
        <pre><code>git clone https://github.com/seu-usuario/nome-do-repositorio.git</code></pre>
    </li>
    <li>Navegue até o diretório do projeto:
        <pre><code>cd nome-do-repositorio</code></pre>
    </li>
    <li>Execute o projeto:
        <pre><code>mvn spring-boot:run</code></pre>
    </li>
    <li>Acesse a aplicação em: <a href="http://localhost:8080" target="_blank">http://localhost:8080</a></li>
</ol>

<h2>Endpoints</h2>
<ul>
    <li><strong>GET /entities:</strong> Retorna todas as entidades.</li>
    <li><strong>POST /entities:</strong> Cria uma nova entidade.</li>
    <li><strong>GET /entities/{id}:</strong> Retorna uma entidade específica por ID.</li>
    <li><strong>PUT /entities/{id}:</strong> Atualiza uma entidade existente.</li>
    <li><strong>DELETE /entities/{id}:</strong> Deleta uma entidade específica.</li>
</ul>

<h2>Contribuição</h2>
<p>Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.</p>

<h2>Licença</h2>
<p>Este projeto está licenciado sob a licença MIT. Consulte o arquivo <strong>LICENSE</strong> para obter mais informações.</p>

</body>
</html>
