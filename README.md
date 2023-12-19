 ## Authentication | Part 2
- Introduction to Authentication
- Authentication Mechanisms
  - Token Authentication
    - JSON Web Token (JWT)
- JWT Methods
  - jwt.sign(payload,"secretCode",callback_optional) - it generates a JWTtoken when user login - use at login request API
  - jwt.verify(jwt,"secretCode",async(error,payload)=>{...}) - use at Apis Get,post,put etc...
