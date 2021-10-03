# Setting request URLs.

Each request you send in Postman requires a URL representing the API endpoint you are working with. Each operation you can perform using an API is typically associated with an endpoint. Each endpoint in an API is available at a particular URL—this is what you enter into Postman to access the API.

If you're building an API, the URL will typically be the base location plus path. For example, in the request https://postman-api-learner.glitch.me/info, https://postman-api-learner.glitch.me is the base URL, and /info is the endpoint path.

## Selecting request methods

By default Postman will select the **GET** method for new request. **GET** methods are usually for retrieving data from an API. You can use a variety of other methods to send data to your APIs, including the following most common options:

**POST**: add new data
**PUT**: replace existing data
**DELETE**: delete existing data

<img src="https://assets.postman.com/postman-docs/request-methods.jpg"/>

For example, if you're working with an API for a To Do list application, you might use a **GET** method to retrieve the current list of tasks, a **POST** method to create a new task, and a **PUT** method to edit an existing task.
