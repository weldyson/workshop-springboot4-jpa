<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Web Services Project with Spring Boot and JPA / Hibernate</title>
</head>
<body>

<h1>Web Services Project with Spring Boot and JPA / Hibernate</h1>

<p>This project aims to build a web application using the Spring Boot framework with JPA/Hibernate. The main focus is to create a robust web service, following the best practices of Java development.</p>

<h2>Objectives</h2>
<ul>
    <li><strong>Create a Spring Boot Java project:</strong> Start a Spring Boot project with the basic structure needed for a web service.</li>
    <li><strong>Implement domain model:</strong> Create the entities of the project, defining the data model that will be persisted in the database.</li>
    <li><strong>Structure logical layers:</strong> Separate responsibilities into distinct layers:
        <ul>
            <li><strong>Resource:</strong> Responsible for communication with REST interfaces.</li>
            <li><strong>Service:</strong> Contains the business logic of the application.</li>
            <li><strong>Repository:</strong> Responsible for communication with the database.</li>
        </ul>
    </li>
    <li><strong>Configure test database (H2):</strong> Set up and use the in-memory H2 database for testing and local development.</li>
    <li><strong>Populate the database:</strong> Insert initial data for testing purposes.</li>
    <li><strong>CRUD - Create, Retrieve, Update, Delete:</strong> Implement basic data persistence operations.</li>
    <li><strong>Exception handling:</strong> Manage and return appropriate responses for errors and exceptions.</li>
</ul>

<h2>Technologies Used</h2>
<ul>
    <li><strong>Java 21:</strong> Programming language.</li>
    <li><strong>Spring Boot 4:</strong> Framework for creating Spring applications.</li>
    <li><strong>JPA / Hibernate:</strong> Object-relational mapping (ORM) frameworks for data persistence.</li>
    <li><strong>H2 Database:</strong> In-memory database for testing.</li>
    <li><strong>Maven:</strong> Dependency management tool.</li>
</ul>

<h2>How to Run</h2>
<ol>
    <li>Clone the repository:
        <pre><code>git clone https://github.com/your-username/repository-name.git</code></pre>
    </li>
    <li>Navigate to the project directory:
        <pre><code>cd repository-name</code></pre>
    </li>
    <li>Run the project:
        <pre><code>mvn spring-boot:run</code></pre>
    </li>
    <li>Access the application at: <a href="http://localhost:8080" target="_blank">http://localhost:8080</a></li>
</ol>

<h2>Endpoints</h2>
<ul>
    <li><strong>GET /entities:</strong> Retrieves all entities.</li>
    <li><strong>POST /entities:</strong> Creates a new entity.</li>
    <li><strong>GET /entities/{id}:</strong> Retrieves a specific entity by ID.</li>
    <li><strong>PUT /entities/{id}:</strong> Updates an existing entity.</li>
    <li><strong>DELETE /entities/{id}:</strong> Deletes a specific entity.</li>
</ul>

<h2>Contributing</h2>
<p>Contributions are welcome! Feel free to open issues and pull requests.</p>

<h2>License</h2>
<p>This project is licensed under the MIT License. See the <strong>LICENSE</strong> file for more details.</p>

</body>
</html>
