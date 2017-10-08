# react-npm-boilerplate

### A simple boilerplate template for creating npm packages using react.

<br/>

## Install

First, clone the repo via git:

```bash
git clone --depth=1 https://github.com/jameelsocorro/react-npm-boilerplate.git your-component-name
```
Don't forget to modify **package.json** with your settings first.

```bash
{
  "name": "your-component-name",
  "version": "0.0.1",
  "description": "Put a description here",
  "author": {
    "name": "Your name",
    "email": "your email"
  }
}
```

And then install dependencies.

```bash
$ npm i
$ npm run build
```

### Make component linkable locally

```bash
$ npm link
```

<br/>

## Test your component

Create a playground project so you could test your component. **(This should be in different directory from your component)**

```bash
$ npm i -g create-react-app
$ npm create-react-app react-component-playgrounds
$ cd react-component-playgrounds
```
**Note**: if you have already have a create-react-app installed globally, you may skip the `npm i -g create-react-app`.

Now let's link the playground app to our package library.

```bash
$ npm link your-package-name
```

Finally, run the playground and play with your component. Happy Coding!

```bash
$ npm start
```

<br/>

## License

[MIT](https://github.com/jameelsocorro/react-npm-boilerplate/blob/master/LICENSE)
