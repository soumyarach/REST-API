# REST-API
# What it built?

The code builds a simple RESTful API using Flask, a popular Python web framework. The API manages a list of users, allowing you to perform CRUD (Create, Read, Update, Delete) operations on the users.

# Why it built?

The API is built to demonstrate a basic example of a RESTful API that can be used to manage a list of users. It provides a simple way to interact with the users data, making it easy to test and understand the API's functionality.

# How it works?

Here's a high-level overview of how the API works:

1. In-memory storage: The API uses an in-memory list to store the users. This means that the data is stored in the RAM and will be lost when the application is restarted.
2. Flask routes: The API defines several Flask routes that correspond to different HTTP methods and URLs. Each route is associated with a specific function that handles the request and returns a response.
3. Request handling: When a request is made to the API, Flask calls the corresponding function to handle the request. The function processes the request data, interacts with the users list, and returns a response.
4. JSON responses: The API returns JSON responses to the client, making it easy to parse and understand the data.

API Endpoints:

The API has the following endpoints:

- GET /: A welcome page with a link to the /users endpoint.
- GET /users: Returns a list of all users.
- GET /users/: Returns a single user by ID. If the user is not found, it returns a 404 error.
- POST /users: Creates a new user. The request body should contain the user's name and age.
- PUT /users/: Updates an existing user. The request body can contain the user's new name and/or age.
- DELETE /users/: Deletes a user by ID.

Example Use Cases:

- You can use a tool like Postman or Curl to test the API endpoints.
- You can use the API to build a simple user management system.
- You can extend the API to include additional features, such as authentication and authorization.

Overall, the API provides a basic example of how to build a RESTful API using Flask, and it can be used as a starting point for more complex projects.
