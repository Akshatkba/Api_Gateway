FRONT-END - MIDDLE-END - BACK-END

- We need and intermediate layer between the client side and the microservices.
- Using this middle end, when client sends request we will be able to make decision that which microservice should actually respond to this request.
- We can do message Validation, response transformation, rate limiting.
- We try to prepare an API gateway that acts as this middle end.
 
## Packages used:
- Morgan: 
HTTP request logger middleware for node.js
Read more about morgan here: www.npmjs.com/package/morgan

- http-proxy-middleware:
Read more about this package here: www.npmjs.com/package/http-proxy-middleware

- express-rate-limit:
Basic rate-limiting middleware for Express.
Read more about this package here: www.npmjs.com/package/express-rate-limit