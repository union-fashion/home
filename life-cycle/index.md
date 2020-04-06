# API Governance
This is the current outline for API governance, providing an overview of how APIs are moved forward.

- [**Documentation**](https://documenter.getpostman.com/view/10394726/SzYUagbA?version=latest)
## Define
This is the first stop of the API life cycle, and is all about defining each API in a consistent way. Providing the foundation for what an API will become, and provide the artifacts needed to understand how well each API is doing, and where it is in its journey. Providing a common approach to using a variety of artifacts to define each APIs, well as dedicated spaces for collaborate around the evolution of artifacts, and apply then throughout the API life cycle to consistently push forward each API being delivered.

### Workspaces (Postman)
This is for designing the Postman workspace that is used for managing this API, allowing it to be stored in one or many workspaces, with different levels of access for developers, QA, and other stakeholders. Establishing a single space where all work will occur on this API, allowing all stakeholders to easily find everything about an API.

 - Single Workspace - Needs a description.
 - All Workspaces - Needs a description.
 - Create Workspace - Needs a description.

### Organizations (GItHub)
This area is for managing the GitHub organization used as part of the development and delivery of each API. Right now there is ajust a single workspace for Union Fashion, but we anticipate creating some other designated workspace for partnering with other groups.

 - Organizations - Needs a description.
 - Organization - Needs a description.

### Repository (GitHub)
This is for managing the GitHub repository for the API being managed, providing a single location to manage its life cycle.

 - Add User Repository - Needs a description.
 - Add Org Repository - Needs a description.
 - Repository - Needs a description.
 - Repositories - Needs a description.

### APIs (Postman)
This is for managing APIs within this workspace, providing requests that can be used to work with the different vesions of each API, using the central truth of this API as part of other processes and integrations.

 - Single API - Needs a description.
 - Get all APIs - Needs a description.
 - Get All API Versions - Needs a description.
 - Get An API Version - Needs a description.
 - Get API Schema - Needs a description.

### Collections (Postman)
This area is for managing collections derived from the contract for the API being managed. Each API should have a consistent set of collection each with a specific name and purpose. Each API should have the following collection to help manage different aspects of the API life cycle.

- **Life Cycle** - The collection that guides This API along a designated path, ensuring that each stop along this APIs journey is in alignment with other Union Fashion APIs, ensuring APIs operate in a similar way across teh organization.
- **Working** - A working collection that is just used for working with the API and defining the surface area of the API in real time without potentially affecting documentation, mocks, tests, and other types of collections.
- **Documentation** - The documentation collection are design for publishing both API documentation as well as generate mock servers for each API, providing a consistent definition that can be used to make each API more tamgible without writing code.
- **Contract Testing** - A collection designated for contract testing on each API providing a set of tests that cover 100% of the API, ensuring that each API is meeting its obligations as defined by the APIs contract.
- **Performance** - Designating collections that are specifically for evaluating the performance of this API, checking the latency around the clock from different geographic regions, focusing on the quality of each API being delivered as part of Union FAshion.
- **Security** - Having a collection that only looks at the security of an API, ensuring that the entire surface area of each API is secure, and the practices in place across APIs are consistent with an organizational wide strategy.
- **Governance** - The final collection type which is focused on the overal consistency, quality, and scope of APIs being delivered across teams, helping ensure that Union Fashion APIs are deliver a seamless experience no matter who delivers each aPI.

We will be adding other collections to this list as they are developed. WE are anticipating needing integration testing and workflow collections, but are failry cnfident there will be other types of collections to emerge as our approach to delivering APIs mature.

### Maintenance
These are some maintenance requests making it easier to work with coolection in use across the delivery of this API. Storing these requests away for when they are needed to qucikly make sense of what is going on with collections that are available in this workspace.

 - All Collections - Needs a description.
 - Single Collection  - Needs a description.
 - Create Collection - Needs a description.
 - Update Collection - Needs a description.
 - Delete Collection - Needs a description.

 - Record Collections in Environment - Needs a description.

### Environments (Postman)
This is the stop along the API life cycle that is focused on managing the environments for how an API is developed and delivered, as well as consumed and integrated. Providing one or more different contexts in which this API can be managed and used.

Right now the guidance is to have two separate environments for each of the stages of development of this API, providing a key / value store for the API during each of these stages:

- **Development** - A key value store for abstracting away everything that is need to develop an API in an API design first manner, storing keys, tokens, and other vital information that is needed to bring a new version of an API to life.
- **Production** - A key value store for abstracting away everything that is need to operate and sustain an API, storing keys, tokens, and other vital information that is needed to properly deliver each API to consumers publicly or privatley.

Eventually we made add a middle stage between development and production, but for now we'll just separate out development from production. After the stages of developerment, there are two other envrionments that should be present for each API:

- **Life Cycle** - This colleciton is designed to help move each API forward, providing the details needed all along the API life cycle, while harvesting and aggregating valuable details about what is going on with this API as it oves forward.
- **Governance** - This collection is about storing what is needed to govern this API, helping understand the overal definition and design of the API, but also every other stop along the API life cycle to quantify and understand what is happening.

Each API should have these four environments, providing an up to date snapshot of this API in these four states. Helping interact with the API while in development as well as in production, but also helping to push forward the API in a consistent way using API, and by having a coherent API governance strategy to ensure API behavior is consistent across the organizaiton.

### Maintenance
These are some maintenance requests making it easier to work with environments in use across the delivery of this API. Storing these requests away for when they are needed to qucikly make sense of what is going on with environments that are available in this workspace.

 - Environments - Needs a description.
 - Environment - Needs a description.
 - Environment - Needs a description.
 - Environment - Needs a description.
 - Environment - Needs a description.

 - Record Environments in  Life Cycle Environment - Needs a description.
 - Pull a list of life cycle environment variables - Needs a description.

### Tagging
This is an aggregate of all of the tagging in use across the infrastructure used to manage this API providing a look at the common vocabulary that is in use as part of operating APIs, helping better define boundaries between APIs across share infrastructure.

### Database (AWS RDS)
These are tagging resources for use on AWS RDS databases used to power this API.

 - Remove Tags From Resource - Needs a description.
 - List Tags For Resource - Needs a description.
 - Add Tags To Resource - Needs a description.

### Compute (AWS Lambda)
This is the tagging layer for this API, providing information about all script activity.

 - List Tags - Needs a description.
 - Tag Resource - Needs a description.
 - Untag Resource - Needs a description.

### Storage (AWS S3)
This is the tagging layer for AWS S3, providing a tagging vocabulary for using across objects made available throuigh this API.

### Bucket Tagging
This section if for managing the tagging applied to buckets.

### Object Tagging
Needs a description.


### Logging (AWS API CloudTrail)
These are tagging requests available for defining the logging layer underneath the operation of the API.

 - Add Tags - Needs a description.
 - List Tags - Needs a description.
 - Remove Tags - Needs a description.

### Support (GitHub)
This is for managing the GitHub labels applied to different layers of the support infrastructure for this API.

 - Labels for Repo - Needs a description.
 - New Label - Needs a description.
 - Update Label - Needs a description.
 - Single Label - Needs a description.
 - Delete Label - Needs a description.


 - Create New API
 - Pull From API


## Design (Postman)
This provides some quick features for managing the design of the API, allowing you to quickly add resources, parameters, schema property, headers, responses, and other moving parts of the API--automatically generating the OpenAPI vocabulary as part of the core API schema.

### Components
This is for speeding up the construction and evolution of the design of each API, allowing you to add common components and patterns to the APIs in this workspace.

 - Add Resource - Needs a description.
 - Add Schema Property - Needs a description.
 - Add Query Parameter - Needs a description.
 - Add Header - Needs a description.
 - Add Response - Needs a description.



## Mock (Postman)
This allows for publishing and management of mocks for different versions of this API, providing static representations of this API that can be used to speed up development, and can be used as part of testing.

### Maintenance
These are maintenance requests for managing mock servers that are in use, helping manage how mock servers are used across this API, making sure they are being used properly across APIs.

 - Mock - Needs a description.
 - Mocks - Needs a description.
 - Mock - Needs a description.

 - Create Development Mock
 - Create Production Mock


## Database (AWS DynamoDB)
This is for managing the data store behind this API using AWS DynamoDB. Providing a persisent store for a development or production instance of the API. This should only be used for simple APIs resources using a NoSQL pattern, providing a quick and easy store behind each API.

### Backup
This section is for managing database backups for APIs.

 - Create Backup - Needs a description.
 - Delete Backup - Needs a description.
 - Describe Backup - Needs a description.
 - List Backups - Needs a description.
 - Describe Continuous Backups - Needs a description.
 - Update Continuous Backups - Needs a description.

### Restore
This section is for restoring database powering APIs.

 - Restore Table From Backup - Needs a description.
 - Restore Table To Point In Time - Needs a description.

 - List Tables
 - Create New Table


## Database (Amazon RDS)
This is for managing the data store behind this API using Amazon RDS. Providing a persisent store for a development or production instance of the API.

### Instances
Managing the RDS instances that are in use.

 - Create DB Instance - Needs a description.
 - Delete DB Instance - Needs a description.
 - Describe DB Instances - Needs a description.
 - Modify DB Instance - Needs a description.
 - Reboot DB Instance - Needs a description.
 - Start DB Instance - Needs a description.
 - Stop DB Instance - Needs a description.

### Logs
The logging for the RDS database backend, providing the details on all usage of the database, which can be audited and used across operations.

 - Describe Log Files - Needs a description.
 - Download Log File Portion - Needs a description.

### Tags
undefined

 - Remove Tags From Resource - Needs a description.
 - List Tags For Resource - Needs a description.
 - Add Tags To Resource - Needs a description.

### Restore
undefined

 - Restore DB Instance From S3 - Needs a description.
 - Restore DB Instance To Point In Time - Needs a description.



## Compute (AWS Lambda)
This is the stop along the API life cycle for managing the compute for use behind APIs, leverage AWS Lambda for the compute when it is needed behind each API method, providing a scripting layer for powering each API.

### Configuration
This is the configuration of the lambda scripts behind the API.

 - Get Function Configuration - Needs a description.
 - Update Function Configuration - Needs a description.

### Tags
This is the tagging layer for this API, providing information about all script activity.

 - List Tags - Needs a description.
 - Tag Resource - Needs a description.
 - Untag Resource - Needs a description.

 - Funtions
 - Function
 - Update Function Code
 - Invoke Copy


## Storage (AWS S3)
This is one of the storage infrastructure opportunities that exist for Union fashion, providing heavy object storage across 

### Buckets
This section for managing AWS S3 buckets that are used as part of the operation of this API.

### Tagging
This section if for managing the tagging applied to buckets.

 - Bucket Tags - Needs a description.
 - Delete Bucket Tag - Needs a description.
 - Bucket Tag - Needs a description.

 - List - Needs a description.
 - Create - Needs a description.
 - Delete - Needs a description.

### Objects
undefined

### Uploads
Needs a description.

 - Create Multipart - Needs a description.
 - Multipart - Needs a description.
 - Complete Multipart - Needs a description.
 - Part - Needs a description.
 - Part Copy - Needs a description.
 - Abort Multipart - Needs a description.

### Tagging
Needs a description.

 - Object Tagging - Needs a description.
 - Tagging - Needs a description.
 - Delete Object Tagging - Needs a description.

 - Objects - Needs a description.
 - Object - Needs a description.
 - Parts - Needs a description.
 - Copy Object - Needs a description.
 - Delete Object - Needs a description.
 - Delete Objects - Needs a description.



## Pipeline (GitHub Actions)
This area is for managing the pipeline behind each API, establishing a repeatable set of patterns that can be used to deploy any code needed to make each API work as expected.

 - Artifacts
 - Secrets
 - Runners
 - Workflows
 - Workflows Runs
 - Workflows Jobs


## Deploy - (AWS API Gateway)
This is the portion of the life cycle for actually deployment the API, allowing for the deployment of development, production, or other stage of API to AWS using AWS API Gateway.

### Maintenance
This section is for the maintenance of APIs being deployed as part of the API life cycle using AWS API Gateway. 

 - List all APIs - Needs a description.
 - Details of API - Needs a description.
 - Details of API Deployment - Needs a description.
 - Export OpenAPI 3.0 - Needs a description.
 - Delete an API - Needs a description.
 - Delete an API Deployment - Needs a description.

 - Build OpenAPI with DynamoDB Backend
 - Publish to Gateway
 - Deploy to Development on API Gateway
 - Deploy to Staging on API Gateway
 - Deploy to Production on API Gateway


## Manage - AWS API Gateway
This is the stop along the API life cycle for managing the API, defining how it will be accessed by cosumers, ensuring there is visibility across API operations.

### Usage Plans
Managing the usage plans in which APIs operate under, defining how API can be used by consumers. Establishing limits for each area of APIs.

 - All - Needs a description.
 - Single - Needs a description.
 - Add Usage Plan for API - Needs a description.

### Stages
undefined

 - By Name Stage - Needs a description.
 - Create Stage - Needs a description.
 - Delete Stage - Needs a description.
 - Flush Authorizer Cache Stage - Needs a description.
 - Flush Cache Stage - Needs a description.
 - Update Stage - Needs a description.
 - Tagsget - Needs a description.
 - Tagstag - Needs a description.
 - Tagsuntag - Needs a description.

### Keys
This is the area for managing the keys being used to access the APIs that are deployed to the AWS API gateway. Allowing keys to be issued for all cosumers of this API using the AWS API Gateway.

 - All - Needs a description.
 - Single - Needs a description.
 - Add Key for API - Needs a description.
 - Add Key to Usage Plan - Needs a description.

 - Get Usage


## Logging
This is the stop along the API life cycle for aggregating of logging across operations, providing a central place where all logs can be access and used to audit and orchestration what is happening.

### Central Logging (AWS API CloudTrail)
This pulls the logs for API activity from the AWS API Gateway, providing a trail of the usage across all APIs.

 - Trails - Needs a description.
 - Trails Cop - Needs a description.

### Central Tagging (AWS API CloudTrail)
undefined

 - Add Tags - Needs a description.
 - List Tags - Needs a description.
 - Remove Tags - Needs a description.

### Storage Logging (AWS S3)
This is the logging for AWS S3, providing a look at how objects are used across this API, helping stay aware of what is being accessed.

 - Bucket Logging - Needs a description.
 - Bucket Logging - Needs a description.

### Database (AWS RDS)
The logging for the RDS database backend, providing the details on all usage of the database, which can be audited and used across operations.

 - Describe Log Files - Needs a description.
 - Download Log File Portion - Needs a description.



## Encryption
This is for managing encryption used as part of API operations, helping work with certificates and make sure they are applied consistently across each API.

 - List CloudFlare Certificates
 - AWS API Gateway Client Certificates
 - Generate Client Certificate
 - AWS API Gateway Client Certificate
 - AWS API Gateway Client Certificate


## DNS
This manages the DNS for all of the APIs, allowing for custom addressing across all resources.

### Analytics (CLoudflare)
undefined

 - Table - Needs a description.
 - By time - Needs a description.

 - Zones (CloudFlare)
 - DNS Records (CloudFlare)
 - Domain Names (AWS API Gateway)
 - Domain Name (AWS API Gateway)


## Portal (GitHub)
This is the stop along the API life cycle to ensure that an API has a single doorway for accessing all fo the details of its operations.

### Documentation (Postman)
This is the area of the life cycle for making sure the API has appropriate documentation for use by other stakeholders as part of it's usage. There is no way to publish documentation right now using the Postman API, but his request is to record the details of what has been published.

 - Sets Documentation URL - Needs a description.

### Discovery (GitHub)
This is the stop along the API life cycle for making sure the API can be properly found and is accounted for.

 - Update APIs.json - Needs a description.

 - Update README


## Testing (Postman)
This is the area for managing all of the testing for this API -- still under construction.

### Contract Testing
This is where we will be assessing the state of contract testing for this API. Publishing a handful of things that should be in place for each API when it comes to validating its API contract.


 - Contract (COMING SOON) - Needs a description.

### Performance Testing
This is where we tracking on the state of performance testing for this API, ensuring that all APIs are being tested for their performance and overall level of service alongside other testing.

 - Performance (COMING SOON) - Needs a description.



## Security
This is the area for managing the security of the API, scanning, testing, and executing different security processes against the current API. Automating the security of each API, and helping using the testing layer of Postman to secure APIs consistently.

### Database Security Groups (AWS RDS)
Work with database security groups to help ensure databases are properly secured.

 - Create Security Group - Needs a description.
 - Delete Security Group - Needs a description.
 - Describe Security Groups - Needs a description.

### Database Security Groups Ingress (AWS RDS)
Actually adding and removing access to security groups for specific IP address, and other network interfaces.

 - Authorize Ingress - Needs a description.
 - Revoke Ingress - Needs a description.

### Security Testing
This is where we tracking on the state of security testing for this API, ensuring that all APis are being properly and consistently secured.

 - Security (COMING SOON) - Needs a description.



## Monitoring (Postman)
This is where the monitoring of this API occurs, and monitors are setup to execute the various collections to achieve specific outcomes in relationship to moving the API forward, and applying governance.

### Maintenance
These are maintenance requests for working with monitors.

 - All Monitors - Needs a description.
 - Single Monitor - Needs a description.
 - Create Monitor - Needs a description.
 - Update Monitor - Needs a description.
 - Delete Monitor - Needs a description.
 - Run a Monitor - Needs a description.

 - Create Contract Test Monitor
 - Create Performance Test Monitor
 - Create Security Test Monitor


## Support  (GitHub)
This is the stop for managing support around the operations of this API, ensuring that all APIs are being supported across the organization.

### Tickets (GitHub)
Issues that have been submitted via GitHub and are flagged as ticket for review my API owners.

 - All Tickets - Needs a description.
 - New Ticket - Needs a description.
 - Single Ticket - Needs a description.
 - Close Ticket - Needs a description.

### Issues  (GitHub)
These are GitHub issues that have been flagged to display known issues, helping make consumers aware of known issues. 

 - All Issues - Needs a description.
 - New Issue - Needs a description.
 - Single Issue - Needs a description.
 - Close Issue - Needs a description.

### Change Log (GitHub)
These are the GitHub issues that have been added an and labeled as change log showing what has been accomplished already.

 - All Change Log Entries - Needs a description.
 - New Change Log Entry - Needs a description.
 - Single Change Log Entry - Needs a description.
 - Close Change Log Entry - Needs a description.

### Road Map (GitHub)
These are the GitHub issues that have been labeled for display as part of the road map, helping share what is being planned around API development.	

 - All Road Map Items - Needs a description.
 - New Road Map Item - Needs a description.
 - Single Road Map Item - Needs a description.
 - Mark Complete - Needs a description.



## Communication  (GitHub)
This is the stop along the API life cycle for ensuring there is proper communication around the operation of the API.

### Blog
This is the area for managing the blog communications for this API. It should be replaced with requests for pulling and publishing of blog posts using Jekyll on GitHub.

 - Blog Post - Needs a description.
 - Blog Posts - Needs a description.
 - Blog Post - Needs a description.

### Twitter
This is the area for managing Tweets about API operations, providing regular updates.

 - Tweet - Needs a description.
 - Twitter Tweet Search - Needs a description.
 - Twitter User Search - Needs a description.



## Analytics
This area is for hanging all of the analytics that exist across the surface area of an API, providing observability across the API life cycle by aggregating all of the outputs of existing systems.

### Analytics (CLoudflare)
This section provides visibility into the DNS layer for each API being delivered.

 - Table - Needs a description.
 - By time - Needs a description.

### Usage (AWS API Gateway)
This provides visibility into the usage of each API at the API gateway layer.

 - Get Usage Copy - Needs a description.



## Deprecation
This is the stop along the API life cycle which determines when a resource will be deprecated.

 - Set Sunset HTTP Header
 - Add Deprecation Date To Road Map


## Reporting
These are some reporting actions that can be taken as part of the management of each API.

 - Publish API life cycle outline to GitHub
 - Visualize the API life cycle outline

