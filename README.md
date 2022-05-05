# JS/TS Monorepos

## What's this course about?

This repo is intended to demostrate the usage of modern
JavaScript and TypeScript monorepos, their use cases and related tools.

## Project setup

First, you should ensure you have [your ssh keys working with GitHub](https://docs.github.com/en/free-pro-team@latest/github/authenticating-to-github/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent). You can verify this by running

### Tools

Next, make sure you have installed [volta](http://volta.sh/) which ensures you have the right version of node and yarn for this project. You can run:

```
volta install node
```

and then:

```
volta install yarn
```

To get the right versions for this workshop.

We also strongly recommend the use of [Visual Studio Code](https://code.visualstudio.com/) as an authoring tool. If you use something else, you're on your own.

### Clone

Next, checkout a working copy of this project

```sh
git clone git@github.com:mike-north/js-ts-monorepos
```

enter the directory you just created

```sh
cd js-ts-monorepos
```

### Install dependencies

[`yarn`](https://yarnpkg.com/) is the recommended package manager to use with this project. Please use it instead of npm.

Install dependencies with yarn by running

```sh
yarn
```

### Starting the project

Start up the project in development mode by running

```sh
yarn dev
```

Changing any files in the `src` folder will result in an incremental rebuild, and a refresh of the screen.

By default, the app is served on https://localhost:1234.
