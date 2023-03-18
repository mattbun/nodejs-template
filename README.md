# nodejs-template

`typescript` / `jest` / `semantic-release` / `github actions` / `prettier` / `renovate`

## Getting Started (Development)

1. `yarn install`
2. `yarn build`
3. `yarn start`

## Docker Images

To enable automated docker builds, add the following secret to the repository's settings:

- `GH_PAT` - [Create a GitHub personal access token.](https://docs.github.com/en/github/authenticating-to-github/keeping-your-account-and-data-secure/creating-a-personal-access-token) It only needs the `public_repo` permission (this might mean the repo can't be private? Haven't tested it).

### Pulling Images

Images are pushed to GitHub Container Registry ([ghcr.io](https://ghcr.io)). To pull an image:

```shell
docker pull ghcr.io/mattbun/nodejs-template
```

### Browse Image Tags

You can browse image tags for this repository [here](https://github.com/mattbun/nodejs-template/pkgs/container/nodejs-template).

### Image Tagging

* `latest` - the most recent release
* `1.2.3` - a specific release
* `1.2` - the most recent patch release of a specific minor version
* `main` - the current state of the `main` branch (you probably don't want to use this)
