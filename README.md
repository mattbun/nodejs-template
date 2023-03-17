# nodejs-template

`typescript` / `jest` / `semantic-release` / `github actions` / `prettier` / `renovate`

## Getting Started (Development)

1. `yarn install`
2. `yarn build`
3. `yarn start`

## Getting Docker Builds to Work

Add the following secret to the repository's settings in GitHub:

- `GH_PAT` - [Create a GitHub personal access token.](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token) It only needs the `public_repo` permission (this might mean the repo can't be private? Haven't tested it).

Images are pushed to GitHub Container Registry (ghcr.io):

```shell
docker pull ghcr.io/mattbun/nodejs-template
```

You can browse image tags for this repository [here](https://github.com/mattbun/nodejs-template/pkgs/container/nodejs-template).
