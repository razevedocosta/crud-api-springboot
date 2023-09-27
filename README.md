# crud-api-springboot

- API Rest com ações de CRUD (Create, Read, Update e Delete) para as classes Médico, Paciente e Consulta
- Validações utilizando Bean Validation
- Uso do Flyway como ferramenta de Migrations para o banco de dados MySQL
- Paginação e ordenação dos resultados


Em caso de erro na migration, será preciso parar a aplicação e executar os seguintes comandos:
- mysql -u root -p
- use vollmed_api;
- delete from flyway_schema_history where success = 0;
- drop database vollmed_api;
- create database vollmed_api;

Este projeto foi criado com base no curso de Spring Boot 3 da Alura o/