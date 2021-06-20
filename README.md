# nodejs-template

`typescript` / `jest` / `semantic-release` / `github actions`

## Getting Started

1. `yarn install`
2. `yarn build`
3. `yarn start`

## Getting Docker Builds to Work

Add the following secrets to the repository's settings in GitHub:

- `DOCKERHUB_TOKEN` - Log into Docker Hub, go to [security settings](https://hub.docker.com/settings/security) and create an access token
- `DOCKERHUB_USERNAME` - Your docker hub username
- `GH_PAT` - [Create a GitHub personal access token.](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token) It only needs the `public_repo` permission (this might mean the repo can't be private? Haven't tested it).
