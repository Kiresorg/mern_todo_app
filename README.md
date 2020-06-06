#Todo app written in MERN stack

## Two projects: front end and back end
### Starting front end project: 
```
cd mern-todo-app 
nodemon server
```
The nodemon server will rebuild and restart the node server on code changes

### Starting back end project
> Requires MongoDB. Written for local installation; need to change connection string URL in backend/server.js if you use an online database
```
cd backend
mongo
use todos
```
And in another terminal, start the server for the backend project like this:
```
cd backend
mongod server
```
