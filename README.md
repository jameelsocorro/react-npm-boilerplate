# react-npm-boilerplate

### A simple boilerplate template for creating npm packages using react.

<br/>

## Install

First, clone the repo via git:

```bash
git clone --depth=1 https://github.com/jameelsocorro/react-npm-boilerplate.git your-package-name
```

And then install dependencies with yarn.

```bash
$ cd your-package-name
$ yarn
```
**Note**: If you can't use [yarn](https://github.com/yarnpkg/yarn) for some reason, try `npm install`.

<br/>

## Linking the library locally

I use [Alan Smith](https://github.com/alanbsmith)'s playground for testing the package locally.

```bash
$ git clone git@github.com:alanbsmith/component-lib-playground.git
$ cd component-lib-playground
$ yarn
```

**Note**: If you can't use [yarn](https://github.com/yarnpkg/yarn) for some reason, try `npm install`.

<br/>

Now let's link the playground app to our package library.

```bash
$ npm link your-package-name
```

You can see the full tutorial for linking the library [here](https://hackernoon.com/building-a-react-component-library-part-2-46fd4f77bb5c)

<br/>

## License

[MIT](https://github.com/jameelsocorro/react-npm-boilerplate/blob/master/LICENSE)
