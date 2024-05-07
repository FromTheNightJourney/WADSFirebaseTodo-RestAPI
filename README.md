# WebDev_ToDoList_RestAPI

## Overview
This To-Do List has been updated to include a FastAPI RestAPI, alongside previous functionality such as Firebase Authentication and of course, the base to-do web application. Once the files are set up properly with the libraries required installed, the documentation page can be found at localhost:8000/docs.

## Task Management

- `POST /tasks/` - This POST creates a new task item.

- `GET /tasks/` - This retrieves all items.

- `GET /tasks/user/{userId}` - This retrieves all tasks for every user.

- `GET /tasks/{taskId}` - This retrieves a task by its ID.

- `PUT /tasks/{taskId}` - This updates an existing task.
- 
- `DELETE /tasks/{taskId}` - This deletes a task by its ID.
