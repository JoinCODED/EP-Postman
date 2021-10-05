You can send path parameters with your requests using the URL field and the **Params** tab.

To send a path parameter, enter the parameter name into the URL field, after a colon, for example **:id**. When you enter a path parameter, Postman will populate it in the **Params** tab, where you can also edit it.

First let's do a regular **Get** request to this endpoint to get a list of all users https://reqres.in/api/users

To fetch a single user by his id lets add an id **Param** to our url in Postman
https://reqres.in/api/users/:id

When you enter a path parameter, Postman will populate it in the **Params** tab, where you can also edit it.

So let's try to enter the value of 1 and send our request.

![Postman](https://i.ibb.co/nPP00RG/app-overview-v8.png)
