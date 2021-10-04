# Bearer token.

Bearer tokens allow requests to authenticate using an access key, such as a JSON Web Token (JWT). The token is a text string, included in the request header.

1. Go to the request **Authorization** tab.
2. Select **Bearer Token** from the Type dropdown list.
3. In the Token field, enter your **token** value

<img src="https://i.ibb.co/VSXKJN9/app-overview-v8.png" alt="app-overview-v8" border="0">

Postman will append the token value to the text "Bearer " in the required format to the request Authorization header as follows:
`Bearer <Your token key>`
