# user-management-api
Backend REST API for managing users using Spring Boot, Java 17, and MySQL, featuring full CRUD functionality.

# User Management API

Backend REST API for managing users using Spring Boot, Java 17, and MySQL.

## 🚀 Features

* Create User
* Get All Users
* Update User
* Delete User

## 🛠️ Tech Stack

* Java 17
* Spring Boot
* Spring Data JPA
* MySQL
* Maven

## 📦 API Endpoints

### GET Users

GET /users

### POST User

POST /users

### PUT User

PUT /users/{id}

### DELETE User

DELETE /users/{id}

## ⚙️ Setup

1. Create database:

```
CREATE DATABASE db_user;
```

2. Configure application.properties

3. Run:

```
mvn spring-boot:run
```
📡 Testing API

You can test this API using:

==== 🧪 Postman ====

Use Postman to send HTTP requests to the API:

- GET all users:
GET http://localhost:8080/users
- Create user:
POST http://localhost:8080/users

- Body (JSON):

{
  "name": "test",
  "email": "test@email.com"
}

====🗄️ DBeaver ====

You can also check the database using DBeaver:

1. Connect to MySQL (localhost:3306)
2. Open database:
db_user
3. Check table:
user
