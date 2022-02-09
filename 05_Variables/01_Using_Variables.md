Variables enable you to store and reuse values in your requests and scripts. By storing a value in a variable, you can reference it throughout your collections, environments, and requests. If you need to update the value, you only have to change it in one place. Using variables increases your ability to work efficiently and minimizes the likelihood of error.

Lets take one of our requests that needs a url and an authorization token

1. Select your api baseUrl and a tooltip will appear.
2. Click set as variable

![postman](https://i.ibb.co/5sttpjz/1.png)

1. Click on set as a new variable

![postman](https://i.ibb.co/d7GFCnY/2.png)

1. Name your variable as `baseUrl`
2. The value will be the text you selected in the first step, but you can also modify it here
3. Select a scope for your variable, it may be with a global scope and you can use it through all you api calls, or it may be limitid within a collection
4. Click set as variable.

![postman](https://i.ibb.co/7vz7YTQ/3.png)

5. Once you set it as a variable you will see the change instantly within your url and you can start using this variable in any other request
6. Try to make a variable for your bearer token, name it `Auth`.

![postman](https://i.ibb.co/6WfC3fW/4.png)
