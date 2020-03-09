# Deploy & Monitor Planning

This is a draft outline for phase one of producing four separate services to drive Union Fashion, using an API (design) first strategy. This phase is actually about delivering a real API behind each four of these services. This is meant to act as a guide for the actual work, as well as conduct a webinar for enterprise customers.

- **Version**
  - **Increment** - Iterate the version of each API and derivatives.
  - **Sync** - Ensure that latest version is synced to GitHub.
  - **Change Log** - Evaluate change log activity for each service.
  - **Publish** - Publish change log to GitHub repository.
- **Develop**
  - **Database** - What database are we using for persistent storage (ie. DynamoDB, RDS, other?)
  - **Compute** - What compute are we using for APIs (ie. EC2, Lambda, other?)
  - **Language** - What programming language are we using? (ie. Node.js, Go, Fortran, other?)
  - **DNS** - I'm currently using ClouFlare for DNS, but can be easily switched.
  - **Pipeline** - What are we using for CI/CD (ie. GitHub Actions, Jenkins, other?)
- **Monitor**
  - **Setup** - Add a new monitor for each services collection.
  - **Service Level Agreement** - Establish benchmarks for service levels.
  - **Schedule** - Establish the schedule for each service monitor.
- **Mocks**
  - **Deploy** - Establish a production mock API for each service being developed.  
  - **Share** - Share the URL of mock server with rest of team.
- **Environment**
    - **Create** - Add a production environment for each service being developed.
    - **Mock URL** - Ensure environment has up to date mock URL.
    - **Production URL** - Ensure environment has up to date production URL.
- **Documentation**
  - **Publish** - Publish documentation for each service being developed.   
  - **Share** - Share the URL of documentation with team members.
- **Feedback Loop** - Stay in tune with the change log for each API.
  - **Email** - Send direct email to stakeholders letting know service is being deployed.
  - **Comments** - Tune into comments available for each service.
  - **Issues** - Tune into GitHub issues for each service.

  If you'd like to get involved, please assume an existing persona, or add a new persona using the organizational structure on the README for this project. Then submit GitHub issues with your feedback, or feel free to go ahead and submit a pull request for this page in the repo. We are working to keep as much of the process available via the public repository as we we possibly can, being transparent and observable in how Union Fashion comes together.

  ## Other Thoughts

  - The name of this phase can change.
  - The outline was thrown together quickly for a webinar should change.
  - We need everything that will be needed to deliver a real API listed here.
