# Overview
Create a network-connected TODO app.

# Features
* Diplay title and completed status of each todo
* Allow user to toggle completed status and update on the backend
* Allow user to search for a specific todo based on title - this should be an offline search. Update the UI with the filtered results.

# API routes
* GET https://jsonplaceholder.typicode.com/todos
* PATCH https://jsonplaceholder.typicode.com/todos

# Requirements
* Fill in functions in `util/api`, then call them when using the API routes. Each should return a promise and call fetch. E.g.
```
api.getTodos(url)
.then(todos => {

})
```
* Use `reduce` to update state when the user toggles `completed` on each todo

# Answer the following:
* If you were responsible for setting up the `Todos` database in PostgreSQL, what might the table structure look like?
* If you had to set up user authentication for this app, how might you go about doing so with PostGres? How would that change the structure of of your db?
* Write a sample query to select all todo titles for a user with ID of 1.
