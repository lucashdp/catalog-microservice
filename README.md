# catalog-microservice
Catalog Microservice is the CRUD API for products. The reason for this API is a postgraduate work in Software Architecture at PUC MINAS, in the field of Cloud Communication Architecture.

## Deploy
**[This API was deployed at https://catalog-microservice-lucashdp.herokuapp.com/](https://catalog-microservice-lucashdp.herokuapp.com/)**

## Database
This API connect with a mongoDB. Any log will be registered with this database.
Your connection string is: <code>mongodb://iplaycore:t0k3n@iplaycore-shard-00-00-m6ecr.mongodb.net:27017,iplaycore-shard-00-01-m6ecr.mongodb.net:27017,iplaycore-shard-00-02-m6ecr.mongodb.net:27017/catalog?ssl=true&replicaSet=iplaycore-shard-0&authSource=admin</code>

## Endpoints

#### Books Resources

##### GET REGION
- **[<code>GET</code> v1/public/books](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/GET_BOOKS.md)**
- **[<code>GET</code> v1/public/books/:bookId](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/GET_BOOKS_BY_ID.md)**
- **[<code>GET</code> v1/public/books/:bookId/comments](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/GET_BOOKS_COMMENTS.md)**
- **[<code>GET</code> v1/public/books/:bookId/scores](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/GET_BOOKS_SCORES.md)**

##### PUT REGION
- **[<code>PUT</code> v1/public/books/:bookId](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/PUT_BOOKS.md)**
- **[<code>PUT</code> v1/public/books/:bookId/comments/:commentId](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/PUT_COMMENTS.md)**
- **[<code>PUT</code> v1/public/books/:bookId/scores/:scoreId](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/PUT_SCORES.md)**

##### POST REGION
- **[<code>POST</code> v1/public/books](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/POST_BOOKS.md)**
- **[<code>POST</code> v1/public/books/:bookId/comments](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/POST_COMMENTS.md)**
- **[<code>POST</code> v1/public/books/:bookId/scores](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/POST_SCORES.md)**

##### DELETE REGION
- **[<code>DELETE</code> v1/public/books/:bookId](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/DELETE_BOOKS.md)**
- **[<code>DELETE</code> v1/public/books/:bookId/comments/:commentId](https://github.com/lucashdp/catalog-microservice/blob/master/api-documentation/books/DELETE_COMMENTS.md)**

## Pre-Requisites

- NodeJS is a pre requisite. You will use the Node Package Manager (npm).

## Install and Run this app

- Clone the project:
    git clone https://github.com/lucashdp/catalog-microservice

- Execute the command line (install dependences):
    npm install

- Run the command line (run the app):
    npm start
