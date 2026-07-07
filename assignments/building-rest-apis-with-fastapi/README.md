# 📘 Assignment: Building REST APIs with FastAPI

## 🎯 Objective

Learn how to create a small REST API using FastAPI by defining routes, handling request data, and returning JSON responses.

## 📝 Tasks

### 🛠️ Create a Basic API

#### Description
Build a simple FastAPI application with a home endpoint that returns a welcome message.

#### Requirements
Completed program should:

- Create a FastAPI app instance.
- Define a GET route at `/`.
- Return a JSON response with a friendly message.
- Run the app locally and confirm that the endpoint responds.

### 🛠️ Add a Resource Endpoint

#### Description
Extend the API with a route that returns information about a specific item.

#### Requirements
Completed program should:

- Define a GET endpoint such as `/items/{item_id}`.
- Accept a path parameter and include it in the response.
- Return JSON data for at least two example items.
- Demonstrate the response format in a browser or API client.

### 🛠️ Handle POST Requests

#### Description
Add support for creating new items through a POST request.

#### Requirements
Completed program should:

- Define a POST endpoint that accepts JSON input.
- Validate that required fields are present.
- Return the created item with a success message.
- Include an example request body and response.
