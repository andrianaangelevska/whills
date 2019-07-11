<p align="center"><img src="https://i.imgur.com/9VOxx5E.png" width="300px"/></p>
<h1 align="center">The Novvum Whills</h1>       

A place for documenting guides, tutorials, and process related to [Novvum](https://www.novvum.io). 

> Live site [here](https://whills.netlify.com)

## Under the hood
- Uses [docz](https://www.docz.site/) along with their [`gatsby-theme-docz`](https://www.docz.site/docs/gatsby-theme)
- A custom docz theme under `clients/whills/src/themes`
- Configured to deploy to netlify on whills.netlify.com

## How to run locally
The novvum whills client is configured with yarn workspaces. Please run all of the following scripts from the root of the directory.

**1. Install Dependencies**
```sh
yarn
```
**2. Development**
```sh
yarn whills develop
```

**Clean**
_Removes gatsby generated `public` and `cache` and `yarn.error.logs` subdirectories _
```sh
yarn whills clean
```

## Where to find stuff

**Markdown & MDX files**
All `md` & `mdx` files are found under [`src/pages/*`](https://github.com/Novvum/novvum/tree/master/clients/whills/src/pages)

**Theme**
The docz theme related materials are found under [`src/theme/*`](https://github.com/Novvum/novvum/tree/master/clients/whills/src/theme)




## Roadmap
- [x] Deploy to Netlify
- [ ] File Structure
- [ ] Contributor guide
- [ ] Documentation on frontmatter
- [ ] Seperate theme into it's own gatsby-theme under `~/themes/@novvum/docz-theme`
- [ ] Figure out a better method for contributing docs
- [ ] Configure a better incorporation of `react-code-blocks` without relying on `wrapRootElement`
