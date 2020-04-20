# Deploy & Monitor Planning

This is a draft outline for phase one of producing four separate services to drive Union Fashion, using an API (design) first strategy. This phase is actually about delivering a real API behind each four of these services. This is meant to act as a guide for the actual work, as well as conduct a webinar for enterprise customers.

## Versioning

* **API Version** - Making sure to iterate the version of each API and derivative collection, managing change across APIs.
* **Version Tag** - Applying vision tagging to each of the collections associated with the API being moved forward.
* **Change Log** - Evaluate change log activity for each service, making sure you are in tune with what has been happening across an API.
* **Sync** - Ensure that latest version is synced to GitHub, keeping all changes made in Postman or on GitHub reflected in both locations.

## Actual Deployment of Each API

* **Basic NoSQL (AWS)** - Providing a standardized and repeatable way to deploy basic NoSQL backed API resources.
    * **OpenAPI** - Leveraging the OpenAPI contract to define, prepare, and build each API being deployed.
    * **Table** - Pulling the table name from the schema available as part of the OpenAPI definition from the API.
    * **Publish** - Publishing the OpenAPI definition to the AWS API Gateway, using it as the truth for deployment.
    * **Deploy** - Actually deploying the API published to the AWS API Gateway into a specific stage of development.
* **Serverless SQL (AWS)** - Providing a standardized and repeatable way to deploy basic serverless SQL backed API resources.
    * **OpenAPI** - Leveraging the OpenAPI contract to define, prepare, and build each API being deployed.
    * **Table** - Pulling the table name from the schema available as part of the OpenAPI definition from the API.
    * **Layers** - Pulling and deploying the AWS Lambda layers package needed to satisfy Node.js dependencies.
    * **Scripts** - Dynamically generating JavaScript for each API method that is defined as part of the OpenAPI.
    * **Packages** - Pulling, zipping, and publishing AWS Lambda deployment packages for each OpenAPI method.
    * **Functions** - Deploying the package for each OpenAPI method and publishing individual AWS Lambda functions.
    * **Publish** - Publishing the OpenAPI definition to the AWS API Gateway, using it as the truth for deployment.
    * **Deploy** - Actually deploying the API published to the AWS API Gateway into a specific stage of development.

## Management

* **Usage Plan** - Publishing a usage plan with access limitations defined, governing each API being deployed.
* **API Key** - Generating an API key and associated it with the plan, allowing each API to be securely accessed.

## Environments

* **Stage**
    * **Name** - Publishing of an environment for managing the deployment of the API, naming for the stage.
    * **BaseURL** - Provide a key / value for the base_url , which will be used when deploying and testing of the deployed API.
* **Mock**
    * **Name **- Publishing of an environment for managing the mock for thi API, naming for the stage.
    * **BaseURL** - Provide a key / value for the base_url , which will be used when working with the mock.

## Monitoring

* **Contract Testing**
    * **Name** - Apply name to the monitor matching it with the API and type of testing being implemented.
    * **Version** - Make sure the monitor has the proper version tag applied associated it with current version.
    * **Environment** - Using the proper environment stage for the API contract being tested and monitored.
    * **Schedule** - Applying the required schedule for the monitoring of the API contract testing.
    * **Region** -  Monitoring the contract of each API from the required geographic regions.
* **Performance Testing**
    * **Name** - Apply name to the monitor matching it with the API and type of testing being implemented.
    * **Version** - Make sure the monitor has the proper version tag applied associated it with current version.
    * **Environment** - Using the proper environment stage for the API performance being tested and monitored.
    * **Schedule**** - Applying the required schedule for the monitoring of the API performance testing.
    * **Region** -  Monitoring the performance of each API from the required geographic regions.
* **Service Level Agreement** - Establish benchmarks for contract and performance testing.
    * **Results** - Ensure that the results of contract and performance testing are being stored in the environment.
    * **Publish** - Publishing of contract and performance testing results to the GitHub repository for each API.

## Mocking

* **Deploy** - Establish a mock representation of the current stage, providing a mocked server for this version.
* **Share** - Share the URL of mock server with rest of team, making sure it is know that there is a separate mock.
* **Environment** - Add the mock URL and keys to the environment, ensuring the mocked version can be accessed.

## Documentation

* **Publish** - Publish documentation for each service being developed, making sure the document is up to date.
* **Environment** - Make sure there is an environment available for each stage of an APIs development.
* **Share** - Share the URL of documentation with team members, making sure everyone has the link they need.

## Feedback Loops

* **API Comments** - Tune into comments available for each API, helping keep discussions self-contained for each API being developed.
* **Collection Comments**** - Tune into comments available for each collection, helping keep discussions self-contained for each API derivative.
* **Issues** - Tune into GitHub issues for each service, leveraging the repository issues as public and private communication cycles.

If you'd like to get involved, please assume an existing persona, or add a new persona using the organizational structure on the README for this project. Then submit GitHub issues with your feedback, or feel free to go ahead and submit a pull request for this page in the repo. We are working to keep as much of the process available via the public repository as we we possibly can, being transparent and observable in how Union Fashion comes together.
