# Overview

In this project, I used  APIs, documentation, and testing to implement a Vehicles API that serves as an endpoint to track vehicle inventory.
While the primary Vehicles API will perform CRUD operations (Create, Read, Update and Delete) related to vehicle details like make, model, color, etc., 
it will need to consume data from other APIs as well regarding location and pricing data. I implemented a RESTful API for the Vehicles API,
and it uses Pricing Service API as a microservice.

We have an application that can communicate with other services and be able to be viewed and used through Swagger-based
API documentation.

We can find details and instructions in readme file of respective modules.
- [Vehicles API](vehicles-api/README.md)
- [Pricing Service](pricing-service/README.md)
- [Boogle Maps](boogle-maps/README.md)

## Dependencies

The project requires the use of Maven and Spring Boot, along with Java v11.