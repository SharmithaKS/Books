# Project Name

This project is about CRUD operation in using Node js and MongoDb

## Table of Contents

- [API Endpoints](#api-endpoints)
- [Usage](#usage)
- [Setup](#setup)
- [Decisions and Assumptions](#decisions-and-assumptions)

## API Endpoints

### Fetch All Records

- **Endpoint:** `GET /books`
- **Description:** Retrieve all records from the database.
- **Usage:** Make a `GET` request to `http://your-server-url/books` using a tool like Postman.

### Insert a Record

- **Endpoint:** `POST /books`
- **Description:** Insert a new record into the database.
- **Usage:** Make a `POST` request to `http://your-server-url/books` with the data you want to insert in the request body (in JSON format).

### Update a Record

- **Endpoint:** `PUT /books/:id`
- **Description:** Update a specific record by its ID.
- **Usage:** Make a `PUT` request to `http://your-server-url/books/:id` with the updated data in the request body (in JSON format).

### Delete a Record

- **Endpoint:** `DELETE /books/:id`
- **Description:** Delete a specific record by its ID.
- **Usage:** Make a `DELETE` request to `http://your-server-url/books/:id`.

### Fetch Record by ID

- **Endpoint:** `GET /books/:id`
- **Description:** Fetch a specific record by its ID.
- **Usage:** Make a `GET` request to `http://your-server-url/books/:id`.



## Setup

1. Clone the repository:

   ```sh
   git clone https://github.com/your-username/your-repo.git

2.Navigate to the project directory . Command : cd your-repo

3.Install the dependency . Command : npm install

4.Start the server . Command :node index.js


Best Practice : For real time application most of the time we need  use only "POST" method to do all actions like insert , update , delete , fetch .
Because in POST method only we can able to pass the parameters in body.

