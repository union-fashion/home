# Planning
This is the initial planning around the next generation of Union Fashion, realizing the platform vision of the company using an API first approach. Allowing us to build, test, deploy, monitor, then go to market and sustain more efficiently across teams.

## Stakeholders
For this discussion we are bringing together four initial stakeholders who will be seeing the design and development of all Union Fashion services throughout the software life cycles.

- Jeff Jones, Vice President Engineering
- Susan Todd, QA Lead
- Alex Wood, Front End Lead
- Kim Oliver, Back End Lead

Susans, Alex, and Kim's teams will be brought into the discussion after this initial meeting, was the platform and scaffolding for how Union Fashion is doing APIs is realized.

## Build & Test
Jeff, Susan, Alex, and Kim are coming together to lay the foundation for the future of Union Fashion APIs. Defining how the API life cycle will be executed, breaking the initial plan into three distinct areas.

### Build & Test
Union fashion is employing an API first approach to delivering all APIs, ensuring there is a well defined API contract present for each of the services being developed.

- Organizational
  - Teams - Configure team settings for our team.
  - Team Members - Add all team members to Postman teams.
  - Manage Roles - Mange the roles for all team members.
  - SSO - Ensure organization structure is using SSO.
  - Workspaces - Setup workspaces for each of the initial four services.
  - Repositories - Setup GitHub repositories for each of the initial four services.
- Schema
  - OpenAPI 3.0 - Publish OpenAPI 3.0 as the central truth.
  - GitHub Sync - Establish sync with GitHub repository.
  - Version - Establish version of APIs being developed.
- Collections
  - Generate - Publish a collection for each service being developed.
- Environment
  - Create - Add a build environment for each service being developed.
  - Variables - Establish key / values need for building each service.
- Mocks
  - Deploy - Establish a mock API for each service being developed.  
  - Share - Share the URL of mock server with rest of team.
  - Environment - Add the URL of the mock to the build environment
- Documentation
  - Publish - Publish documentation for each service being developed.   
  - Share - Share the URL of documentation with team members.
- Tests
  - Contracts - Develop contract tests for each service being developed.   
  - Integration - Develop integration tests for each service being developed.   
- Feedback Loop
  - Email - Send direct email to stakeholders letting know service is being developed.
  - Comments - Leveraging comments for each API as part of wider feedback loop.
  - Issues - Leveraging GitHub issues for each API as part of wider feedback loop.

This build and test scaffolding established by Union fashion leadership provides a repeatable process that teams can apply when defining each of the services that will be needed for the business.

## Deploy & Monitor
With a proven contract, the API leadership team wants to ensure there is a logical deployment strategy for bringing each service to life in a consistent way. The leadership team is relying on each service development team to propose how each API will be deployed, but require the following exist as part of the deployment process.

- Version
  - Increment - Iterate the version of each API and derivatives.
  - Sync - Ensure that latest version is synced to GitHub.
  - Change Log - Evaluate change log activity for each service.
  - Publish - Publish change log to GitHub repository.
- Monitor
  - Setup - Add a new monitor for each services collection.
  - Service Level Agreement - Establish benchmarks for service levels.
  - Schedule - Establish the schedule for each service monitor.
- Mocks
  - Deploy - Establish a production mock API for each service being developed.  
  - Share - Share the URL of mock server with rest of team.
- Environment
    - Create - Add a production environment for each service being developed.
    - Mock URL - Ensure environment has up to date mock URL.
    - Production URL - Ensure environment has up to date production URL.
- Documentation
  - Publish - Publish documentation for each service being developed.   
  - Share - Share the URL of documentation with team members.
- Feedback Loop - Stay in tune with the change log for each API.
  - Email - Send direct email to stakeholders letting know service is being deployed.
  - Comments - Tune into comments available for each service.
  - Issues - Tune into GitHub issues for each service.

This is an initial plan for the deployment and monitoring of each service. As part of future planning for API deployment a pipeline plan will be proposed by each team, resulting in further guidance regarding how each contract is actually brought to life.

## Go To Market & Sustainment
With each service deploy, a consistent approach to going to market and sustaining each API is required. Providing a common approach to how APIs can be made available internally, amongst partners, and to the general public. Ensuring each individual service is well defined, observable, and are active in the following ways.

- Documentation
  - Access - Ensure all documentation is accessible to the targeted groups.
  - Environment - Ensuring all environments are accessible to targeted groups.
- Validation
  - Mocks - Ensure mock is in alignment with production OpenAPI truth.
  - Documentation - Ensure documentation is in alignment with production OpenAPI truth.
  - Tests - Ensure tests are in alignment with production OpenAPI truth.   
- Monitors
  - Results - Review and stay in tune with monitor results for each service.
  - Service Level Agreement - Are we meeting our service level agreement.
- Reports
  - Team Overview - Tune into what each team is working on and moving forward.
  - Service Details - Tune into reports for each of the individual services.
- Communication (Marketing)
  - Blog Post - Publish an internal, partner, or public blog post for releases.
  - Social - Publish release message via internal, partner, or public social channels.
  - Newsletter - Share release information via target audience newsletter.
- Feedback Loop
  - Email - Send direct email to stakeholders letting know service is available.
  - Comments - Tune into comments available for each service.
  - Issues - Tune into GitHub issues for each service.

This should provide a base for what is needed to take each Union Fashion service to market, meeting internal, partner, and public needs. Further details will be fleshed out by each team in future planning sessions, providing more detail about how teams will actually be sustaining each of the services in a production state.

## Conclusion
This initial planning is designed to establish the scaffolding for what is needed to satisfy leadership requirements when it comes to delivering each Union Fashion service. It is up to Susan, Alex, and Kim to further flesh out what teams will need when it comes to the building, deploying, and sustainment of each Union Fashion service, which will be defined via three separate future planning sessions that will flesh out the details of each area.

Jeff, Susan, Alex, and Kim will be meeting to further discuss this API-first build, deploy, and sustain strategy. Then schedule separate team meetings for each of the stages of development, providing further opportunity for teams to contribute their feedback, needs, and concerns regarding the API-first strategy for delivering API infrastructure at Union Fashion, providing the platform for all web, mobile, device, and integration needs of the business.
