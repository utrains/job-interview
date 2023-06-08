# Project Description

## Continuous integration
Set up a new repository and CI pipeline using any code version provider specified below:
- Github Actions
- Gitlab CI/CD
- CircleCI
- Azure DevOps

The CI steps should be created and triggered for any pull request. The pipeline should run the following steps:
- Install dependencies npm install 
- Linter (ESLint) npm run lint
- Formatter (Prettier) npm run prettier
- Test (Jest) CI=true npm run test
- Build npm run build

The pipeline should be successful.

Please provide some pull requests to show pass or fail status in the CI pipeline.

## Continuous deployment

Deploy the application in your AWS Account using Terraform platform.
The Terraform should at least create three environments (devel, stage, and prod which is the main). Each environment should be related to the three new branches with the same name.

The application needs to be:

    1. Available via HTTPS protocol
    2. Available for anyone with Internet access only during the challenge recording

The AWS resource type is a free choice since it meets the expected requirements.
