# Life Cycle
This is the API life cycle for managing all Union Fashion APIs, helping provide a consistent set of steps that can be accomplished by anyone delivering APIs across the organization.

Here is the current outline for the Union Fashion API life cycle.

- **Define**** - Defining APIs and their platform.
    - **Workspace**** - Establishing a Postman workspace.
    - **Organizations**** - Establishing a GitHub organization.
    - **Repositories**** - Establishing a GitHub repository.
    - **APIs**** - Defining an API contract for each API.
    - **Collection**** - Define the derivatives of an API.
    - **Environments**** - Define the environments for an API.
- **Design**** - Handling the design of APIs consistently.
    - **New Components**** - Helpers to quickly add new components.
    - **Existing Components**** - Helpers to reuse components.
- **Mocks**** - Providing mock representations of APIs.
- **Documentation**** - Documenting the surface area of each API.
- **Versioning**** - Making sure that versioning is well managed.
- **Database**** - Establishing persistent data stores for APIs.
- **Compute**** - Providing a computer layer for each API.
- **Storage**** - Establish an an object store for each API.
- **Deploy**** - Deploying APIs into different stages.
- **Manage**** - Managing all API consistently across operations.
- **Logging**** - Ensuring all activity is being logged.
- **Encryption**** - Making sure encryption is the default.
- **DNS**** - Defining the addressing for all API infrastructure.
- **Portal**** - Having a common doorway for all APIs.
- **Road Map**** - Publishing the road map for each API.
- **Change Log**** - Ensuring there is a change log for APIs.
- **Issues**** - Publishing any open issues that are known.
- **Support**** - Providing consistent support across APIs.
- **Communication**** - Ensuring consistent communication for teams.
- **Testing**** - Making sure there is tests across all APIs.
- **Performance**** - Understanding the performance of APIs.
- **Security**** - Scanning an auditing the security of APIs.
- **Monitoring**** - Scheduling the monitoring of all APIs.
- **Discovery**** - Making sure all APIs are discoverable.
- **Deprecation**** - Planning for the deprecation of all APIs.

Each of these stops along the API life cycle are available as part of the Union Fashion API life cycle collection, providing actual executable requests that help you realize each stop along the API life cycle.

| API Life Cycle Collection  | [Docs](http;//)  |  Embed  |

## Define
Providing the base definition that will guide this API throughout the API life cycle.

### Workspace (Postman)
Each individual API should have its own dedicated workspace for managing all the moving parts of an API across its life cycles. These are the actions that can be taken to help manage the dedicated workspace for managing this API, and other workspaces where the API is syndicated within.

- **Get This Workspace** - Get the workspace designated for the API being managed to operate within.
- **Get All Workspaces** - Get a list of all workspaces available as part of the account managing this API.
- **Create New Workspace** - Create a new workspace for either managing this API, or syndicating too.
- **Change Workspace** - Change the workspace for the API being managed to another workspace.
- **Syndicate to Workspace** - Syndicate this API to another workspace beyond its original workspace.
- **Get List of Syndicated Workspaces** - Get a list of workspaces where the API being managed is syndicated.

Postman provides a private workspace that houses all the building, deploying, and operating of a single API, providing a single location where stakeholders can visit to understand what is happening with each API that is being developed, evolved, deprecation, and arching. Providing a single source of truth for activity over the entire life of each API.

### Organizations (GitHUB)
Each individual API should belong to a GitHub organization, providing a public or private bucket for tracking not just this single API, but all the other APIs being developed. Providing a single home page where developers can understand the wider organizational platform and resources available for each individual API being delivered and consumed.

- **Get This Organization** - Get the organization designated for the API being managed to operate within on GitHub.
- **Get All Organizations** - Pull a list of all organizations available as part of the accounting managing this API.
- **Create New Organization** - Create a new GitHub organization that can be used to manage a grouping of APIs.
- **Change Organization** - Change the organization for the API being managed to use another GitHub organization.

The GitHub organization will provide each API with a home. Grouping it within a wider organization, with a home page, website, developer portal, and other shared resources that can be used to define, guide, evolve, and manage each API in a collective way. Providing a consistent place where everything about an API can be found, quantifying the existence of each individual API resource.

### Repository (Github)
Each individual API should have its own GitHub repository which acts as the primary doorway for engaging with an API throughout the entire life cycle. Providing a single source of truth where all artifacts will be stored, evolved, and managed as each API moves through a standardized life cycle process. Consistently tracking the provenance of each API, and making it easier for stakeholders and consumers to find wha they need and stay in tune with what is occurring around each API, with the following actions available:

- **Get This Repository -Gets the GitHub repository that is assigned as part of the management of this individual API.
- **Get All Repositories** - Gets a list of all of the GitHub repositories available for the organization managing this repository.
- **Create New Repository** - Creates a new GitHub repository for use as part of the management of an API.
- **Change Repository** - Changes the repository being used to manage this API, changing its source of truth.

A single repository for each individual serve allows for a single source of truth where all artifacts, conversations, and activity for each API can occur. Providing a complete snapshot of everything being done to move an API forward. Leveraging GitHub to help better organize how APIs are being delivered across an organization, helping bring more observability to each individual API resource.

### APIs
Each API is defined as a machine readable definition using OpenAI or RAML and stored in Postman. Each individual API definition truth will be versioned and managed in Postman and synced to the GitHub repository for the API. There are a number of actions that can be taken when it comes to managing the API source of truth for each API, which will be used to guide an API throughout the API life cycle.

- **Get This API** - Gets the individual API that is being used to manage this project.
- **Get All APIs** - Get a list of all APIs in this workspace for the account managing this API.
- **Get All API Versions** - Get a list of the version that exist for an API being managed.
- **Get a Single API Version** - Returns the detail for a specific version of the API being managed.
- **Get a Single API Schema** - Returns the schema for an individual API version being managed.

Each API will be managed using its central source of truth which is stored in Postman and managed using the Postman platform and on GitHub, making the source of truth available in other products and services. Every stop along the API life cycle will be derived and governed using this central source of truth, providing a single set of definitions that can be applied to understand the value generated from each API resource.

### Collections
Postman collections are used to govern multiple stops along the API life cycle as well this API life cycle and governance. Collections can be generated from the central API truth as well as hand-crafted and maintained manually as part of the process. There are a number of actions that can be take to manage the collections being maintained and executed through the management of this API.

- **Get a Single Collection** - Gets a single collection that is being used as part of the management of this API.
- **Get All Collections** - Gets a list of all collections that are part of the workspace for this API.
- **Delete Collection** - Deletes one of the collections being used to manage this API.

Collections provide a machine readable derivative of the truth for this API, providing a specialized artifact that help publish documentation, deploy mock servers, apply specific tests, and other stops along the API life cycle. Collections, along with the artifacts they can produce provide much of the functionality needed to quantity and execute different stops along the API life cycle while managing this API.

### Environments
Postman environments are used to define and guide different stages of the development, staging, and production for each API, as well as this API life cycle and governance. Providing a static snapshot of the state of each API as it moves forward, providing the key / values needed to quantify an API, and capturing the details of the evolution of each API as it progresses along the API life cycle. Here are a handful of the actions for managing environments for this API.

- **Get All Environments** - Gets all environments that are available within the workspace being used to manage the API.
- **Get a Single Environment** - Gets a single environment from within the workspace being used to manage the API.
- **Create Development Environment** - Creates a single development environment for use during the development process.
- **Create Staging Environment** - Creates a single development environment for use during the staging process.
- **Create Production Environment** - Creates a single development environment for use during the production process.
- **Create Life Cycle Environment** - Creates a single development environment for during the API life cycle for this API.
- **Create Governance Environment** - Creates a single development environment for the governance of this API.
- **Delete an Environment** - Delete a specific environment from the workspace being used to manage the API.

Environments play a central role in how this API life cycle and governance is applied to an API, managing the state of each API, helping apply a consistent set of rules across each API, while helping shepherd the API through its development, staging, and production environments. Environments are for storing of key / value pairs that are needed throughout the management and usage of each API.

## Design
Designing the surface area of an API by adding to the OpenAPI definition, expanding the details each request and response from new and existing components. Applying common patterns to help ensure consistency and purpose across all APIs that are being developed, making it easier to consume APIs by reducing the friction involved with understanding what each API can do.

### New Components
The details of each API definition can quickly become unwieldy due the amount of detail required to full define every aspect of how an API can be used. These are some actions that can be taken which add new design elements to any API, while also saving time in properly crafting the individual components that make up the full definition of each API being moved forward.

- **Add Resource** - Adds a completely new resource path, with GET, POST, PUT, and DELETE methods.
- **Add Schema Property** - Adds a new property to an existing schema object being defined.
- **Add Query Parameter** - Adds a new query parameter to individual HTTP method being defined.
- **Add Header** - Adds a new header to individual HTTP method being defined.
- **Add Response** - Adds a new response to individual HTTP method being defined.

Design components are meant to help make the work of crafting a complete API definition faster and more efficient by allowing developers to rapidly assemble common components of an API design, and then work to further refine to make sure the component fits well with each individual API that is being developed.

### Reusable Components ()
Reusable components are similar to new components except they are carefully crafted, stored, and made available based upon common API patterns that are proven effective across API operations. Allowing API developers to rapidly assemble and evolve API definitions from common building blocks that reflect common industry patterns and organizational API governance, being more consistent in how APIs are delivered across operations.

- **Date** - Using common date standards.
- **Currency** - Using common currency standards.
- **Contact** - Using common contact standards.

Reusable components are only as good as an organizational components library. This API life cycle collection is meant to provide as many common building blocks as possible so that teams don’t have to do the hard work to go find existing patterns, and can learn along the way as they are evolving each individual API across a common API life cycle.

## Mocks (Postman)
Mocks are critical to an API-first process, and continue to play an important role even once an API is moved into product, providing a virtualized instance of an API that can be used to verify an API during the development process, and safely learn about what each API does in production. There are a handful of actions involved in managing the presence of mock servers across the API life cycle.

- **Get Mocks** - Returns all of the mock servers that exist for an API being developed.
- **Get Single Mock** - Gets a single mock server from the workspace for this API.
- **Create Mock** - Adds a new mock server for an API in the designated workspace.
- **Delete Mock** - Removes an existing mock from the current APIs workspace.

Mock servers help rapidly articulate what an API does, and provides a virtualized instance to learn about what is possible for an API. Allowing the static representation of each API to be used as part of testing, on-boarding, and other aspects of delivering and consuming each API.

## Database (AWS DynamoDB)
This stop provides the durable storage needed for an API, allowing data and content that is submitted as part of each API request to be stored for am amount of time and be recalled as part of the development and operations of each API being evolved.

- **List Tables** - Get a list of all the tables that exist in a database.
- **Add Tables** - Adds a new table to database used for each API.
- **Remove Table** - Removes an existing table from a database.

Ultimately there should be a variety of database options for teams to use when developing and delivering their APIs. Providing a consistent way to implement the database behind each API being delivered as part of this API life cycle process.

## Compute (AWS Lambda)
This is where the compute behind an API gets defined, providing the computer power that responses to requests, handle transformations and logic, and then provide the response. Not all APIs will have a compute layer, but for the ones that do, this provides a set of actions	that can be applied when defining and managing the compute stop along the API life cycle.

- **Get Single Function** - Gets a specific serverless function.
- **Get Functions** - Gets all available serverless functions.

Compute will vary for each API, and define the amount resources that are available for each API to use when responding to requests. Which will set the tone for what happens across many of the other stops along the API life cycle like performance and overall reliability.

## Storage (AWS S3) NEEDS CONTENT
This is where the compute behind an API gets defined, providing the computer power that responses to requests, handle transformations and logic, and then provide the response. Not all APIs will have a compute layer, but for the ones that do, this provides a set of actions	that can be applied when defining and managing the compute stop along the API life cycle.

- **Get Single Function** - Gets a specific serverless function.
- **Get Functions** - Gets all available serverless functions.

Compute will vary for each API, and define the amount resources that are available for each API to use when responding to requests. Which will set the tone for what happens across many of the other stops along the API life cycle like performance and overall reliability.

## Deploy (AWS API Gateway)
This is the actual stop along the API life cycle where you can deploy an API using an API, pipeline, or other repeatable process. Providing a proven way to making APIs available, allowing them to go from idea to design, and to something that can actually be used in other applications. Providing a handful of actions that can be taken to bring an API to life as part of a consistent process and infrastructure.

**Default**:

- **Build OpenAPI** - Takes the OpenAPI definition and builds a copy for publishing to the gateway.
- **Publish to AWS API Gateway** - Publishes an API to the gateway using the OpenAPI definition.
- **Deploy to Development on Gateway** - Deploys the API to a specific stage within the API gateway.
- **Deploy to Staging on Gateway** - Deploys the API to a specific stage within the API gateway.
- **Deploy to Production on Gateway** - Deploys the API to a specific stage within the API gateway.

**Maintenance**:

- **Get Deployed APIs** - Gets a list of all the APIs that have been deployed to stages.
- **Get Deployed API** - Gets an individual API that has been deployed to the API Gateway.
- **Export OpenAPI 3.0** - Exports an OpenAPI 3.0 definition from a deployed API.
- **Delete and API** - Deletes an API that has been deployed to the API gateway.

This stop along the API life cycle is about deploying the contract for each API into a development, staging, or production environment. Going beyond a mock, and actually producing a functional representation of each API being moved forward across the API life cycle.

## Manage (AWS API Gateway)
Once an API has been deployed it should always be managed, ensuring that access to each resource has a plan for who should be able to access, and how much of the resource they can use. Developing an awareness of how each individual API resource is put to use across applications, providing a suite of actions that can be taken when it comes to managing how APIs are used, or not used.

### Usage Plans
API management plans define the scaffolding in which one or multiple APIs can be accessed, setting rate limits, and other configurations that define how each API can be put to use. Making sure that every single API has a plan for how it should and shouldn’t be used by developers Planning the usage and the evolution of how each resource can be utilized across applications.

- **Get All Plans** - Gets a list of all the plans available for putting APIs to work.
- **Get Plan** - Gets a single plan that has been setup for usage by APIs.
- **Add Plan** - Creates a new plan that can be used to manage APIs.
- **Get Usage** - Gets the usage of the API being managed within an API plan.

Each individual API can have its own plan, or be grouped under the same plan. Providing unique management definitions to operate each individual API, or set benchmarks that can be applied across several APIs. Being as precise or broad in how APIs are being managed, securing resources while also establishing and wider awareness of how they are used.

### Keys
Another part of the management of APIs involves issuing keys for each consumer. All APIs require keys to access them and each consumer of an API should require a key. Keys can be given access to one or many plans, and can be reported upon individually, providing a handful of actions when it comes to managing key access of API resources.

- **Get All Keys** - Gets all the keys available in the API Gateway for use across Apis.
- **Get Single Key** - Gets a single key that is setup as part of the gateway and has access to aPIs.
- **Create New Key** - Creates a new key for accessing APIs by a consumer.
- **Get Usage Plan Keys** - Gets all of the keys associated with a specific plan that is setup.
- **Add Security Key** - Add a security object for each HTTP method in the API.
- **Add Security Definition** - Add a security definition to the API.

Key management is essential to securing API resources, but also establishing the awareness required to strike a balance between how available or unavailable an API is to consumers. API key management is the key to the value being made available via many different APIs and their individual paths and methods, ensuring that there is no friction for those who should have access, and zero access for those who shouldn’t.

### Logging (AWS Cloud Trail)
Each API should have its own logging strategy, making sure all access of an API is logged and audible. Centralizing all activity across the operations of each API so that it can be used to improve the quality of service, secure all resources, and make sure that APIs are all visible. Providing a suite of actions that can be taken to manage the logging of APIs being evolved as part of the API life cycle.

- **Get Trails** - Gets all of the log trails that are available.
- **Get Trail** - Gets a single log trail for the API being managed.

This should contain logs for every component in the API delivery chain, ideally providing visibility into every layer of the stack. Providing a complete history of everything that happens with an API, establishing a trail of how it is access and used across all applications. Ensuring there is audibility and accountability consistently cross all available API resources.

## Encryption
Each API should have encryption enabled by default. No APIs should accessed without encryption. Ensuring that all API resources are secured in transport, but also potentially expanded to data at rest, as well as in transport. Providing a suite of encryption related actions that can be taken as part of the management of this API across all stops along the API life cycle.

- **List CloudFlare Certificates** - Gets all of the available CloudFlare certificates.
- **List AWS API Gateway Client Certificates** - Lists all of the available certificates registered with gateway.
- **Generate Client Certificate** - Produce a new client certificate for use as part of this API.
- **Get AWS API Gateway Client Certificates** - Gets a single client service registered with the gateway.
- **Delete AWS API Gateway Client Certificates** - Deletes a certificate registered with the gateway.

Certificate management is critical to API security. Ensuring that encryption is default across everything and valuable resources are secured in transit and on disk. Laying a solid foundation for how APIs are accessed and put to use. Making sure encryption by default is the standard way of doing business across all APIs, and certificates are managed with this philosophy in mind.

## DNS
Each API can be worked with using its development, staging, or production gateway URI, but then an added layer of publish DNS is used to further manage accessibility of each API resource. Strategically managing the base of each URI that is assigned to resources being made available via APIs, and adding another layer for managing traffic and understanding access.

- **All Zones (CloudFlare)** - Gets all available DNS zones from Cloudflare.
- **DNS Records (CloudFlare)** - Gets all available DNS records from CloudFlare.
- **Domain Names (AWS API Gateway)** - Gets a List of domain names registered with gateway.
- **Domain Name (AWS API Gateway)** - Pull a single domain name registered with the gateway.

DNS is the frontline of all APIs that are being deployed. The API management layer will decide who has access to each API, and DNS will provide the necessary addressing for being able to find each API using the web. DNS can be used to further organize how APIs are delivered and accessed, making API infrastructure scalable and more resilient across applications.

## Portal (GitHub)
Each individual API will use its own GitHub repository as a portal to the world, providing a single place where everything about an API can be accessed. While also making sure each API is also published and accessible via other aggregate portals where APIs are accessed by consumers. Making for a suite of actions that can be used to ensure all APIs being managed are accessible by the target audience.

- **Update README** - Updates the README for the API portal repository.
- **Register Home** - Register the API with the master home portal for organization.

Each API should have its own portal, acting as a single doorway for engaging with each API. Each API should also be accessible via multiple where it is published alongside other complimentary APIs. Providing additional doorways for consumers to engage with each API published via localized portals meeting different needs of an organization, partners, and the public.

## Documentation (Postman)
Every API should have documentation available fore each stage of its evolution, providing development, staging, as well as production documentation that is generated from a collection derived from the central API source of truth. Providing a set of actions that can be used to make sure documentation is always part of the process when it comes to moving each API forward.

- **Set Development Documentation URL** - Publish the URL for the documentation that has been published for use as part of the development of an API.
- **Set Staging Documentation URL** - Publish the URL for the documentation that has been published for use as part of the staging of an API.
- **Set Production Documentation URL** - Publish the URL for the documentation that has been published for use as part of the production of an API.
- **Update README with Documentation** - Publish the URLs for documentation for al stages to the README portal for the API being managed.

Documentation for all APIs should always be up to date and accessible by consumers. Making sure there is human readable documentation detailing the entire surface area of each API being made available via an organization. Documentation is always the number one pain point for developers, and it should be something that is consistently invested in, published, and made available as part of all API operations.

## Road Map (GitHub)
Each API should have a road map for defining what the future hold for each API. Providing a list of features that will be added to each API, helping API consumers understand what the future holds, and the feature they can expect when it comes to the evolution of each API. Providing a set of actions that can be taken when it comes to managing the road map for each API.

- **All Road Map Items** - Pull a list of all of the API road map items.
- **New Road Map Item** - Adding a new item to the APIs road map.
- **Single Road Map Item** - Pulling a single road map item for an API.;

A road map should alway be up to date and provide as much details about what will be happening, going as far into the future as an API provider is willing to go. Being as transparent as possible when it comes what the future plans are for each API. Ensuring that all consumers have a heads up on what changes will be coming when it comes to the APIs they depend on.

## Change Log (GitHub)
In addition to a road map there should be a log of every change made to an API, taking everything that is planned as part of the road map, and adding it to the change log once it has been completed. Providing a continual stream of what features are being added, and the timeline in which they were implemented, providing a variety of actions that can be taken to manage the change log.

- **All Change Lot Entries** - Gets all of the change log entries that have been made.
- **New Change Log Entry** - Adds a new entry to the change log, providing detail of what has happened.
- **Single Change Log Entry** - Gets a single change lot entry that has been entered.
- **Close Change Log Entry** - Closes a change log entry so it no longer shows on the log.

The change log should provide an honest look at what has happened to each API, providing accountability when it comes to the evolution of each API, sharing all details with stakeholders, and making it available via the APIs portal. Providing a single place to understand what has happened to each API, which is accessible via all stakeholders involved with each API.

## Issues (GitHub)
Any known issues for an API should be published as part of a central issue log, providing visibility into what is happening with each API, while helping reduce the number of support requests needed to address known issues. Providing a set of actions that can be used when it comes to actively managing issues that are impacting the operation of each aPI.

- **All Issues** - Gets all issues for the API being managed.
- **New Issue** - Adds a new issue for the API being managed.
- **Single Issue** - Gets a single issue for the API being managed.
- **Close Issue** - Closes an issue that is available for the API.

Actively managing issues as part of the road map and change log allow for more consistent management of the issues that will inevitably occur via each API. Providing a consistent way for managing issues across many APIs, and being more transparent when it comes to what issues are occurring that will impact consumers.

## Support (GitHub)
All APIs need to be equally supported, ensuring that consumers receive the support they need to be successful. Whether email, ticketing, or other mechanism there should be a handful of actions available to manage the support needs of each API that fits well with overall strategy across all of operations.

- **All Tickets** - Gets all support tickets that have been submitted via GitHub issues.
- **Single Ticket ** - Gets a single ticket that has been submitted as a GitHub issue.
- **New Ticket** - Creates a new ticket for a problem or feedback using GitHub issues.
- **Close Ticket** - Closes out a ticket signaling it has been satisfied using GitHub issues.

Ideally all of support is API-driven or via common email channel, allowing for support to operate across many different APIs, with each API owner or group of owners to step in and help support their resources. Ensuring that there are no islands or gaps I how APIs are support across teams.

## Communication
There should be a collective communication strategy that exists across all teams and APIs developed, requiring developers to provide updates via a common channel about what is happening with their services. These updates can then be syndicated and published to other channels, Providing a range of actions that can be taken by API developers at different stages of the API life cycle.

### Updates
Providing a low friction way for developers to quickly publish updates about what is happening with an API, ensuring there is a regular stream of information coming out about what is changing with an API. Providing a regular heartbeat of activity, and a handful of channels for managing regular API updates.

- **Get Updates** - Get all of the updates for an API using GitHub Issues.
- **Get Update** - Get a single update for an API using Github Issues.
- **Modify Update** - Apply changes to an update using GitHub issues.
- **Add Update** - Creates a new update for an API using GitHub Issues.

Updates can be monitored, aggregated, and even syndicated to increase the reach of each APIs update system beyond what each team or individual developer is required to do as part of their regular updates. Providing a wider reach for the communication around each API, and the wider organization.

### Twitter
Because Union Fashion and it’s APIs are a very public affair, there is a dedicated Twitter account is available for the platform, providing another stream when it comes to providing updates around each of the API published as part of the platform. Providing a handful of actions that can be used as part of the wider API communications strategy.

- **Tweet** - Sends a new Tweet using Twitter.
- **Twitter Tweet Search** - Searches for tweets on Twitter.
- **Twitter User Search** - Searches for users on Twitter.

Twitter is an important channel for publishing regular updates about what is happening on the platform, keeping consumers and other stakeholders up to date on what is happening, leveraging 3rd party APIs to help get the word out about what is happening via the platform.

## Testing
The entire surface area of the API should be tested using a variety of approaches. Providing a complete as possible suite of modular tests that can be manually or automatically applied across operations by different stakeholders. There are a handful of actions that can be taken when it comes to the testing of the API being moved forward.

## Status Codes
Looking for consistent status codes across resources, ensuring that APIs are meeting the baseline HTTP requirements for all API infrastructure, being consistent in how the web is used to make API resources are available.

- **Test for 200 on GET** - Make sure all GET requests have tests for 200 status code.
- **Test for Valid Schema on 200** - Is there a valid schema being returned for successful calls.
- **Test for 204 on POST, PUT, DELETE** - Make sure all POST requests have tests for 204 status code.

## Management
Postman provides some interesting ways to manage how testing is conducted across API operations, providing some actions that can be taken to make sure testing is more consistent at scale across teams and APIs.

- **Backup Scripts** - Loop through all collections and backup scripts to GitHub.

The ultimate goal of this testing is to ensure that as much of the definition for this API is accounted for, as well as the different behaviors and actions that end-users will be taking are accounted for. Ensuring that all the objectives behind delivering an API are regularly evaluated as part of the API life cycle, and regular operations.

## Performance
The entire surface area of the API should be tested using a variety of approaches. Providing a complete as possible suite of modular tests that can be manually or automatically applied across operations by different stakeholders. There are a handful of actions that can be taken when it comes to the testing of the API being moved forward.

### Status Codes
Looking for 200 status codes with a record of performance for root level resources, ensuring that an API is able to respond to consumers in a timely manner and meet SLAs that are set by teams and agreed upon with customers.

- **Test for 200 on GET** - Make sure all GET requests have tests for 200 status code.

Performance should be monitored from multiple regions, providing the basic level of heartbeat monitoring from any relevant region to customers. Recoding the response time for each API, so that the performance of each API can be evaluated, allowing for the determination of whether an API has met its SLA.

## Security
Security of each API should be approached in a consistent way, making sure the entire surface area of each API is adequately secured. Providing a suite of actions that can be taken to help realize the security needs of each aPI being managed.

- **SQL Injection** - Apply a SQL inject request across all APIs.
- **Add Security to Methods** - Make sure each of the methods have a security method.
- **Add Security Definition** - Ensure the OpenAPI has a security definition.

Security should be expanded based upon a strategic approach to applying security to each API as it is being de eloped, and moved forward across the API life cycle. Applying security, but also recording that it has been consistently applied across teams and APIs.

## Monitoring
Each API should have a set of monitors established for making sure an API is responsive at a basic level. Making sure each API is up and responding at the most basic level, with testing going deeper There are a handful of actions that can be taken when it comes to the monitoring of the API being moved forward.

- **List all Monitors** - Make sure all GET requests have tests for 200 status code.

While testing will use Postman monitors to evaluate the quality of service across APIs, this section is meant to provide the basic level uptime monitoring to ensure services are available. Notifications from these monitors can go to a wider audience than individual tests which will provide specific developers with what they need to further understand the health of APIs.

## Discovery
Each API should be made discoverable by default, regularly publishing artifacts and resources to its central repository, maintaining all artifacts via a common workspace. Making sure each API is available to all technical and business stakeholders via common channels in both a human and machine readable, providing a handful of actions that can be taken to help address discovery.

- **Update APIs APIs.json** - Updating the APIs.json index for each individual API.
- **Update Org APIs.jon** - Updating the APIs.json include index for entire organization.

All of the artifacts used as part of this API life cycle all contribute to discover, providing machine readable definitions for the API and every stop along the life cycle. Then rolling it all up into a single machine readable index that can be used to fully understand what each API offers and how it is being used.

## Deprecation
Every version of an API will eventually be deprecated, requiring a common set of actions that can be used to properly plan, communicate, and execute the deprecation of each API in operation.

- **Set Sunset HTTP Header** - Apply the Sunset HTTP header to the API being managed.
- **Add Deprecate Date to Road Map** - Add the date of deprecation to the road map for the API.

Deprecation should be considered as soon as the first version of an API is ready. Leveraging a standardized approach to bringing APIs to life as well as to close them down, making sure there is always a plan for how APIs will be shut down.

## Conclusion
The Union Fashion API life cycle is not a linear set of steps that everyone will be executing in the same order. It is meant to be a comprehensive list of steps that MAY be taken, and can be used as part of smaller cycles to achieve specific outcomes when it comes to the evolution of each API.
