[![Netlify Status](https://api.netlify.com/api/v1/badges/52edb431-af5b-4629-bd4f-ba96e1380584/deploy-status)](https://app.netlify.com/sites/novvum-whills/deploys)

<p align="center"><img src="https://i.imgur.com/9VOxx5E.png" width="300px"/></p>
<h1 align="center">The Novvum Whills</h1>

A place for documenting guides, tutorials, and process related to [Novvum](https://www.novvum.io).

> Live site [here](https://whills.novvum.io)

## Under the hood

- Configured to deploy to netlify on novvum-whills.netlify.com

## How to run locally

The novvum whills client is configured with yarn workspaces. Please run all of the following scripts from the root of the directory.

**1. Install Dependencies**

```sh
yarn
```

**2. Development**

```sh
yarn dev
```

**Clean**
_Removes gatsby generated `public` and `cache` and `yarn.error.logs` subdirectories _

```sh
yarn clean
```

## Where to find stuff

**Markdown & MDX files**
All `md` & `mdx` files are found under [`content/*`](https://github.com/Novvum/whills/tree/master/content)

## Roadmap

- [x] Deploy to Netlify
- [x] File Structure
- [ ] Contributor guide
- [ ] Documentation on frontmatter
- [x] Seperate theme into it's own gatsby-theme under `~/themes/@novvum/docz-theme`
- [ ] Figure out a better method for contributing docs
- [ ] Configure a better incorporation of `react-code-blocks` without relying on `wrapRootElement`
