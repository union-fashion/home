# Bringing Your API to Market

This is an outline for phase one of producing four separate services to drive Union Fashion, using an API (design) first strategy. This phase is actually about bringing services to market and supporting their actual usage. This is meant to act as a guide for the actual work, as well as conduct a webinar for enterprise customers.

- **Management**
  - **Gateway** - We are using AWS API Gateway for the management layer of our APIs.
  - **Logging** - We are using AWS CloudWatch for the logging layer of our APIs.
- **Authorization**
  - **3rd Party Token** - We are allowing GitHub, LinkedIn, Facebook, and Twitter auth.
  - **API Gateway** - We exchange 3rd party tokens for AWS API gateway keys.
- **Portal**
  - **Platform** - Publish static developer portal using GitHub Pages and Jekyll.
  - **Resources** - Provide as many resources for developers to help them get started.
  - **On-Boarding** - Make it easy for developers to on-board with the APIs easily.
- **Documentation**
  - **Published** - Ensure all documentation is accessible to the targeted groups.
  - **Artifacts** - Provide a wealth of artifacts that help consumers quickly use APIs.
  - **Environment** - Ensuring all environments are accessible to targeted groups.
- **Monitors**
  - **Scheduled** - We have ongoing monitors operating on a regular schedule.
  - **Results** - Review and stay in tune with monitor results for each service.
  - **Service Level Agreement** - Are we meeting our service level agreement?
- **Reports**
  - **Team Overview** - Tune into what each team is working on and moving forward.
  - **Service Details** - Tune into reports for each of the individual services.
  - **Contract Tests** - Providing current contract testing results via README report.
  - **Performance Tests** - Providing current performance testing results via README report.
  - **Security Tests** - Providing current security testing results via README report.
- **Communication (Marketing)**
  - **Blog Post** - Publish an internal, partner, or public blog post for releases.
  - **Social** - Publish release message via internal, partner, or public social channels.
  - **Support** - Supporting API consumers via email and GitHub issues for the repository.
- **Discovery**
  - **APIs.json** - Each API has an APIs.json index that is used to register it with portal(s).
  - **GitHub** - Each API is available on GitHub using repositories making it discoverable.
- **Feedback Loop**
  - **Email** - Send direct email to stakeholders letting know service is available.
  - **Comments** - Tune into comments available for each service.
  - **Issues** - Tune into GitHub issues for each service.

If you'd like to get involved, please assume an existing persona, or add a new persona using the organizational structure on the README. Then submit GitHub issues with your feedback, or feel free to go ahead and submit a pull request for this page in the repo. We are working to keep as much of the process available via the public repository as we we possibly can, being transparent and observable in how Union Fashion comes together.
