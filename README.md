# react-app-boilerplate

**Easily start building your React application using this opinionated boilerplate.**

What's included:

* Webpack and Babel for generating a bundle of your application in ES5
* ESLint and Husky for code linting
* Sass support and Autoprefixer for simple styling

*My boilerplate for React **component libraries** can be found [here](https://github.com/samuelmeuli/react-library-boilerplate).*


## Requirements

You need to have Node.js and Yarn installed.


## Usage

To use this boilerplate for creating your own application, execute the following commands (and replace `my-app` with the name of your application):

```sh
git clone https://github.com/samuelmeuli/react-app-boilerplate my-app
```

Clean up the files from this repository and install the dependencies:

```sh
cd my-app
rm -rf .git README.md
yarn install
```

Execute the start script to bundle your application and start your development server:

```sh
yarn start
```

Finally, open http://localhost:3000 to see your component in action.
