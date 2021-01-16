# Your-First-Node-REST-API

it needs a .env file to hold all values like URLs, User access to DB and so on

DATABASE_URL=mongodb://localhost/subscribers

## for testing the restapi use a plugin for visual studio code called "rest api"

it allows you to create a plain text file  .rest containing all the requests

e.G.:
_a blank line is needed between Request and data to be send_

-------begin file content------------
```
GET http://localhost:3000/subscribers

###

GET http://localhost:3000/subscribers/15

###

POST GET http://localhost:3000
Content-Type: application/json

{
  "name": "Joe Doe",
  "subscribedToChannel": "awesome channel"
}
```
-------end file content--------------
