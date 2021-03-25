# Open Source Workflow

Workflow to follow in order to **Open Source** a library or an application.

## Why a workflow

This workflow help to align all the actors of an entity on the same objectives.

whithout a workflow :
![Why a workflow](./images/why-workflow-1.png)

with a workflow :
![Why a workflow](./images/why-workflow-2.png)

# 1) Prerequisites

- No business rule specific to AXA
- Code quality & practices
  - At least 60% of code coverage
- CI (Continuous Integration) with all the internal tools
- License: [MIT](https://github.com/AxaGuilDEv/react-oidc/blob/master/LICENSE)
  - please note that you have to "Copy/Paste" the licence text because it has to specify the entity "AXA France IARD / AXA France VIE"
- Mandatory files : README.md, CONTRIBUTING.md, CODE_OF_CONDUCT.md, LICENCE.md, CHANGELOG.md, Templates : Issues, PR
- At least one “Repository Maintainer“


![Workflow step 1](./images/workflow-step1.png)

# 2) Validations

- Technical director of the entity
- Communities of practice:
  - Security
  - Software Craftmanship

![Workflow step 2](./images/workflow-step2.png)

# 3) Team/Maintainer Must

- Use and force two factor Authentication everywhere it is possible: github, npm, nuget, etc.
- Tokens must be kept private
- Set up and maintain CI / CD
  - use https://dev.azure.com/axaguildev
  - use https://sonarcloud.io/organizations/axaguildev
- Manage the roadmap
- Manage “Issues” and “PullRequests”
- Help to grow the community

![Workflow step 3](./images/workflow-step3.png)

# 4) Mentality

- Going Open Source brings and requires a change of mentality within development teams.

![Workflow step 4](./images/workflow-step4.png)
