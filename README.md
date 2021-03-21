# Info
This is for getting information about this project

Rules for Contributing in this project:
- All Repository must have all dependancy metioned with all of its versions.
- All Repository must contain README file and all instructions for running particular application.
- All Repository must have Some kind of documentation of API's like Swagger
- All Repository must follow same schmea for db and same endpoints.

DB model:
- Todo
  - Id: Integer 
  - Item: String
  - Status: String
  - TimeStamp: String


Endpoints:
  - GET ALL Todo's
    - GET /v1/todo
  - GET A Single Todo
    - GET /v1/todo/{id}
  - Create New Todo
    - POST /v1/todo
  - Update Exisitng Todo
    - PUT /v1/todo
  - Delete Todo
    - DELETE /v1/todo/{id}


* Use sqlite as db .
* Give proper instructions to run the Application.
