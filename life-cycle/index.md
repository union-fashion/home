# API Governance
This is the current outline for API governance, providing an overview of how APIs are moved forward.

- [**Documentation**](https://documenter.getpostman.com/view/10394726/SzYUagbA?version=latest)
## Define
This is the first stop of the API life cycle, and is all about defining each API in a consistent way. Providing the foundation for what an API will become, and provide the artifacts needed to understand how well each API is doing, and where it is in its journey. Providing a common approach to using a variety of artifacts to define each APIs, well as dedicated spaces for collaborate around the evolution of artifacts, and apply then throughout the API life cycle to consistently push forward each API being delivered.

### Workspaces (Postman)
This is for designing the Postman workspace that is used for managing this API, allowing it to be stored in one or many workspaces, with different levels of access for developers, QA, and other stakeholders. Establishing a single space where all work will occur on this API, allowing all stakeholders to easily find everything about an API.

 - Single Workspace
 - All Workspaces
 - Create Workspace

### Organizations (GItHub)
This area is for managing the GitHub organization used as part of the development and delivery of each API. Right now there is ajust a single workspace for Union Fashion, but we anticipate creating some other designated workspace for partnering with other groups.

 - Organizations
 - Organization

### Repository (GitHub)
This is for managing the GitHub repository for the API being managed, providing a single location to manage its life cycle.

 - Add User Repository
 - Add Org Repository
 - Repository
 - Repositories

### APIs (Postman)
This is for managing APIs within this workspace, providing requests that can be used to work with the different vesions of each API, using the central truth of this API as part of other processes and integrations.

 - Single API
 - Get all APIs
 - Get All API Versions
 - Get An API Version
 - Get API Schema

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

 - Record Collections in Environment

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

 - Record Environments in  Life Cycle Environment
 - Pull a list of life cycle environment variables

### Tagging
This is an aggregate of all of the tagging in use across the infrastructure used to manage this API providing a look at the common vocabulary that is in use as part of operating APIs, helping better define boundaries between APIs across share infrastructure.

### Database (AWS RDS)
These are tagging resources for use on AWS RDS databases used to power this API.

### Compute (AWS Lambda)
This is the tagging layer for this API, providing information about all script activity.

### Storage (AWS S3)
This is the tagging layer for AWS S3, providing a tagging vocabulary for using across objects made available throuigh this API.

### Logging (AWS API CloudTrail)
These are tagging requests available for defining the logging layer underneath the operation of the API.

### Support (GitHub)
This is for managing the GitHub labels applied to different layers of the support infrastructure for this API.


 - Create New API
 - Pull From API


## Design (Postman)
This provides some quick features for managing the design of the API, allowing you to quickly add resources, parameters, schema property, headers, responses, and other moving parts of the API--automatically generating the OpenAPI vocabulary as part of the core API schema.

### Components
This is for speeding up the construction and evolution of the design of each API, allowing you to add common components and patterns to the APIs in this workspace.

 - Add Resource
 - Add Schema Property
 - Add Query Parameter
 - Add Header
 - Add Response



## Mock (Postman)
This allows for publishing and management of mocks for different versions of this API, providing static representations of this API that can be used to speed up development, and can be used as part of testing.

### Maintenance
These are maintenance requests for managing mock servers that are in use, helping manage how mock servers are used across this API, making sure they are being used properly across APIs.

 - Mock
 - Mocks
 - Mock

 - Create Development Mock
 - Create Production Mock


## Database (AWS DynamoDB)
This is for managing the data store behind this API using AWS DynamoDB. Providing a persisent store for a development or production instance of the API. This should only be used for simple APIs resources using a NoSQL pattern, providing a quick and easy store behind each API.

### Backup
undefined

 - Create Backup
 - Delete Backup
 - Describe Backup
 - List Backups
 - Describe Continuous Backups
 - Update Continuous Backups

### Restore
undefined

 - Restore Table From Backup
 - Restore Table To Point In Time

 - List Tables
 - Create New Table


## Database (Amazon RDS)
This is for managing the data store behind this API using Amazon RDS. Providing a persisent store for a development or production instance of the API.

### Instances
Managing the RDS instances that are in use.

 - Create DB Instance
 - Delete DB Instance
 - Describe DB Instances
 - Modify DB Instance
 - Reboot DB Instance
 - Start DB Instance
 - Stop DB Instance

### Logs
The logging for the RDS database backend, providing the details on all usage of the database, which can be audited and used across operations.

 - Describe Log Files
 - Download Log File Portion

### Tags
undefined

 - Remove Tags From Resource
 - List Tags For Resource
 - Add Tags To Resource

### Restore
undefined

 - Restore DB Instance From S3
 - Restore DB Instance To Point In Time



## Compute (AWS Lambda)
This is the stop along the API life cycle for managing the compute for use behind APIs, leverage AWS Lambda for the compute when it is needed behind each API method, providing a scripting layer for powering each API.

### Configuration
This is the configuration of the lambda scripts behind the API.

 - Get Function Configuration
 - Update Function Configuration

### Tags
This is the tagging layer for this API, providing information about all script activity.

 - List Tags
 - Tag Resource
 - Untag Resource

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

 - List
 - Create
 - Delete

### Objects
undefined

### Uploads
undefined

### Tagging
undefined

 - Objects
 - Object
 - Parts
 - Copy Object
 - Delete Object
 - Delete Objects



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

 - List all APIs
 - Details of API
 - Details of API Deployment
 - Export OpenAPI 3.0
 - Delete an API
 - Delete an API Deployment

 - Build OpenAPI with DynamoDB Backend
 - Publish to Gateway
 - Deploy to Development on API Gateway
 - Deploy to Staging on API Gateway
 - Deploy to Production on API Gateway


## Manage - AWS API Gateway
This is the stop along the API life cycle for managing the API, defining how it will be accessed by cosumers, ensuring there is visibility across API operations.

### Usage Plans
Managing the usage plans in which APIs operate under, defining how API can be used by consumers. Establishing limits for each area of APIs.

 - All
 - Single
 - Add Usage Plan for API

### Stages
undefined

 - By Name Stage
 - Create Stage
 - Delete Stage
 - Flush Authorizer Cache Stage
 - Flush Cache Stage
 - Update Stage
 - Tagsget
 - Tagstag
 - Tagsuntag

### Keys
This is the area for managing the keys being used to access the APIs that are deployed to the AWS API gateway. Allowing keys to be issued for all cosumers of this API using the AWS API Gateway.

 - All
 - Single
 - Add Key for API
 - Add Key to Usage Plan

 - Get Usage


## Logging
This is the stop along the API life cycle for aggregating of logging across operations, providing a central place where all logs can be access and used to audit and orchestration what is happening.

### Central Logging (AWS API CloudTrail)
This pulls the logs for API activity from the AWS API Gateway, providing a trail of the usage across all APIs.

 - Trails
 - Trails Cop

### Central Tagging (AWS API CloudTrail)
undefined

 - Add Tags
 - List Tags
 - Remove Tags

### Storage Logging (AWS S3)
This is the logging for AWS S3, providing a look at how objects are used across this API, helping stay aware of what is being accessed.

 - Bucket Logging
 - Bucket Logging

### Database (AWS RDS)
The logging for the RDS database backend, providing the details on all usage of the database, which can be audited and used across operations.

 - Describe Log Files
 - Download Log File Portion



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

 - Table
 - By time

 - Zones (CloudFlare)
 - DNS Records (CloudFlare)
 - Domain Names (AWS API Gateway)
 - Domain Name (AWS API Gateway)


## Portal (GitHub)
This is the stop along the API life cycle to ensure that an API has a single doorway for accessing all fo the details of its operations.

### Documentation (Postman)
This is the area of the life cycle for making sure the API has appropriate documentation for use by other stakeholders as part of it's usage. There is no way to publish documentation right now using the Postman API, but his request is to record the details of what has been published.

 - Sets Documentation URL

### Discovery (GitHub)
This is the stop along the API life cycle for making sure the API can be properly found and is accounted for.

 - Update APIs.json

 - Update README


## Testing (Postman)
This is the area for managing all of the testing for this API -- still under construction.

### Contract Testing
This is where we will be assessing the state of contract testing for this API. Publishing a handful of things that should be in place for each API when it comes to validating its API contract.


 - Contract (COMING SOON)

### Performance Testing
This is where we tracking on the state of performance testing for this API, ensuring that all APIs are being tested for their performance and overall level of service alongside other testing.

 - Performance (COMING SOON)



## Security
This is the area for managing the security of the API, scanning, testing, and executing different security processes against the current API. Automating the security of each API, and helping using the testing layer of Postman to secure APIs consistently.

### Database Security Groups (AWS RDS)
Work with database security groups to help ensure databases are properly secured.

 - Create Security Group
 - Delete Security Group
 - Describe Security Groups

### Database Security Groups Ingress (AWS RDS)
Actually adding and removing access to security groups for specific IP address, and other network interfaces.

 - Authorize Ingress
 - Revoke Ingress

### Security Testing
This is where we tracking on the state of security testing for this API, ensuring that all APis are being properly and consistently secured.

 - Security (COMING SOON)



## Monitoring (Postman)
This is where the monitoring of this API occurs, and monitors are setup to execute the various collections to achieve specific outcomes in relationship to moving the API forward, and applying governance.

### Maintenance
These are maintenance requests for working with monitors.

 - All Monitors
 - Single Monitor
 - Create Monitor
 - Update Monitor
 - Delete Monitor
 - Run a Monitor

 - Create Contract Test Monitor
 - Create Performance Test Monitor
 - Create Security Test Monitor


## Support  (GitHub)
This is the stop for managing support around the operations of this API, ensuring that all APIs are being supported across the organization.

### Tickets (GitHub)
Issues that have been submitted via GitHub and are flagged as ticket for review my API owners.

 - All Tickets
 - New Ticket
 - Single Ticket
 - Close Ticket

### Issues  (GitHub)
These are GitHub issues that have been flagged to display known issues, helping make consumers aware of known issues. 

 - All Issues
 - New Issue
 - Single Issue
 - Close Issue

### Change Log (GitHub)
These are the GitHub issues that have been added an and labeled as change log showing what has been accomplished already.

 - All Change Log Entries
 - New Change Log Entry
 - Single Change Log Entry
 - Close Change Log Entry

### Road Map (GitHub)
These are the GitHub issues that have been labeled for display as part of the road map, helping share what is being planned around API development.	

 - All Road Map Items
 - New Road Map Item
 - Single Road Map Item
 - Mark Complete



## Communication  (GitHub)
This is the stop along the API life cycle for ensuring there is proper communication around the operation of the API.

### Blog
This is the area for managing the blog communications for this API. It should be replaced with requests for pulling and publishing of blog posts using Jekyll on GitHub.

 - Blog Post
 - Blog Posts
 - Blog Post

### Twitter
This is the area for managing Tweets about API operations, providing regular updates.

 - Tweet
 - Twitter Tweet Search
 - Twitter User Search



## Analytics
This area is for hanging all of the analytics that exist across the surface area of an API, providing observability across the API life cycle by aggregating all of the outputs of existing systems.

### Analytics (CLoudflare)
This section provides visibility into the DNS layer for each API being delivered.

 - Table
 - By time

### Usage (AWS API Gateway)
This provides visibility into the usage of each API at the API gateway layer.

 - Get Usage Copy



## Deprecation
This is the stop along the API life cycle which determines when a resource will be deprecated.

 - Set Sunset HTTP Header
 - Add Deprecation Date To Road Map


## Reporting
These are some reporting actions that can be taken as part of the management of each API.

 - Publish API life cycle outline to GitHub
 - Visualize the API life cycle outline

