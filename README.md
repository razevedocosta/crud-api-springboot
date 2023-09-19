# crud-api-springboot

- Desenvolvimento de uma API Rest
- CRUD (Create, Read, Update e Delete)
- Validações
- Paginação e ordenação

Em caso de erro na migration, parar a aplicação e executar os seguintes comandos:
- mysql -u root -p
- use vollmed_api;
- delete from flyway_schema_history where success = 0;
- drop database vollmed_api;
- create database vollmed_api;
