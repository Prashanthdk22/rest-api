# rest-api
This project is a simple User CRUD API built using Flask.
It stores user details like id, name, and email in a Python dictionary (no database).

The API supports:

GET /users → returns all users

GET /users/<id> → returns one user

POST /users → creates a new user (name required)

PUT /users/<id> → updates user details

DELETE /users/<id> → deletes a user

Each new user gets an auto-generated id.
Data is stored only in memory, so it resets when the server restarts.
This API helps understand how backend routes, JSON data, and CRUD operations work.
