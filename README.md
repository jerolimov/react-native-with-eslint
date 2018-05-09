# react-native example project with ESLint configuration

[![Build Status](https://travis-ci.org/jerolimov/react-native-with-eslint.svg?branch=master)](https://travis-ci.org/jerolimov/react-native-with-eslint)

This project contains an "bare" [react-native](http://facebook.github.io/react-native/)" projects
with enabled [ESLint](https://eslint.org/) configuration.

## Step by step

*   Create your react-native app:
    *   Run `react-native init Tutorial`
*   Add ESLint runtime and plugins.
    *   With npm: `npm install --save-dev eslint babel-eslint eslint-plugin-react eslint-plugin-react-native`
    *   Alternative with yarn: `yarn add --dev eslint babel-eslint eslint-plugin-react eslint-plugin-react-native`
*   Add an ESLint configuration file, like this [.eslintrc.js](./eslintrc.js)
*   Add a `lint` run script to your [package.json](package.json)
*   Run the linter:
    *   With npm `npm run lint`
    *   or with yarn: `yarn run lint`
