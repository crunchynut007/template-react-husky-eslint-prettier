# React + Vite + eslint + prettier + husky + lint-staged

This template provides a minimal setup to get React working in Vite with HMR and some ESLint & prettier rules, and husky. It also included a github workflows config file to publish your repo to github pages.

## Getting started:

### Duplicate to your repo

To make a mirror of this template into a new repo run:

```bash
# clone the template
git clone --bare https://github.com/crunchynut007/template-react-husky-eslint-prettier.git

# push template to a new repo with a new name
cd template-react-husky-eslint-prettier.git
git push --mirror https://github.com/<USERNAME>/<NEW REPO>.git

# remove the template you created earlier
rm -rf template-react-husky-eslint-prettier.git
```

Source: https://docs.github.com/en/repositories/creating-and-managing-repositories/duplicating-a-repository

### Install and start coding

Clone your new repo (if not already) then install dependencies to get started:

```bash
# clone your new repo
git clone https://github.com/<USERNAME>/<NEW REPO>.git

# install node and dependencies
cd <REPO>.git
npm install

# test it works
npm run dev
```

The following dependencies will be installed:

- react
- vite
- husky
- lint-staged
- eslint
- prettier
- eslint-config-prettier

## Template Configuration

This template configuration was based on configuration files from:
https://blog.stackademic.com/adding-eslint-and-prettier-to-a-vitejs-react-project-84a0752c0fc5

Husky setup:
https://gist.github.com/shahsagarm/4017ae2a918d15b673299be400157062
https://typicode.github.io/husky/getting-started.html
