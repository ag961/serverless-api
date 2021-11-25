# serverless-api

**in-progress**

## Feature Tasks & Requirements

Create a single resource REST API using a domain model of your choosing, constructed using AWS Cloud Services

- Database: DynamoDB
  - 1 Table required
  - Routing: API Gateway
  - POST
  - /people - Given a JSON body, inserts a record into the database
  - returns an object representing one record, by its id (##)
  - GET
    - /people - returns an array of objects representing the records in the database
    - /people/## - returns an object representing one record, by its id (##)
  - PUT
  - /people/## - Given a JSON body and an ID (##), updates a record in the database
  - returns an object representing one record, by its id (##)
  - DELETE
  - /people/## - Given an id (##) removes the matching record from the database
  - returns an empty object
- CRUD Operation Handlers: Lambda Functions

## Author

Ayrat Gimranov

## Collaborators

Mark Thanadabouth - setting up ithub repo, AWS environment (API, lambda function, Dynamo) and post request
Tom McGuire - giodance through GitHub actions
Alex White(instructor) - starter code



## Documentation

Provide a UML diagram showcasing the architecture of your API

Document the data and program flow for your API, including the mapping of Routes and Functions, as well as the flow of data.

### UML

What is the root URL to your API?
What are the routes?

- GET
- POST
- PUT
- DELETE

What inputs do they require?

What output do they return?

