# API Deployment
This section is dedicated to defining API deployment collections that can be used across the organization. The goal of this work is to not specifically tell developers how they should be deploying their APIs, but to push them to make sure their API deployments are as mapped out, repeatable, and reusable for other APIs as possible.

## Current API Blueprints
These are the API collections that we currently have established as part of the Union Fashion API life cycle. Helping provide some common patterns for how APIs get delivered across the organization.

|Collection   | Docs  | Run in Postman  |
|---|---|---|
| Deploy API (AWS API, DYN)  | [Docs](https://documenter.getpostman.com/view/10394726/Szf6XTqp?version=latest)  | [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/2b87de2d53001e658663) |
| Deploy API (AWS API, LAM, RDS)   | ([Docs](https://documenter.getpostman.com/view/10394726/Szf6X8Wd?version=latest))  | [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/f17f39e70ec132c85950) |

You can find these collections listed as part of [the operations repo](https://github.com/union-fashion/operations), and follow [any issues there as well using the deploy label](https://github.com/union-fashion/operations/issues?q=is%3Aissue+is%3Aopen+label%3Adeployment).

## Future API Blueprints
There is more work occurring around API deployment collections. Right now it is focused on Amazon primarily, but by June we will be developing Azure and Google base collections as well for simple API deployment.

### Amazon

- API Gateway (Management) + Lambda (Compute) DynamoDB (NoSQL Data Store)
- API Gateway (Management) + Lambda (Compute) MySQL (SQLData Store)
- API Gateway (Management) + Lambda (Compute) PosgreSQL (SQLData Store)
- API Gateway (Management)  + Lambda (Compute) + SQL Server (SQLData Store)

### Azure

- API Management (Management) + Cosmos DB (NoSQL Data Store)
- API Management (Management) + Function (Compute) + Cosmos DB (NoSQL Data Store)
- API Management (Management) + Function (Compute) + SQL Server (SQL Data Store)
- API Management (Management) + Function (Compute) + MySQL (SQL Data Store)
- API Management (Management) + Function (Compute) + PosgreSQL (SQL Data Store)

### Google

- Apigee API Management (Management) + Cloud Functions (Compute) + Cloud DataStore (NoSQL Data Store)
- Apigee API Management (Management) + Cloud Functions (Compute) + Cloud SQL MySQL (SQL Data Store)
- Apigee API Management (Management) + Cloud Functions (Compute) + Cloud SQL PosgreSQL (SQL Data Store)
- Apigee API Management (Management) + Cloud Functions (Compute) + Cloud SQL SQL Server (SQL Data Store)

### Heroku

- Dynos (Compute) + PostgreSQL (SQL Data Store)

## Philosphy
Our API deployment philosophy at Union Fashion centers around begin platform and technology agnostic. You can use ANY deployment pattern you'd like, but you have to be able to document that process, make it something that is repeatable and reusable by others, while following the wider API life cycle and governance requirements that are already in place.
