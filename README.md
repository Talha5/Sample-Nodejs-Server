# Prerequisites:
1. node and npm latest
2. Postgres

# Installation:
1. clone the project and cd into the project
2. run `npm install`
3. create database with name: `api` and also create a table inside this database named users with columns `name, email`.
4. run server by `node index.js`
5. Hit these APIs:

URLS Exposed:

`
GET http:localhost:3000/users
`

`
POST http:localhost:3000/users {name: 'Jonathan', email: 'jona@gmail.com'}
`

or use curl to hit API

`
curl --data "name=Ela22ine&email=elain44e@example.com" http://localhost:3000/users
`