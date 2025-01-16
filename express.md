# What is Express JS 
## Library vs framework 
## Features of Express (7)
Routing , middleware , templating , error handling , security features , faster development , compatibility with databases 
## Create  a Server and set basic routes 
### app.all 
# Routing in Express js 
## Dynamic Routing 
### Query params vs path params 
### Router chaining using app.route()
## Router Chaining 
## Response Methods 
send , json , end , status , sendFile , redirect 
## Routers 
### Router Creation 
### Benefits of using Router 
modularity , seperation of concerns , reusability , specific middlewares 
# Middlewares 
## Types of middlewares
### App level 
### Router level 
### Builtin 
express.json, express.urlencoded , express.static 
### Third Party 
cors , cookie-parser , express-session , morgan , helmet , compression 
### Custom Module 
## App.use vs App.set 
app.set - views , view engine , appName 
## MiddleWare chaining 
# Session and Cookies 
## Key concepts of cookies 
stateless nature of http , session storage, session middleware , 
## Express session configuration options 
secret , resave , saveunintialised , cookie 
## Cookie 
### maxage vs expires 
### secure , httponly 
## Authentication vs authorisation 
## Tokens (jwt)
### cookies vs tokens 
state, storage , sending , security risks 
## Cache-control 
max-age , no-cache , no-store , public private , immutable 
# Sever communication in Express
## Setting headers 
res.set(), res.header 
setting - content type , content length , cache-control , cookie-set , access control , expires , 
## Setting status codes 
res.status, res.sendStatus
## content negotiation
## Rate limiting 
# Api Development 
## Restful API 
### Features 
statelessness , resource based , 
# Error handling 
## methods to handle errors 
builtin , async handling , custom middlewares
# File management and validation 
## upload files using multer 
## download files using res.download 
## validation using express validator 

# Security and Perfomance 
## Common Security Vulnarabilities 
RCE, XSS , Injection attacks , DOS DDOS , IDOR , Dependency vulnarabilities 
csp ,
# Extras
## Some Protocols 
## MVC 
## CronJob 
## Microservices 
## Web Sockets 
### Benefits usecases 
## Local vs session storage 
## Environment variables 
## Proxy and Reverse Proxy 
## Optimize perfomace 
use compression , clustering , async programming , optimize database queries , implement caching , optimize middleware 
## Abort controller 
## Async hook 
## content secure policy 





socket
interceptors 

