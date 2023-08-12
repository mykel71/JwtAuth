# JwtAuth

.Net Core JWT Authentication first attempt which explains how to implement JWT Token Authentication . 
I have used ASP.Net Core 6 JWT implementation in this mini demo project.

Authentication is the process that helps identify who is the users. On the other hand, authorization is the process of determining what a user can do. 
For authorization to work, the user will be authenticated first. We need the user's identity to identify the role of a user and act accordingly.

JWT, or JSON Web Token, is an open standard used to share security information between two parties - a client and a server. 
Each JWT contains encoded JSON objects, including a set of claims. JWTs are signed using a cryptographic algorithm to ensure that the claims cannot be altered after the token is issued.

A common way to use JWT is as OAuth bearer tokens. The authentication method creates a JWT at the request of a client and signs it so that it cannot be altered by any other party. 
The client will then send this JWT with its request to a REST API. The REST API will verify that the JWT's signature matches its payload and header to determine that the JWT is valid. 
When the REST API has verified the JWT, it can use the claims to either grant or deny the client's request.
