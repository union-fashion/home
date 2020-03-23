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

Before diving into and explaining Union Fashion it’s important to understand the structure of the business and the requirements of key stakeholders/teams.

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

- [Products](https://github.com/union-fashion/products) - Defining all of the products that Union Fashion offers.
- [Orders](https://github.com/union-fashion/orders) - Allows for the ordering of Union Fashion products online.
- [Users](https://github.com/union-fashion/users) - Defines users who engage with the Union Fashion platform.
- [Search](https://github.com/union-fashion/search) - Provides a universal search for products, orders, and users.

Additional services will be defined and added to the list as part of future planning sessions. This provides the base foundation for the Union Fashion platform, driving web, mobile, device applications, as well as other integrations.

## Planning
This project is a work in progress, with the following planning efforts on the table. You can join in via submitting GitHub issues via this repository, or for any of the individual services being developed.

- [Initial Planning](planning/initial-planning.md) - Getting the ball rolling with an API-first approach to development.
  - [Build & Test Planning](planning/build-and-test-planning.md) - Needs development.
  - [Deploy & Monitor Planning](planning/deploy-and-monitor-planning.md) - Needs development.
  - [GTM & Sustainment](planning/go-to-market-and-sustainment.md) - Needs development.
- [Website](http://union.fashion) - We need a website for union fashion.
- [Twitter](unionfashionapi) - We have a Twitter account.
We are in the initial planning stages for Union Fashion's digital transformation, and move to an API-first way of doing business, allowing the business to operate more as an online platform, going beyond traditional e-commerce.

## Support
If you have any questions or comments you can [submit a GitHub issue for this repository](https://github.com/union-fashion/home/issues), or email [mail@union.fashion](mailto:mail@union.fashion) for a more private channel of discussion. If there are tasks to be accomplished, go ahead and add as an issue, and either complete it yourself, or leave open for assigning to someone else.
