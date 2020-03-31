# Union Fashion

## Why?
<img src="https://avatars0.githubusercontent.com/u/61293199?s=200&v=4" align="right" width="250">
Currently we have no way of showcasing Postman as a complete platform. We may talk about individual features, or a specific flow of features that contribute to a practice such as automated testing.

By creating a demo company, this allows us to configure an instance of Postman in a best practice way, showcasing how the platform can be used for API development in an end-to-end fashion.

Union Fashion aims to be a fully blown demo company with organizational structure, teams, roles and how they interact with Postman visible. This will allow for a prospect to drop into the demo instance and understand how they could be working/what they should be working towards.

Everyone is familiar with the e-commerce example and how a website/app selling fashion items would work, hence the selection in this instance.

Using a demo space is key to this as it allows us to show Postman working in the real world, and brings our story/slides/pitch to life with a real world use case.

## Overview

Union Fashion is an online-only fashion retailer looking to disrupt the fashion market. Their products appeal to fashionistas and their online experience is at the heart of how they’d like to push the boundaries and become a market leader.

To create a distinct, bleeding edge website and app experience, Union Fashion will be harnessing some of the latest tech. Inevitably, this creates a reliance on both consuming and authoring their own APIs.

Management at Union Fashion understand and have bought into the API first approach. They know that Postman can help design and develop APIs which are more consistent, reliable and reusable than APIs of old.

Union are not only looking to power their themselves through use of an API first approach, but what makes their business unique is that they will be allowing independents, boutiques and small businesses the opportunity to sell their products through Union Fashion in a way indistinguishable from Union’s own product lines.

## Organizational Structure

Before diving into and explaining Union Fashion it’s important to understand the structure of the business and the requirements of key stakeholders/teams who will be defining and delivering the APIs that drive Union Fashion.

- **Robert Brown, Chief Executive Officer** - Looking for a good methodology to be followed on the technical front. Keen to ensure tech used within Union Fashion is consolidated. Wants to use company’s relative small size to ensure they are agile, early adopters and are providing a marketing leading online/app experience.
- **Jeff Jones, Vice President Engineering** - Looking for a solution which will help with a modern microservices approach. Knows that an individual, autonomous approach will mean their APIs are easy to integrate and reuse. Looking to solve the collaboration aspect between teams to ensure all engineering teams can depend upon each others solutions reliably.
  - **Susan Todd, QA Lead** - Looking to ensure integrity across all Union’s systems. Wants to be able to create integrated testing flows to join up the work of front/back end teams to verify end use cases as well as test parts of the system in isolation. Needs a CI solution and a way to monitor these flows.
    - Team 3 QA engineers
  - **Alex Wood, Front End Lead** - Alex would like to avoid several typical scenarios: handover of APIs from front to back end being complicated - outdated documentation, old versioning. For new developers joining the team Alex needs them to be able to consume and start working with their APIs right away. Looking to have input on the tests for APIs ensuring they meet their use cases moving forward.
    - Team 10 FE engineers
  - **Kim Oliver, Back End Lead** - Kim would like her team to spend more time building and progressing their roadmaps than worrying about documentation, debugging issues with the front end team and would like to ensure a consistent approach to how new APIs are developed and made available for the business.
    - Team 6 BE engineers
- **Holly Statham, VP Sales**  - Shared objectives of being able to demonstrate how easy Union’s APIs are to pick up and use through both demos and sales material. Having access to source of truth.
  - Team 3 sales representatives
- **Tom Hill, VP Sales** - Shared objectives of being able to demonstrate how easy Union’s APIs are to pick up and use through both demos and sales material. Having access to source of truth.
  - Team 6 marketing

## Services
These are the initial services being developed to support Union Fashion business operations, providing the core digital services needed to sell products to our customers, and support our on and offline business operations.

- **Products** - ([Repo](https://github.com/union-fashion/products)) ([Docs](https://documenter.getpostman.com/view/10394726/SzS2xojt?version=latest)) - Defining all of the products that Union Fashion offers.
- **Orders** - ([Repo](https://github.com/union-fashion/orders)) ([Docs](https://documenter.getpostman.com/view/10394726/SzYXXzLu?version=latest)) - Allows for the ordering of Union Fashion products online.
- **Baskets** - ([Repo](https://github.com/union-fashion/baskets)) ([Docs](https://documenter.getpostman.com/view/10394726/SzYXXzVh?version=latest)) - Allows for the ordering of Union Fashion products online.
- **Users** - ([Repo](https://github.com/union-fashion/users)) ([Docs](https://documenter.getpostman.com/view/10394726/SzYXXzaC?version=latest)) - Defines users who engage with the Union Fashion platform.
- **Search** - ([Repo](https://github.com/union-fashion/search)) ([Docs](https://documenter.getpostman.com/view/10394726/SzYXXza6?version=latest)) - Provides a universal search for products, orders, and users.

Additional services will be defined and added to the list as part of future planning sessions. This provides the base foundation for the Union Fashion platform, driving web, mobile, device applications, as well as other integrations.

## Planning
This project is a work in progress, with the following planning efforts on the table. You can join in via submitting GitHub issues via this repository, or for any of the individual services being developed.

- [Initial Planning](planning/initial-planning.md) - Getting the ball rolling with an API-first approach to development.
  - [Build & Test Planning](planning/build-and-test-planning.md) - In planning phase currently, determining the process for how we will be building and testing our infrastructure.
  - [Deploy & Monitor Planning](planning/deploy-and-monitor-planning.md) - In planning phase currently, shaping how each team will be delivering their API infrastructure across the organization.
  - [GTM & Sustainment](planning/go-to-market-and-sustainment.md) -In planning phase currently, and helping make sure we have a formal approach to how we are going living with our infrastructure.
- [Website](http://union.fashion) - We need a website for union fashion that is API-first, helping make sure we are using our own APIs for all aspects of the Union Fashion operations, and they are not just a side project.
- [Twitter](unionfashionapi) - We have a Twitter account, we need a strategy for using it as part of the operation of the API and the business they drive

We are in the initial planning stages for Union Fashion's digital transformation, and move to an API-first way of doing business, allowing the business to operate more as an online platform, going beyond traditional e-commerce.

## API Platform
Union Fashion employs a platform approach to building APIs, establishing an organizational wide set of infrastructure, services, tooling, and blueprints for ensuring that all APIs have the resources they need, no matter which part of the organization they come from. Providing a common approach to delivering APIs by ensuring all teams have the same platform to operate on at every stage of the API life cycle.

### Infrastructure ([Details](/platform/infrastructure.md))
To support API operations at Union Fashion, we are using the following infrastructure to define, deliver, and sustain APIs throughout the course of their life. Standardizing the services and tools we use across all teams at Union Fashion, and helping to guide new hires, as well as those who find their way to our organization via acquisitions, helping make sure everyone is on the same page when it comes to delivering APIs at Union Fashion.

- **Postman** - We use Postman as our API life cycle manager, helping deliver on a variety of stops along the life cycle for each API, and orchestrate how everything works using APIs.
- **GitHub** - We use GitHub as the underlying workspace for each API, working in sync with Postman workspaces to make the core definition of each API available across the entire life cycle.
- **AWS API Gateway** - All internal, partner, and public APIs are published using the AWS API Gateway, providing a constent management layer across all APIs being delivered.
- **AWS DynamoDB** - For simpler data APIs we are using AWS DynamoDB for the persistent data storage behind APIs, allowing for simple NoSQL data storage for each individual APIs.
- **AWS RDS Aurora** - For more complex data APIs we are using AWS RDS Aurora for persistent storage behind APIs, allowing for more complex relational data storage for each API.
- **AWS Lambda** - For the serverless compute layer for many APIs we are using Lambda as the scalable power behind each API, allowing us to scale APIs at the most atopic level.
- **AWS S3** - Using AWS S3 for the storage of all images, videos, documents, and other heavy objects that are made available via Union Fashion APIs, giving each API it's own object store.
- **AWS Cloudtrail** - We are using AWS CloudTrail for the logging layer behind each API, gathering the exhaust of the database, storage, compute, and gateway layers of the APIs.
- **CloudFlare** - We are using CloudFlare as the DNS and certificate provider behind Union Fashion, providing addressing and encryption for all of the APIs being delivered.

This represents all of the infrastructure currently in use across APIs. Teams are not restricted to using just these infrastructure components, but they are required to submit a GitHub issue request the usage of a new service or tool, and making sure it is added to this list before an API moves into production. Visit the platform infrastructure page for more details on how this infrastructure is being used, and our general philosophy when it comes to delivering APIs at Union Fashion.

## API Life Cycle ([Details](/life-cycle.md))
Union Fashion employs a standard approach to the life cycle of each API, applying a consistent approach to the delivery, sustainment, and deprecation of APIs across operations.

- **Define** - Providing guidelines for how APIs should be defined.
- **Design** - Training and guidance about how to design APIs.
- **Mocking** - The ability to mock an API to assist in it's delivery.
- **Documentation** - Always having consistent up to date documentation.
- **Database** - Ensuring there is always persistent data storage.
- **Storage** - Providing a place to put objects as part of API operations.
- **Compute** - Having the appropriate amount of compute behind each API.
- **Deployment** - Making sure that APIs are deployed in repeatable ways.
- **Management** - Ensuring that every API is being managed consistently.
- **Encryption** - Always making encryption the default response across APIs.
- **DNS** - Having a strategy for how DNS is handled across groups and APIs.
- **Portal** - Ensuring there is always a doorway to get at all APIs.
- **Support** - Requiring there be support for every API being operated.
- **Communications** - Having consistent communication in place for APIs.
- **Testing** - Providing a consistent approach to testing all APIs.
- **Performance** - Looking specifically at the performance of each API>
- **Security** - Scanning and auditing the security landscape for each API.
- **Monitoring** - Having monitors on a schedule ensuring the quality of APIs.
- **Deprecation** - Making sure there is a plan for how all APIs will be sunset.

You can view [the details for the Union Fashion life cycle](/life-cycle.md), and run the API life cycle collection within any workspace for managing an API--using the collection as guardrails and checklist for the entire API life cycle.

# Governance ([Details](/governance.md))
All Union Fashion APIs are governed to ensure consistently and a quality of service across all the APIs coming from distributed teams. Providing consumers with a smoother experience across all of the APIs we are making available internally, to partners, and with the general public.

- **Definition** - The guidelines in place when it comes to defining each API.
- **Design** - The guidelines in place for helping design better APIs.
- **Mocking** - Looking at how mocking is used across the API life cycle.
- **Development** - Helping standardize how APIs are being developed.
- **Staging** - Providing a staging environment for each iteration of an API.
- **Production** - Standardizing how APIs are made available in live environment.
- **Licensing** - Looking at the licensing of each API and it's support resources.
- **Reporting** - Reporting on governance for each API, providing an overview.

You can [view the details for the governance of Union Fashion APIs](/governance.md), and run the API governance collection within any workspace, helping apply common governance practices to each API. Helping enforce how APIs are being defined and delivered, offering up a consistent Union Fashion experience for all API consumers.

## Philosophy
Union Fashion is intended to be a reference implementation showing how to deliver APIs across the a business implementation most readers will find relatable. Our goal is to do as much of the work on Union Fashion out in the open using GitHub and Postman so that others can follow along. Using Union Fashion as a live sandbox for driving the API-first conversation, helping us center our efforts on a single point of reference across storytelling, workshops, webinars, and other channels.

## Support
If you have any questions or comments you can [submit a GitHub issue for this repository](https://github.com/union-fashion/home/issues), or email [mail@union.fashion](mailto:mail@union.fashion) for a more private channel of discussion. If there are tasks to be accomplished, go ahead and add as an issue, and either complete it yourself, or leave open for assigning to someone else.
