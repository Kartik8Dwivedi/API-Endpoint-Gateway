FRONTEND - MIDDLE-END - BACKEND

- We need an intermediate layer between the client side nad the microservices
- Using this middle end, when client sends request we will be able to make decision that which microservice should acutally responde to this request.
- We can do message validation, response transformation, rate limiting
- We try to prepare an API gateway that acts as this middle end.