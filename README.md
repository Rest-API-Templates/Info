# Info
This is for getting information about this project

Rules for Contributing in this project:
- All Repository must have all dependancy metioned with all of its versions.
- All Repository must contain README file and all instructions for running particular application.
- All Repository must have Some kind of documentation of API's like Swagger
- All Repository must follow same schmea for db and same endpoints.

```yaml
DB model:
- Todo
  - id: Integer [Auto Generated]
  - title: String
  - status: String
  - lastUpdate: String [Auto Generated]
```
```yaml
Endpoints:
  - GET /v1/todo (GET ALL Todo's)
  - GET /v1/todo/{id} (GET A Single Todo)
  - PUT /v1/todo (Update Exisitng Todo)
  - DELETE /v1/todo/{id} (Delete Todo)
```

> Use sqlite as db and give proper instructions to run the Application.
