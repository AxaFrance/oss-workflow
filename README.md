# Open Source Workflow

- [Third Party Contribution](#third-party-contribution)
- [Open Source A Library Or An Application](#Open-Source-A-Library-Or-An-Application)

## Third Party Contribution

You are encouraged to contribute to third party repositories during your work time:
- The subject must be related to a problem of your project or work
- Your manager must be notified

## Open Source A Library Or An Application

Workflow to follow in order to **Open Source** a library or an application.

### Why a workflow

This workflow help to align all the actors of an entity on the same objectives.

whithout a workflow :
![Why a workflow](./images/why-workflow-1.png)

with a workflow :
![Why a workflow](./images/why-workflow-2.png)

## 1) Prerequisites

Please consider to be **Open Source First**:
- More feedbacks
- Iterate quicker (open source does not mean to be perfect, but on the way to be perfect quicker)

### Prerequisites for starting a new pure technical asset "Open Source First"

- No business rule specific to AXA
- License ([MIT](https://github.com/AxaGuilDEv/react-oidc/blob/master/LICENSE) / Apache v2)
- Mandatory files : README.md, CONTRIBUTING.md, CODE_OF_CONDUCT.md, LICENCE.md, CHANGELOG.md, Templates : Issues, PR
- At least one “Repository Maintainer“

### Prerequisites for an existing internal technical asset

- No business rule specific to AXA
- Code quality & practices
  - At least 60% of code coverage
- CI (Continuous Integration) with all the internal tools
- License ([MIT](https://github.com/AxaGuilDEv/react-oidc/blob/master/LICENSE) / Apache v2)
- Mandatory files : README.md, CONTRIBUTING.md, CODE_OF_CONDUCT.md, LICENCE.md, CHANGELOG.md, Templates : Issues, PR
- At least one “Repository Maintainer“

![Workflow step 1](./images/workflow-step1.png)

## 2) Validations

- Technical director of the entity
- Communities of practice:
  - Security
  - Software Craftmanship

![Workflow step 2](./images/workflow-step2.png)

## 3) Team/Maintainer Must

- Use and force two factor Authentication everywhere it is possible: github, npm, nuget, etc.
- Tokens must be kept private
- Set up and maintain CI / CD
  - use Github Action
  - use https://sonarcloud.io/organizations/axaguildev
- Manage the roadmap
- Manage “Issues” and “PullRequests”
- Help to grow the community

![Workflow step 3](./images/workflow-step3.png)

## 4) Mentality

- Going Open Source brings and requires a change of mentality within development teams.

![Workflow step 4](./images/workflow-step4.png)
