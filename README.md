# DocNexusApi
 RESTful API that allows users to create, read, update, and delete blog posts
 
In this code:

We use Express.js to create the RESTful API.
We handle user registration, login, and authentication using JWT and bcrypt for password hashing.
Blog post data is stored in memory for simplicity (in a real app, you would use a database).
The "authenticateToken" middleware ensures that protected routes are only accessible to authenticated users.
