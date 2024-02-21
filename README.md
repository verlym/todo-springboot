# todo-springboot

##Spring boot Day 2 Use Case Study.


#API Contract

Creating a new Todo

Make a POST request with the JSON body as shown below to http://127.0.0.1:8080/api/v1/todo.

{
    "title": "Go to market",
    "description": "Buy eggs from market",
    "todoStatus": "NOT_COMPLETED"
}

Getting the list of todos

Make a GET request to http://127.0.0.1:8080/api/v1/todo to get all the todos.

Getting a Todo by ID

Make a GET request to http://127.0.0.1:8080/api/v1/todo/2 specifying the ID of the Todo at the end of the URL, in our case ID is 2.

Updating a Todo

Make a PUT request to http://127.0.0.1:8080/api/v1/todo/2 adding the ID of the todo to update in the URL, in our case the ID is 2 and a JSON body with the fields to update.

{
    "title": "Market",
    "description": "Buy eggs from supermarket",
    "todoStatus": "NOT_COMPLETED"
}

Deleting a Todo

Make a DELETE request to http://127.0.0.1:8080/api/v1/todo/2 adding to the end of the URL the ID of the todo to delete, in our case the ID is 2.
