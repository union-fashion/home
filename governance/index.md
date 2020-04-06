# API Governance
This is the current outline for API governance, providing an overview of how APIs are moved forward.

- [**Documentation**](https://documenter.getpostman.com/view/10394726/SzYUagbA?version=latest)## Definition
### Workspace
Establishing Postman workspaces for each API, making sure each individual API has a place to store it's API contract, and all the derivative collection. Providing a simple place for all stakeholders working on the API to work on and engage around the evolution of each Union Fashion API.

 - Is there a Postman workspace?
 - Is workspace named properly?

### Organization
Ensuring that each API belongs to the Union Fashion GitHub organization so it can be discovered, managed, and given the same resources and support as other APIs. Providing a single organizational umbrella for all Union Fashion APIs to be accessed and made available to other stakeholders, but also allowing the management of each API to be automated and integrated as part of other systems and processes.

 - Is there a GitHub organization?

### Repository
Verifying that each API has its own GitHub repository, providing a single location where all details about an API, allowing each API to be moved forward individually. Storing all details of an API within a single repository which shares a common structure with other APIs being delivered at Union Fashion, while allowing those details to be forked and integrated with wherever they are need as part of the life cycle of each API.

 - Is there a GitHub repository?

### APIs
Establishing the central truth of each API using the Postman API builder. Providing an API contract that can be used by all other areas of operations. Ensuring that there is a versioned, machine readable contract that defines each API, which can be used to generate other artifacts, and drive each stop along the API life cycle. Making sure that each API is consistently moving through a known API life cycle, which is something that enables this governance.

 - Is there a Postman API?
 - Is there an OpenAPI?
 - Is there a valid OpenAPI?

### Collections
This section is about establishing that there are the required derivatives of each API to execute upon other stops along the API life cycle, beginning with the life cycle itself, and then using this governance collection. Leveraging a handful of Postman collections to document, test, and quantify each API. Depending on a handful of collections to act as the gears of the API supply chain, driving different stops along the way.

 - Is there a life cycle collection?
 - Is there a governance collection?
 - Is there a documentation collection?
 - Is there a contract collection?
 - Is there a performance collection?
 - Is there a security collection?

### Environment
Postman environments are used to define the state of each API as it moves through the API lifecycle. Providing a machine readable definition that can be used to develop, stage, and put an API into production. In addition to the actual development and delivery of each aPI, these environments are used to guide each API along the API life cycle, and to realize this API governance vision.

 - Is there a development environment?
 - Is there a mock development environment?
 - Is there a production environment?
 - Is there a mock production environment?

### Owner
Making sure that each API has an owner, with up to date contact information so that there is always someone taking ownership over what is happening.

 - Is there a contact for the API?
 - Is there a contact name for this API?
 - Is there a contact email for the API?


## Design
### Info
Making sure the most common information about each API is as complete as possible. Providing an area of each aPIs contract that describes the value each API delivers, standardizing what information is available about APIs across operations.


 - Does the name of the API meet requirements?
 - Does the description of the API meet requirements?

### Paths
This section is about evaluating each individual path being used to make API resources available. Helping make sure there is a consistent approach to the naming, structure, and scope of surface area of each API. Providing a well designed set of paths for getting at the valuable resources being made available via Union Fashion APIs.

 - Are paths using words?

### Methods
These governance requests are about interrogating each individual method of an API, helping set guidelines for how APIs are structured, using a common vocabulary for making data available. Defining the vocabulary of the Union Fashion operations, ensuring that we all speak the same language when it comes to working with Union Fashion digital assets.

### Parameters
For the methods that have parameters, there are a number of details that should be present. This area of governance is about making sure that path and query parameters are consistent across all APIs, employing the same patterns for how resources are defined, and made accessible via Union Fashion APIs.

### Request Bodies
For the methods that have request bodies, there are number of details that should exist. Providing guidelines for how the body is used across POST, PUT, PATCH, and other suitable methods. Ensuring that the payload of each API is consistently shaping each request, providing what is needed to shape the desired response.

### Responses
Moving beyond the request surface area of each API, this area of governance is about shaping the response for each individual API method. Helping establish the rules for how each response should be returned, providing a consistent experience across all APIs, reducing friction when it comes to integrating Union Fashion resources in internal, partner, and public applications.

 - Does GET, POST, PUT, and DELEETE exist for all resources?
 - Do all methods have summaries?
 - Do all methods have descriptions?
 - Do all methods have operation ids?
 - Do all methods have tags?

### Schema
Next, we want to drill further into the schema that is used as part of the request and response structure of each API. Being more organized about how schema are used as part of the request body, and returned with each response, making sure the schema used across the platform are part of a larger strategy for managing the structure of digital resources.

 - Do all schema have properties?
 - Do all schema properties have descriptions?


## Mocks
 - Is there a mock development server? - undefined
 - Is there a mock production server? - undefined

## Development
 - Is there a development server? - undefined
 - Is there a development stage defined with the API gateway? (COMING SOON) - undefined

## Production
 - Is there a production server? - undefined
 - Is there a production stage defined with the API gateway? (COMING SOON) Copy - undefined

## Management
 - Is there an API plan? - undefined
 - Is there an API key? - undefined

## Testing
### Contract Testing
 This section is for tracking on what contract testing is in place, making sure the contract of each API is being regularly tested.

 - Is there output from contract tests?
 - Did the API pass the contract tests?

### Security Testing
 This section is for tracking on what security testing is in place, making sure the security of each API is being regularly tested.

 - Is there output from security tests?
 - Did the API pass the security tests?

### Performance Testing
 This section is for tracking on what performance testing is in place, making sure the overall quality of service of each API is being regularly tested.

 - Is there output from performance tests?
 - Did the API pass the performance tests?


## Monitornig
 - Is there a contract testing collection monitor? - undefined
 - Is there a performance testing collection monitor? - undefined
 - Is there a security testing collection monitor? - undefined

## Support
### Road Map
This area is about making sure there is a road map for each API, revealing what the next steps are for each API.

 - Is GitHub issues setup for tracking roadmap?
 - How many road map entries are there?

### Issues
Making sure there is an active issue thread being shared, making sure consumers are kept aware of active issues with each API.

 - Is GitHub issues setup for tracking issues?
 - How many open issue entries are there? (COMING SOON)
 - How many close issue entries are there? (COMING SOON)

### Change Log
Relabeling things from the road map that get delivered, providing a change log of everything that has occurred to each API.

 - How many change log entries are there? (COMING SOON)
 - Is GitHub issues setup for tracking change log?


## LIcense
 - Is there a license for the API?? - undefined
 - How many road map entries are there? (COMING SOON) Copy - undefined

