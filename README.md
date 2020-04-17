[![Netlify Status](https://api.netlify.com/api/v1/badges/c6d91f1e-c973-4fb5-8be4-33220497aa07/deploy-status)](https://app.netlify.com/sites/belajartypescript/deploys)

# Website

Belajar Typescript dibuat dengan [Docusaurus 2](https://v2.docusaurus.io/)

### Installation

```
$ yarn
$ yarn start
$ yarn build
```

This command generates static content into the `build` directory and can be served using any static contents hosting service.

### Deployment

```
$ GIT_USER=<Your GitHub username> USE_SSH=true yarn deploy
```

If you are using GitHub pages for hosting, this command is a convenient way to build the website and push to the `gh-pages` branch.

### Searching Build

```
$ yarn build
$ node build-search-data.js
```

Update your index of searching using lunr.js!

### Netlify

```
https://belajartypescript.netlify.app/
```
