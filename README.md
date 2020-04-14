# The Petful Server 

Live: https://the-petful-app.now.sh/
Client Repo: https://github.com/thinkful-ei-leopard/Petful-Client-Ron-Paul
API Repo: https://github.com/thinkful-ei-leopard/Petful-Server-Ron-Paul

## Consuming API endpoints
### /api/people
* GET 
    * returns a JSON object with key "allPeople":['person name', 'person2 name', 'etc']

* POST
    * requires a string "name" to be sent in the POST request
returns back with the name of that you sent in.

### /api/pets
* GET
    * Returns a JSON list of all pets. There are two keys "dogs" and "cats". The key's value is an array of objects - each object has all of the details of one pet.

* DELETE 
    * 'type' - the type of animal to delete. Valid types are 'cats' or 'dogs', both are strings. We will dequeue the first dog or cat and dequeue the person who adopted the animal
 
    * 'both' - boolean, if set to 'true' we will dequeue the first dog AND cat and dequeue the person who adopted the animal

## Technology Used
* React
* Node
* Express
* PostgreSQL

## Authors
[Ron Martin](https://github.com/Izzle) and [Paul Baisley](https://github.com/wavinginspace)
