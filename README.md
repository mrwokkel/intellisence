# Monorepo intellisense issue

Monorepo to point to VSCode intellisense issue when working with WindiCSS in monorepo.

## Description

When I open VSCode at monorepo root level the intellisense is not working.
When I cd to a project in the workspace and open VSCode intellisense IS working.

Also I ran into the problem that, if the windi.config.js is created with `defineConfig` the intellisense is not working
at all.

## Developing

This is a monorepo meaning the repo holds multiple packages. It requires the use of [pnpm](https://pnpm.js.org/en/). You can [install pnpm](https://pnpm.io/installation) with:

```bash
npm i -g pnpm
```

`pnpm` commands run in the project's root directory will run on all sub-projects. You can checkout the code and build all sub-projects with:

```bash
git clone git@github.com:mrwokkel/intellisence.git
cd intellisence
pnpm install
pnpm build
```