# Build & Test Planning

This is a draft outline for phase one of producing four separate services to drive Union Fashion, using an API (design) first strategy. This phase is purely about doing everything prior to actually delivering the API. This is meant to act as a guide for the actual work, as well as conduct a webinar for enterprise customers.

## Organizational

  - **Organization** (Web)
    - Overview - Providing a single organization landing page for all APIs.
    - People - Leveraging GitHub network and authorization to manage team.
  - **Teams** (Web) ([URL](https://cs-demo.postman.co/team))
    - Team Settings - Configure the settings available to each team.
    - Add Users - Add user slots to the team licensing configuration.
    - Search Users - Search for users who are added as a team member.
  - **Team Members** (Web) ([URL](https://cs-demo.postman.co/team))
    - Invite Members - Invite other real world members to the team.
    - Activity - View the team level activity across all members.
  - **Manage Team Roles** (Web) ([URL](https://cs-demo.postman.co/team))
    - Administrators - Manage the users who can make administrative changes.
    - Developers - Establish who the developers on a team are up to date.
    - Audit - Regularly audit the team roles ensuring they are up to date.

## APIs

  - **Workspace** (Desktop) ([URL](https://cs-demo.postman.co/team))
    - Launchpad - Learn about what the desktop launchpad has to offer.
    - APIs - View and manage API definitions using workspace API builder.
    - Collections - View a list of available collections within a workspace.
    - Environments - Environments exist as key / value store for APIs.
    - History - Utilize workspace history to understand what has happened.
    - Filter - Filter collections using the keyword filter text box.
    - Invite -  Be able to invite additional team members to the workspace.
  - **Repository** (Web)
    - Readme - Each API has its own README landing page within GitHub repo.
    - Issues - The repository issues are used for support and communications.
  - **OpenAPI 3.0** (Desktop)
    - Contract - There is an OpenAPI present for all APIs being developed.
    - Versioning - All API definitions are semantically version controlled.
    - YAML - YAML is used for the format of choice for API contracts.
    - ChangeLog - The change log is used understand the evolution of each API.
    - Comments - Conversation around an API uses comments to localize.
    - Reports - API reporting is used to stay aware of API prioritization.
  - **GitHub Sync** (Desktop/Web)
    - Setup - Setting up the two-sync for a specific version of an API.
    - Webhooks - Setup the GitHub webhook for managing two-way sync.
    - Two-Way - Changes to Open API are synced in both directions.
    - Integrations - Leveraging OpenAPI on GitHub for other integrations.
    - Authorization - Rely on GitHub authorization to secure OpenAPI access.

## Collections (Desktop)U

  - Requests - Definite each API method as an individual API request.
  - Examples - Ensuring that each request has at least one example.
  - Folders - Organizing API requests into logical folders for easier use.
  - Generate - Rely on generated collection from an OpenAPI definition when possible.
  - Manual - Work with collections manually to refine and polish approach.
  - Authorization - Have an authorization strategy in place for each collection.
  - Naming - Having a naming strategy for applying across all APIs.
  - Purpose - Ensuring that collections each have a specific purpose in mind.
  - Scope - Work to keep the scope of each collection small and meaningful.
  - Backups - Establish a backup strategy for all API collections in use.

## Environment (Desktop)

  - Development - Utilizing a development environment for each API.
  - Production - Utilizing a production environment for each API.
  - Naming - Employing a naming strategy for all environments.
  - Base URL - Publish the base URL for each API and its environment.
  - API Keys - Store keys, tokens, and other secrets in environments.
  - Key / Value - Use environments for other needed key / value pairs.
  - Backups - Regularly backup environments locally and to other workspaces.

## Mocks (Desktop)

  - Deploy - Publishing a new mock server from an existing collection.
  - Naming - Having a naming strategy for how mocks are named.
  - URL - Pulling, copying, and applying the mock URL for each server.
  - Share - Sharing a mock server URL with other users.
  - Environment - Publishing the mock URL to the appropriate environment.
  - Validation - Validating the collection behind the mock against OpenAPI.

## Documentation (Desktop/Web)

  - Publish - Publishing documentation from a collection.
  - Environment - Associate an environment with the documentation.
  - Styling - Apply styling to the API documentation.
  - Custom Domain - Utilize a custom URL for the documentation.
  - Share Workspace - Make the documentation available in other workspaces.
  - Share URL - Publish the URL to the documentation.
  - Run in Postman Button - Embed the run in Postman button elsewhere.
  - Discovery - Make sure documentation is automatically discoverable.
  - Validation - Validating the collection behind the mock against OpenAPI.

## Tests (Desktop)

  - Contracts - Having API contract collections in place for all APIs.
  - Runners - Ensure that contract testing collections are designed for runners.
  - Monitors - Always having at least one monitor running for contract collections.
  - Newman - Employing Newman within existing code pipelines behind APIs.
  - Results - Having a strategy for publishing test results to environment and GitHub.
  - Validation - Validating the contract test collection against the OpenAPI.

## Feedback Loop (Desktop/Web)

  - API Comments - Utilizing the comments for each OpenAPI contract.
  - Collection Comments - Utilizing the comments for each individual collection.
  - GitHub Home Issues - Employing the GitHub issues for the organizational home repo.
  - GitHub Repo Issues - Employing the GitHub issues for each individual API repo.
  - Team Activity - Tuning into the team activity in Postman to understand landscape.
  - Workspace Activity - Tuning into the individual workspace activity across users.
  - Workspace History - Looking at the individual API workspace history of requests.

If you'd like to get involved, please assume an existing persona, or add a new persona using the organizational structure on the README for this project. Then submit GitHub issues with your feedback, or feel free to go ahead and submit a pull request for this page in the repo. We are working to keep as much of the process available via the public repository as we we possibly can, being transparent and observable in how Union Fashion comes together.

## Other Thoughts

- This should be applied to all APIs equally, ensuring coverage.
- This should be implemented as an API design first philosophy.
